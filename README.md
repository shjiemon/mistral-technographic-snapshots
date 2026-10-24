# Mistral AI — Technographic Snapshots

A series of technographic network diagrams examining the evolution of Mistral AI's infrastructure ecosystem (2023–2026).

This repository supports the research essay *Mistral AI: Rethinking Technological Autonomy through Infrastructural Dependence*, developed for the MA Cultural Data & AI programme at the University of Amsterdam (2026).

## Research focus

The project investigates the relationship between:

- **Downstream technological autonomy:** The choices and capabilities Mistral offers its users, including model access, customization, and deployment options.
- **Upstream infrastructural dependence:** Mistral's reliance on external computing resources, hardware, cloud infrastructure, and distribution channels.

## Historical snapshots

| Snapshot | Date | Focus |
|---|---|---|
| T₀ | September 2023 | Mistral 7B and open-weight distribution |
| T₁ | December 2023 | Mixtral 8x7B and La Plateforme beta |
| T₂ | July 2024 | Integration with major cloud providers |
| T₃ | October 2025 | Enterprise and private/hybrid deployment |
| T₄ | October 2026 | Mistral-operated compute infrastructure |

Snapshots represent documented configurations rather than exhaustive infrastructure inventories. The diagrams distinguish established relationships from technical capabilities and announced arrangements.

## Evidence register

The diagrams are based on a [technographic evidence register](https://docs.google.com/spreadsheets/d/1dL5M2QMF2TcRpt84B57iQuj-Xqew7yIV_ZRQTRB3nUE/edit) (Google Sheets).

The register documents the principal infrastructural relationships and deployment capabilities represented across the five snapshots (T₀–T₄), including their evidentiary status, supporting sources, and relevant qualifications.

The register served as input for the ChatGPT-assisted generation of the Graphviz code, which was subsequently reviewed and refined by the author. The diagrams were further refined in Figma.

The register serves as a concise index of empirical evidence rather than an exhaustive source archive.

## Repository structure

```text
src/       Graphviz DOT source files
svg/       Generated SVG diagrams
exports/   Finalized diagrams (Figma exports)
```

## Tools

Graphviz DOT source code was generated with assistance from ChatGPT, using the technographic evidence register as input. The diagrams were rendered using [Graphviz](https://graphviz.org/) and visually refined in Figma.

To generate an SVG (replace the example filenames with your own):

```bash
dot -Tsvg graphviz-input-file.dot -o output-file.svg
```

## Related project

`mistral-discourse-analysis` — a companion project examining changes in Mistral AI's public communications.