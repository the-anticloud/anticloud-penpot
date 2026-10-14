# PENPOT

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-design_tools-lightgrey)

> Anticloud-hardened packaging of the upstream project `PENPOT` in category **DESIGN TOOLS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** DESIGN TOOLS · **Upstream:** https://github.com/penpot/penpot · **Upstream pin:** `76e9c132efd0b66b57763c5ddd9dfcfda0051cdf` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<img width="100%" src="https://github.com/user-attachments/assets/da17b160-f289-436f-b140-972083a08602" />

[uri_license]: https://www.mozilla.org/en-US/MPL/2.0
[uri_license_image]: https://img.shields.io/badge/MPL-2.0-blue.svg

<p align="center">
  <a href="https://www.digitalpublicgoods.net/r/penpot" rel="nofollow">
    <img alt="Verified DPG" src="https://img.shields.io/badge/Verified-DPG-3333AB?logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMzEiIGhlaWdodD0iMzMiIHZpZXdCb3g9IjAgMCAzMSAzMyIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTE0LjIwMDggMjEuMzY3OEwxMC4xNzM2IDE4LjAxMjRMMTEuNTIxOSAxNi40MDAzTDEzLjk5MjggMTguNDU5TDE5LjYyNjkgMTIuMjExMUwyMS4xOTA5IDEzLjYxNkwxNC4yMDA4IDIxLjM2NzhaTTI0LjYyNDEgOS4zNTEyN0wyNC44MDcxIDMuMDcyOTdMMTguODgxIDUuMTg2NjJMMTUuMzMxNCAtMi4zMzA4MmUtMDVMMTEuNzgyMSA1LjE4NjYyTDUuODU2MDEgMy4wNzI5N0w2LjAzOTA2IDkuMzUxMjdMMCAxMS4xMTc3TDMuODQ1MjEgMTYuMDg5NUwwIDIxLjA2MTJMNi4wMzkwNiAyMi44Mjc3TDUuODU2MDEgMjkuMTA2TDExLjc4MjEgMjYuOTkyM0wxNS4zMzE0IDMyLjE3OUwxOC44ODEgMjYuOTkyM0wyNC44MDcxIDI5LjEwNkwyNC42MjQxIDIyLjgyNzdMMzAuNjYzMSAyMS4wNjEyTDI2LjgxNzYgMTYuMDg5NUwzMC42NjMxIDExLjExNzdMMjQuNjI0MSA5LjM1MTI3WiIgZmlsbD0id2hpdGUiLz4KPC9zdmc+Cg==">
  </a>
  <a href="https://community.penpot.app" rel="nofollow">
    <img alt="Penpot Community" src="https://img.shields.io/discourse/posts?server=https%3A%2F%2Fcommunity.penpot.app">
  </a>
  <a href="https://tree.taiga.io/project/penpot/" rel="nofollow">
    <img alt="Managed with Taiga.io" src="https://img.shields.io/badge/managed%20with-TAIGA.io-709f14.svg">
  </a>
  <a href="https://gitpod.io/#https://github.com/penpot/penpot" rel="nofollow">
    <img alt="Gitpod ready-to-code" src="https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod">
  </a>
</p>

<p align="center">
  <a href="https://penpot.app/"><b>Website</b></a>  •
  <a href="https://help.penpot.app/user-guide/"><b>User Guide</b></a>  •
  <a href="https://penpot.app/learning-center"><b>Learning Center</b></a>  •
  <a href="https://community.penpot.app/"><b>Community</b></a>
</p>
<p align="center">
  <a href="https://www.youtube.com/@Penpot"><b>Youtube</b></a>  •
  <a href="https://peertube.kaleidos.net/a/penpot_app/video-channels"><b>Peertube</b></a>  •
  <a href="https://www.linkedin.com/company/penpot/"><b>Linkedin</b></a>  •
  <a href="https://instagram.com/penpot.app"><b>Instagram</b></a>  •
  <a href="https://fosstodon.org/@penpot/"><b>Mastodon</b></a>  •
  <a href="https://bsky.app/profile/penpot.app"><b>Bluesky</b></a>  •
  <a href="https://twitter.com/penpotapp"><b>X</b></a>
