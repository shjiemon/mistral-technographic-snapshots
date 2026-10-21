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

## Repository structure

```text
src/       Graphviz DOT source files
svg/       Generated SVG diagrams
exports/   Finalized diagrams (Figma exports)
```

## Tools

Diagrams are created using [Graphviz](https://graphviz.org/) and visually refined in Figma.

To generate an SVG:

```bash
dot -Tsvg src/T1-december-2023.dot -o svg/T1-december-2023.svg
```

## Related project

`mistral-discourse-analysis` — a companion project examining changes in Mistral AI's public communications.