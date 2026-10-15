# CARBON

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-carbon_capture-lightgrey)

> Anticloud-hardened packaging of the upstream project `CARBON` in category **CARBON CAPTURE**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CARBON CAPTURE · **Upstream:** https://github.com/carbon-design-system/carbon · **Upstream pin:** `1334429ae63f9a3d052d59ec8c6b158fa5db0943` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center">
  <a href="https://www.carbondesignsystem.com">
    <img
      alt="Carbon Design System"
      src="https://user-images.githubusercontent.com/3901764/57545698-ce5f2380-7320-11e9-8682-903df232d7b0.png"
      width="720"
    />
  </a>

  <h1>Carbon Design System</h1>

  <p>
    <a href="https://www.carbondesignsystem.com">Website</a> ·
    <a href="https://carbondesignsystem.com/designing/get-started/">Design</a> ·
    <a href="https://carbondesignsystem.com/developing/get-started/">Develop</a> ·
    <a href="https://carbondesignsystem.com/contributing/get-started/overview/">Contribute</a> ·
    <a href="https://carbondesignsystem.com/migrating/guide/overview/">Migrate</a>
  </p>

  <p>
    <a href="https://github.com/carbon-design-system/carbon/actions/workflows/ci.yml">
      <img alt="CI" src="https://github.com/carbon-design-system/carbon/actions/workflows/ci.yml/badge.svg" />
    </a>
    <a href="https://bestpractices.coreinfrastructure.org/projects/7034">
      <img alt="OpenSSF Best Practices" src="https://bestpractices.coreinfrastructure.org/projects/7034/badge" />
    </a>
    <a href="./LICENSE">
      <img alt="GitHub License" src="https://img.shields.io/github/license/carbon-design-system/carbon">
    </a>
    <a href="https://discord.gg/J7JEUEkTRX">
      <img alt="Discord" src="https://img.shields.io/discord/689212587170201628?label=chat&logo=discord&logoColor=white&color=5865F2" />
    </a>
  </p>
</div>

Carbon is IBM's open-source design system for products and experiences. This
monorepo includes the React and web components libraries, Sass styles, design
tokens, icons, pictograms, and tooling used to build with Carbon.

## Packages