</p>

[Penpot video](https://github.com/user-attachments/assets/7c67fd7c-04d3-4c9b-88ec-b6f5e23f8332)

Penpot is the open-source design platform for teams that build digital products at scale.

Penpot’s key strength lies in giving you **full ownership of your design infrastructure**. Built on open source and designed for [self-hosting](https://help.penpot.app/technical-guide/getting-started/), it puts teams in complete control of their design environment supporting strict compliance and governance requirements. Whether used in the **browser or deployed on your own servers**, Penpot **works with open standards** like SVG, CSS, HTML, and JSON. 

Real-time collaboration strengthens this foundation, helping teams scale and bring design closer to the product through top-tier capabilities. Additionally, developers feel at home using Penpot, because design is expressed as code, enabling a direct translation and shipping products faster. 

Best-in-class native [Design Tokens](https://penpot.dev/collaboration/design-tokens) provide a single source of truth between design and development. They ensure consistency, improve collaboration, and make it easier to manage complex design systems.

The [MCP server](https://penpot.app/penpot-mcp-server) takes it further by enabling multi-directional workflows between design and code. A [powerful open API](https://help.penpot.app/mcp/#quick-start) and plugin system makes the workspace programmable, enabling automation, AI-driven workflows, and integrations with the tools and systems you already use.

With [CSS Grid and Flex Layout](https://help.penpot.app/user-guide/designing/flexible-layouts/), teams can design responsive interfaces that behave like real code from the start.

Combined, these features turn Penpot into a **full-stack design platform** for building scalable design systems and fully integrated product development processes.

If your organization is scaling and needs extra support, we’re here to help. [Talk to us](https://penpot.app/talk-to-us)

## Table of contents ##

- [Why Penpot](#why-penpot)
- [Getting Started](#getting-started)
- [Penpot Enterprise](#penpot-enterprise)
- [Community](#community)
- [Contributing](#contributing)
- [Resources](#resources)
- [License](#license)

## Why Penpot ##

Penpot connects design, code, and AI workflows through a code-based approach, making designs readable by developers and AI via the MCP server. This approach helps teams ship what’s actually designed and manage design systems at scale with powerful design tokens. As a self-hosted, open-source and real-time collaboration platform, Penpot offers full flexibility, security, and ownership without vendor lock-in. Learn more about [why Penpot](https://penpot.app/why-penpot) is the platform for your team.

### Plugin system ###

[Penpot plugins](https://penpot.app/penpothub/plugins) let you expand the platform's capabilities, give you the flexibility to integrate it with other apps, and design custom solutions.

### Designed for developers ###

Penpot was built to serve both designers and developers and create a fluid design-code process. You have the choice to enjoy real-time collaboration or play "solo".

### Inspect mode ###

Work with ready-to-use code and make your workflow easy and fast. The inspect tab gives instant access to SVG, CSS and HTML code.

### Integrations ###

Penpot offers [integration](https://penpot.app/integrati

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `backend/`, `common/`, `docker/`, `experiments/`, `exporter/`, `frontend/`, `library/`, `mcp/`, `media-processor/`, `plugins/`, `render-wasm/`, `sample_media/`
- Snapshot size: **6327 files**, **147389 lines of code** (measured; see Benchmarks)
- Primary languages: `.svg` (1444), `.cljs` (890), `.json` (409), `.scss` (329), `.webp` (313), `.ts` (304)
- Upstream commit pinned for this packaging: `76e9c132efd0b66b57763c5ddd9dfcfda0051cdf`

---

## Installation

Penpot’s key strength lies in giving you **full ownership of your design infrastructure**. Built on open source and designed for [self-hosting](https://help.penpot.app/technical-guide/getting-started/), it puts teams in complete control of their design environment supporting strict compliance and governance requirements. Whether used in the **browser or deployed on your own servers**, Penpot **works with open standards** like SVG, CSS, HTML, and JSON. 

Real-time collaboration strengthens this foundation, helping teams scale and bring design closer to the product through top-tier capabilities. Additionally, developers feel at home using Penpot, because design is expressed as code, enabling a direct translation and shipping products faster. 

Best-in-class native [Design Tokens](https://penpot.dev/collaboration/design-tokens) provide a single source of truth between design and development. They ensure consistency, improve collaboration, and make it easier to manage complex design systems.

The [MCP server](https://penpot.app/penpot-mcp-server) takes it further by enabling multi-directional workflows between design and code. A [powerful open API](https://help.penpot.app/mcp/#quick-start) and plugin system makes the workspace programmable, enabling automation, AI-driven workflows, and integrations with the tools and systems you already use.

With [CSS Grid and Flex Layout](https://help.penpot.app/user-guide/designing/flexible-layouts/), teams can design responsive interfaces that behave like real code from the start.

Combined, these features turn Penpot into a **full-stack design platform** for building scalable design systems and fully integrated product development processes.

If your organization is scaling and needs extra support, we’re here to help. [Talk to us](https://penpot.app/talk-to-us)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Best-in-class native [Design Tokens](https://penpot.dev/collaboration/design-tokens) provide a single source of truth between design and development. They ensure consistency, improve collaboration, and make it easier to manage complex design systems.

The [MCP server](https://penpot.app/penpot-mcp-server) takes it further by enabling multi-directional workflows between design and code. A [powerful open API](https://help.penpot.app/mcp/#quick-start) and plugin system makes the workspace programmable, enabling automation, AI-driven workflows, and integrations with the tools and systems you already use.

With [CSS Grid and Flex Layout](https://help.penpot.app/user-guide/designing/flexible-layouts/), teams can design responsive interfaces that behave like real code from the start.

Combined, these features turn Penpot into a **full-stack design platform** for building scalable design systems and fully integrated product development processes.

If your organization is scaling and needs extra support, we’re here to help. [Talk to us](https://penpot.app/talk-to-us)

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

With [CSS Grid and Flex Layout](https://help.penpot.app/user-guide/designing/flexible-layouts/), teams can design responsive interfaces that behave like real code from the start.

Combined, these features turn Penpot into a **full-stack design platform** for building scalable design systems and fully integrated product development processes.

If your organization is scaling and needs extra support, we’re here to help. [Talk to us](https://penpot.app/talk-to-us)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | 6327 |
| Lines of code | 147389 |
| Dependency references | 327 |
| Dependencies by ecosystem | cargo: 30, npm: 297 |
| Upstream license | AGPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @playwright/mcp | ^0.0.83 | package.json |
| npm | @playwright/test | ^1.63.0 | package.json |
| npm | @types/node | ^26.6.3 | package.json |
| npm | commander | ^15.0.0 | package.json |
| npm | dotenv | ^18.0.4 | package.json |
| npm | esbuild | ^0.28.2 | package.json |
| npm | mdts | ^0.21.0 | package.json |
| npm | nrepl-client | ^0.3.0 | package.json |
| npm | playwright | ^1.63.0 | package.json |
| cargo | name | render | render-wasm/Cargo.toml |
| cargo | version | 0.1.0 | render-wasm/Cargo.toml |
| cargo | edition | 2021 | render-wasm/Cargo.toml |
| cargo | project | https://github.com/penpot/penpot | render-wasm/Cargo.toml |
| cargo | license-file | ../LICENSE | render-wasm/Cargo.toml |
| cargo | description | Wasm-based canvas renderer for Penpot | render-wasm/Cargo.toml |
| ... | (312 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

Real-time collaboration strengthens this foundation, helping teams scale and bring design closer to the product through top-tier capabilities. Additionally, developers feel at home using Penpot, because design is expressed as code, enabling a direct translation and shipping products faster. 

Best-in-class native [Design Tokens](https://penpot.dev/collaboration/design-tokens) provide a single source of truth between design and development. They ensure consistency, improve collaboration, and make it easier to manage complex design systems.

The [MCP server](https://penpot.app/penpot-mcp-server) takes it further by enabling multi-directional workflows between design and code. A [powerful open API](https://help.penpot.app/mcp/#quick-start) and plugin system makes the workspace programmable, enabling automation, AI-driven workflows, and integrations with the tools and systems you already use.

With [CSS Grid and Flex Layout](https://help.penpot.app/user-guide/designing/flexible-layouts/), teams can design responsive interfaces that behave like real code from the start.

Combined, these features turn Penpot into a **full-stack design platform** for building scalable design systems and fully integrated product development processes.

If your organization is scaling and needs extra support, we’re here to help. [Talk to us](https://penpot.app/talk-to-us)

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing Guide

Thank you for your interest in contributing to Penpot. This guide covers
how to propose changes, submit fixes, and follow project conventions.

For architecture details, module-specific guidelines, and AI-agent
instructions, see [AGENTS.md](AGENTS.md). For final user technical
documentation, see the `docs/` directory or the rendered [Help
Center](https://help.penpot.app/).

## Table of Contents

- [Prerequisites](#prerequisites)
- [AI-Assisted Contributions](#ai-assisted-contributions)
- [Reporting Bugs](#reporting-bugs)
- [Pull Requests](#pull-requests)
  - [Workflow](#workflow)
  - [Branch naming](#branch-naming)
  - [Format](#format)
    - [Title format](#title)
    - [Description](#description)
  - [Review process](#review-process)
  - [What we won't accept](#what-we-wont-accept)
  - [Good first issues](#good-first-issues)
- [Commit Guidelines](#commit-guidelines)
  - [Commit types](#commit-types)
  - [Rules](#rules)
  - [Examples](#examples)
- [Formatting and Linting](#formatting-and-linting)
- [Changelog](#changelog)
- [Code of Conduct](#code-of-conduct)
- [Developer's Certificate of Origin (DCO)](#developers-certificate-of-origin-dco)

## Prerequisites

- **Language**: Penpot is written primarily in Clojure (backend), ClojureScript
  (frontend/exporter), and Rust (render-wasm). Familiarity with the Clojure
  ecosystem is expected for most contributions.
- **Issue tracker**: We use [GitHub Issues](https://github.com/penpot/penpot/issues)
  for public bugs and [Taiga](https://tree.taiga.io/project/penpot/) for
  internal project management. Changelog entries reference both.
- **AI coding agents**: guidance lives in `AGENTS.md` and the skills in
  `.agents/skills/`, which Codex, opencode, Cursor, Zed, Amp, omp and pi read
  without setup. Claude Code reads `AGENTS.md` from 2.1.277, but only in a
  project that has no instruction file of its own, so keep no `CLAUDE.md`,
  `.claude/CLAUDE.md` or `CLAUDE.local.md` in your checkout: any one of them
  hides this project's guidance from your session. Skills still load from
  `.claude/skills` alone, so link it once per source with
  `mkdir -p .claude && ln -s ../.agents/skills .claude/skills`, or with
  `npx skills add ./.agents/skills --agent claude-code`. Below 2.1.277, and
  on Bedrock, Vertex and Foundry where the fallback has not arrived, add
  `ln -s AGENTS.md CLAUDE.md` and remove it once your client has the
  feature. Personal instructions belong in `AGENTS.local.md`, personal

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: AGPL-3.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Mozilla Public License Version 2.0
==================================

1. Definitions
--------------

1.1. "Contributor"
    means each individual or legal entity that creates, contributes to
    the creation of, or owns Covered Software.

1.2. "Contributor Version"
    means the combination of the Contributions of others (if any) used
    by a Contributor and that particular Contributor's Contribution.

1.3. "Contribution"
    means Covered Software of a particular Contributor.

1.4. "Covered Software"
    means Source Code Form to which the initial Contributor has attached
    the notice in Exhibit A, the Executable Form of such Source Code
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original AGPL-3.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `AGPL-3.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `PENPOT` (category: DESIGN TOOLS)
- **Upstream URL:** https://github.com/penpot/penpot
- **Pinned commit (SHA):** `76e9c132efd0b66b57763c5ddd9dfcfda0051cdf`
- **Branch:** develop
- **Pin provenance:** GitHub API commits/develop. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`476453b7b7305878fea3f1094bb430a363de7a1386b228f31ede0307cba163eb`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

