# Awesome-Wireframing-Mockup-Software

## Top Wireframing & Mockup Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Low-Fidelity Wireframing, Collaborative Design & Self-Hosted UI Prototyping*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Wireframing & Mockup Software**. These tools enable product managers, designers, and developers to sketch UI layouts, map user flows, and prototype interfaces—turning abstract requirements into tangible screens before committing to high-fidelity design or code.



**Examples** include Balsamiq for Confluence, Figma, Miro, Lucidchart, Sketch, Moqups, Axure RP, Whimsical, Marvel, and InVision (the category leaders).



**Open-source emphasis**: Wireframing & Mockup Software is a domain where open-source tooling is **genuinely viable but bifurcated by workflow philosophy**. **Penpot** stands out as the most complete open-source Figma alternative—self-hostable, SVG-native, with native CSS Grid/Flexbox handoff and real-time collaboration, making it the default recommendation for teams wanting a full design platform . For **text-first wireframing**, **wiremd** lets you write mockups in Markdown and export to Figma-native JSON, HTML, or React, with a Balsamiq-style sketch theme . **Wireloom** (Stardock, MIT) renders indentation-based wireframe blocks as inline SVG directly in Markdown, designed explicitly for AI agents sketching UIs in chat and PRs . **Telva** is an embeddable React design canvas with live React components as canvas shapes, positioning itself as a self-hostable, MIT-licensed Figma alternative . The critical caveat: **Pencil Project**, long the go-to desktop open-source wireframing tool, is marked **Discontinued** .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Balsamiq for Confluence](https://balsamiq.com/)**  

  Low-fidelity wireframing tool integrated into Atlassian Confluence; known for its intentional "sketchy" aesthetic that keeps stakeholders focused on structure rather than visual polish.



- **[Figma](https://www.figma.com/)**  

  Industry-standard collaborative design platform with wireframing capabilities, component libraries, and developer handoff; proprietary and per-seat priced, but dominates the design tool market .



- **[Miro](https://miro.com/)**  

  Infinite-canvas whiteboard with a dedicated Wireframe Library; best for teams that wireframe during live brainstorming sessions, though it lacks the precision and layer management of dedicated design tools .



- **[Lucidchart](https://www.lucidchart.com/)**  

  Diagramming and visual collaboration platform with wireframing shapes and templates for UI flows and architecture.



- **[Sketch](https://www.sketch.com/)**  

  Mac-only design tool with wireframing and prototyping capabilities; historically popular before Figma's cross-platform dominance.



- **[Moqups](https://moqups.com/)**  

  All-in-one wireframing, mockup, and diagramming suite with a stencil library that rivals Balsamiq's ease of use; free plan is limited to 2 projects and 400 objects .



- **[Axure RP](https://www.axure.com/)**  

  High-fidelity prototyping tool with interactive logic and dynamic content; heavier than wireframing tools but suited for complex interactive specifications.



- **[Whimsical](https://whimsical.com/)**  

  Collaborative workspace for flowcharts, wireframes, and sticky notes; focused on "speed of thought" rapid wireframing with pre-built components .



- **[Marvel](https://marvelapp.com/)**  

  Prototyping and design platform for turning sketches and wireframes into interactive mobile and web prototypes.



- **[InVision](https://www.invisionapp.com/)**  

  Prototyping and collaboration platform (historically popular for design handoff); **caution**: InVision announced it is shutting down at the end of 2024, so verify current status before adopting.



## Open-Source GitHub Projects



### Full Design Platforms (Figma/Balsamiq Alternatives)



- **[Penpot](https://github.com/penpot/penpot)**  

  The most complete open-source design platform (MPL-2.0) and the default recommendation for teams seeking a self-hostable Figma alternative . Features: **SVG-native architecture** (designs are real SVG, not proprietary vectors), native **CSS Grid and Flexbox** layout (not a proprietary Auto Layout wrapper), real-time collaboration, reusable components, design tokens, plugins, and a self-hosted option with no tracking . The Inspect tab produces near-production-ready HTML/CSS instantly, eliminating the Figma-to-code translation layer that often misrepresents spacing and positioning . **Best for teams wanting a full design system tool without per-seat pricing**—smaller plugin ecosystem than Figma, and lacks the intentional "sketchy" aesthetic of Balsamiq .



- **[Telva](https://github.com/vmaspad/telva)**  

  Production-grade, **embeddable React design canvas** (MIT) positioned as a self-hostable Figma alternative . The killer feature: **live React components as first-class canvas shapes**—not iframes, but your actual component tree rendered on an infinite canvas, responding to input and fetching data . Features rectangle/ellipse/triangle/arrow/text/sticky/image/video shapes, infinite canvas with pan/zoom, layers panel, multi-page support, undo/redo, snap-to-grid, PNG/SVG export, dark/light theming, and **real-time multiplayer via Liveblocks or custom backend** . **Best for developers wanting to embed a design canvas inside their own product**—not a standalone desktop app, but a component you drop into a React application.



### Text-First & Markdown Wireframing



- **[wiremd](https://github.com/akonan/wiremd)**  

  Open-source **text-first UI design tool** for developers who think in code (MIT) . Write wireframes as Markdown, then export to **Figma-native designs via a plugin** (fully editable frames and components with auto-layout), HTML with Tailwind, JSON AST, or React . Includes visual themes: **Sketch** (Balsamiq-style hand-drawn look), Clean, Wireframe (traditional grayscale), and Minimal . Also ships an **Obsidian plugin** for live previews inside notes . **Best for developers and technical writers who prefer typing over dragging**—not a visual editor, but a fast way to generate wireframes from structured text.



- **[Wireloom](https://github.com/StardockCorp/Wireloom)**  

  Open-source Markdown extension from Stardock (MIT) that renders **UI wireframes as inline SVG** from indentation-based `wireloom` code blocks . Designed explicitly for **AI agents sketching UIs in chat, notes, and PRs**—where ASCII art breaks in proportional fonts and PNG images cost tens of thousands of tokens, a Wireloom block for a full settings dialog is ~300 tokens of source . Syntax: quoted strings are labels, bare words are flags, indentation defines structure. Static by design (no click handlers or state) . **Best for AI-assisted workflows and documentation-embedded wireframes**—not a collaborative design tool.



### Additional Strong Open-Source Options



- **mydraft.cc** — Open-source wireframing tool written in TypeScript, React, and Redux (862 GitHub stars, actively updated October 2026) . **A lightweight browser-based wireframing tool**—verify feature depth and maintenance cadence before production adoption.

- **Open Pencil** — Open-source design editor with vector and interface projects, AI-powered generation, `.fig`/`.pen` file support, design-to-code export, and real-time P2P collaboration (MIT) . **A newer entrant**—check maturity and community size.

- **Pencil Project** — **CAUTION: Discontinued** . Long-standing desktop wireframing tool (GPL-2.0) for Mac/Windows/Linux, but no longer actively maintained. Avoid for new projects.



**Frameworks for building custom systems**: For a **full Figma-like design platform**, Penpot is the most mature open-source choice with SVG-native architecture and CSS-native handoff . For **embedding a design canvas in a React product**, Telva provides a self-hostable component with live React shapes . For **text-first wireframing from Markdown**, wiremd exports to Figma and HTML . For **AI-agent-friendly wireframes in documentation**, Wireloom renders inline SVG from Markdown blocks . No open-source project replicates Balsamiq's specific low-fidelity sketch aesthetic as a dedicated standalone tool—Penpot's design system focus and wiremd's theme option are the closest approximations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Wireframing tools handling design files and user research data should consider access controls for sensitive product plans; self-hosted tools require proper server hardening and backup strategies.

- **Open-source wireframing is strongest for full design platforms and text-first workflows**—Penpot provides a production-ready Figma alternative , Telva offers an embeddable canvas , and wiremd/Wireloom enable Markdown-based wireframing . However, **Pencil Project is discontinued**, and no open-source tool matches Balsamiq's dedicated low-fidelity sketch aesthetic out of the box . Teams requiring Balsamiq-style sketching should evaluate commercial tools or use wiremd's Sketch theme.

- Verify license terms for commercial use; Penpot uses MPL-2.0 , Telva uses MIT , wiremd is MIT , and Wireloom uses MIT .



---



**Made for product managers, UX designers, developers, and teams sketching interfaces before code.**  

Let's make wireframing more open, but with clear eyes about the discontinued tools and aesthetic gaps that remain.