| Package                                   | Version                                                                                                                 | Downloads                                                                  | Description                                                   | Links                                                                          |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [`@carbon/react`][react-source]           | [![npm](https://img.shields.io/npm/v/%40carbon%2Freact)](https://www.npmjs.com/package/@carbon/react)                   | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Freact)          | React components and styles.                                  | [Docs][react-docs] · [Storybook][react-storybook] · [Source][react-source]     |
| [`@carbon/web-components`][wc-source]     | [![npm](https://img.shields.io/npm/v/%40carbon%2Fweb-components)](https://www.npmjs.com/package/@carbon/web-components) | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Fweb-components) | Standards-based web components.                               | [Docs][wc-docs] · [Storybook][wc-storybook] · [Source][wc-source]              |
| [`@carbon/colors`][colors-source]         | [![npm](https://img.shields.io/npm/v/%40carbon%2Fcolors)](https://www.npmjs.com/package/@carbon/colors)                 | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Fcolors)         | Color scales and color token utilities.                       | [Source][colors-source]                                                        |
| [`@carbon/elements`][elements-source]     | [![npm](https://img.shields.io/npm/v/%40carbon%2Felements)](https://www.npmjs.com/package/@carbon/elements)             | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Felements)       | IBM Design Language foundations, including tokens and assets. | [Source][elements-source]                                                      |
| [`@carbon/grid`][grid-source]             | [![npm](https://img.shields.io/npm/v/%40carbon%2Fgrid)](https://www.npmjs.com/package/@carbon/grid)                     | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Fgrid)           | Layouts built on Carbon's grid.                               | [Source][grid-source]                                                          |
| [`@carbon/icons`][icons-source]           | [![npm](https://img.shields.io/npm/v/%40carbon%2Ficons)](https://www.npmjs.com/package/@carbon/icons)                   | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Ficons)          | Icon assets and framework packages.                           | [React][icons-react-source] · [Vue][icons-vue-source] · [Source][icons-source] |
| [`@carbon/layout`][layout-source]         | [![npm](https://img.shields.io/npm/v/%40carbon%2Flayout)](https://www.npmjs.com/package/@carbon/layout)                 | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Flayout)         | Layout units and spacing scale tokens.                        | [Source][layout-source]                                                        |
| [`@carbon/motion`][motion-source]         | [![npm](https://img.shields.io/npm/v/%40carbon%2Fmotion)](https://www.npmjs.com/package/@carbon/motion)                 | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Fmotion)         | Productive and expressive motion curves.                      | [Source][motion-source]                                                        |
| [`@carbon/pictograms`][pictograms-source] | [![npm](https://img.shields.io/npm/v/%40carbon%2Fpictograms)](https://www.npmjs.com/package/@carbon/pictograms)         | ![NPM Downloads](https://img.shields.io/npm/dw/%40carbon%2Fpictograms)     | Pictogram assets.                                             | [React][pictograms-react-source] · [Source][pictograms-source]                 |
| [`@carbo

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, yarn.lock; scanned in UPSTREAM_CLONE)
- Top-level source layout: `actions/`, `config/`, `e2e/`, `examples/`, `packages/`, `tasks/`
- Snapshot size: **10214 files**, **473323 lines of code** (measured; see Benchmarks)
- Primary languages: `.svg` (4554), `.js` (1413), `.scss` (1321), `.ts` (1179), `.tsx` (496), `.mdx` (319)
- Upstream commit pinned for this packaging: `1334429ae63f9a3d052d59ec8c6b158fa5db0943`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# from this project directory
npm install        # or: npm ci
npm run build      # if a build script is declared
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
npm start          # declared start script, when present
npm run dev        # declared dev script, when present
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `CARBON` source tree vendored in `UPSTREAM_CLONE/` (Node.js / npm ecosystem). Public entry points:

- Source modules: `actions/`, `config/`, `e2e/`, `examples/`, `packages/`, `tasks/`
- The snapshot declares 1014 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, yarn.lock |
| Files in snapshot | 10214 |
| Lines of code | 473323 |
| Dependency references | 1014 |
| Dependencies by ecosystem | npm: 1014 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | unrun | ^0.3.1 | package.json |
| npm | @babel/core | ^8.0.0 | package.json |
| npm | @babel/plugin-proposal-export-default-from | ^8.0.0 | package.json |
| npm | @babel/plugin-transform-class-properties | ^8.0.0 | package.json |
| npm | @babel/plugin-transform-export-namespace-from | ^8.0.0 | package.json |
| npm | @babel/plugin-transform-runtime | ^8.0.0 | package.json |
| npm | @babel/preset-env | ^8.0.0 | package.json |
| npm | @babel/preset-react | ^8.0.0 | package.json |
| npm | @babel/runtime | ^8.0.0 | package.json |
| npm | @carbon/cli | workspace:packages/cli | package.json |
| npm | @carbon/ibm-products | latest | package.json |
| npm | @commitlint/cli | ^21.0.0 | package.json |
| npm | @commitlint/config-conventional | ^21.0.0 | package.json |
| npm | @eslint/compat | ^2.0.1 | package.json |
| npm | @eslint/js | ^9.24.0 | package.json |
| ... | (485 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `config`
- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `.github/CONTRIBUTING.md`:*

<!--
  Purpose: This is the contributor-facing entry point for finding work and
  understanding how to participate. Keep issue search links aligned with the
  project's current issue fields and labels.
-->

# Contributing

## Our contribution model

Carbon Design System is an **open source** project at IBM. We pride ourselves on
open and inclusive design and development. If you're curious about our
contribution process, you're in the right place. Thank you for your interest!

This project is made possible not just by the core Carbon team, but by community
members who’ve generously contributed their time to give back.

## Code of conduct

[Code of conduct](./CODE_OF_CONDUCT.md)

## Prerequisites

Before contributing, ensure you have these tools installed:

- [Node.js](https://nodejs.org/en/download/) – Use the version specified in
  [.nvmrc](../.nvmrc).
  - On macOS, we recommend using [nvm](https://github.com/nvm-sh/nvm) to manage
    Node versions.
- [Git](https://github.com/git-guides/install-git)
- [Yarn](https://yarnpkg.com/getting-started)
- [WSL](../docs/guides/setup/windows.md) (Windows only)

If you're on Windows, follow
[these additional steps](../docs/guides/setup/windows.md).

You'll also need a code editor. [VS Code](https://code.visualstudio.com/) and
[Sublime Text](https://www.sublimetext.com/) are popular options.

Once these tools are installed, you're ready to contribute!

## Start contributing

### Setting up your environment

#### Fork the project

[Forking a project](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-project#forking-a-project)

#### source your fork

[Cloning a project](https://docs.github.com/en/projects/creating-and-managing-projects/cloning-a-project#cloning-a-project)

#### Add upstream remote

After cloning your fork, set up the upstream remote:

```sh
# Add the upstream remote to your project
git remote add upstream git@github.com:carbon-design-system/carbon.git

# Verify the remote was added
git remote -v
```

Expected output:

```sh
origin  git@github.com:<your_github_username>/carbon.git (fetch)
origin  git@github.com:<your_github_username>/carbon.git (push)
upstream  git@github.com:carbon-design-system/carbon.git (fetch)
upstream  git@github.com:carbon-design-system/carbon.git (push)
```

Great job on getting to this point! Now it's time to code :computer:

### Making a contribution

#### Find or create an issue

Check the [issues list](htt

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `CARBON` (category: CARBON CAPTURE)
- **Upstream URL:** https://github.com/carbon-design-system/carbon
- **Pinned commit (SHA):** `1334429ae63f9a3d052d59ec8c6b158fa5db0943`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`31612de989f51058d09fece534576bb13441cd8d800b0c1232f44e27767d5f83`.

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


> Note: a same-named project in another category is the canonical published copy; this directory is retained as a local reference and is not published separately.
