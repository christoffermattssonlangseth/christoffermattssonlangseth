<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1400&color=58A6FF&center=true&vCenter=true&width=620&lines=Postdoctoral+researcher+%C2%B7+Karolinska+Institutet;Spatial+omics+%C2%B7+Neuroinflammation+%C2%B7+Single-cell;Research+software+in+Python%2C+Swift+and+Rust" alt="Typing SVG" />

[![spatialist](https://img.shields.io/badge/spatialist-co--founder-0969da?style=flat-square)](https://www.spatial.ist)
[![CV](https://img.shields.io/badge/Curriculum_vitae-view-57606a?style=flat-square)](https://christoffermattssonlangseth.github.io/cv.html)
[![Thesis](https://img.shields.io/badge/PhD_thesis-2025-57606a?style=flat-square)](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1929647&dswid=-2336)

<img src="https://skillicons.dev/icons?i=py,r,swift,rust,apple&theme=dark" alt="Languages and platforms" />

</div>

Computational biologist in the Castelo-Branco group at Karolinska Institutet. My research uses spatial and single-cell transcriptomics to study neuroinflammation, and I develop open-source software for analyzing and sharing spatial omics data. Co-founder of [spatialist](https://www.spatial.ist).

<div align="center"><code>──────────── research ────────────</code></div>

### KaroSpace

Open-source toolkit for turning spatial omics datasets into interactive, shareable web viewers.

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'Inter, Helvetica, Arial, sans-serif','fontSize':'14px','lineColor':'#8b949e','primaryColor':'#ffffff','primaryBorderColor':'#d0d7de','primaryTextColor':'#24292f'}}}%%
flowchart LR
    data["Spatial omics data"]
    subgraph create ["Create"]
        direction TB
        builder["KaroSpaceBuilder<br/><small>desktop app</small>"]
        agent["KaroSpaceAgent<br/><small>AI-assisted</small>"]
    end
    core["KaroSpace<br/><small>viewer generator</small>"]
    viewer["Interactive web viewer"]

    data --> builder & agent
    builder & agent --> core
    core --> viewer

    classDef node fill:#ffffff,stroke:#d0d7de,color:#24292f
    classDef main fill:#0969da,stroke:#0969da,color:#ffffff
    class data,builder,agent,viewer node
    class core main
    style create fill:#f6f8fa,stroke:#d0d7de,color:#57606a
```

| Repository | Description |
|---|---|
| [**KaroSpace**](https://github.com/christoffermattssonlangseth/KaroSpace) | Core library for generating viewers |
| [**KaroSpaceBuilder**](https://github.com/christoffermattssonlangseth/KaroSpaceBuilder) | Graphical application for building viewers without code |
| [**KaroSpaceAgent**](https://github.com/christoffermattssonlangseth/KaroSpaceAgent) | AI agent for configuring viewers from a dataset description |

### Unpublished work

| Project | Status |
|---|---|
| Spatiotemporal modeling of tissue in disease | ![In preparation](https://img.shields.io/badge/in_preparation-57606a?style=flat-square) |

<sub>Code will be released upon publication. Collaboration inquiries are welcome.</sub>

<div align="center"><code>──────────── applications ────────────</code></div>

### Applications

| Application | Description | Platform |
|---|---|---|
| [**Lunta**](https://github.com/christoffermattssonlangseth/lunta) | Reference manager with reading views, annotations, full-text search, citation export and a daily literature feed | macOS, iOS |
| [**Grepp**](https://github.com/christoffermattssonlangseth/grepp) | Strength-training log stored as plain Markdown, with an integrated Claude-based coach | iOS |
| [**BarVelo**](https://github.com/christoffermattssonlangseth/BarVelo) | Bar velocity measurement for velocity-based training, integrated with Grepp | iOS · in development |
| [**KidDos(e)**](https://github.com/christoffermattssonlangseth/KidDose) | Dose tracking for pediatric ibuprofen and paracetamol | iOS |
