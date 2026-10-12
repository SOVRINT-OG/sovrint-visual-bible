# Research Program: Visual Bible

**Status:** Proposed agenda for a documented visual-specification draft. The repository README states design intentions; those intentions are not yet a validated visual standard. See [RESEARCH_STATUS.yaml](./RESEARCH_STATUS.yaml).

## Questions

1. Can each public glyph, color token, graph convention, and typography rule have a stable identifier, source, version, and intended meaning?
2. Can diagrams preserve meaning when color is removed, rendered at mobile sizes, or viewed with assistive technology?
3. Which measurable accessibility checks apply to each artifact, and which require human review?
4. Can exported vector assets be reproduced from source files with traceable versions and authorship?
5. How should experimental visual variants link back to a canonical source without silently changing symbol meaning?

## Planned work

- Create a visual-token inventory with identifier, description, usage, source, version, and status (proposed, reviewed, or canonical).
- Add synthetic test plates covering text, shape, labels, and color-coded relationships.
- Check contrast and non-color cues against WCAG 2.2 criteria where applicable; record the criterion and method for each result.
- Review diagrams at narrow/mobile widths and in grayscale; distinguish manual review from automated checks.
- Preserve editable source, exports, and checksums together when a public plate is approved.

## Evidence and rights boundaries

A test result applies only to the tested artifact, content, and criterion. It does not certify the entire visual system or guarantee accessibility for every user. Do not include protected diagrams, unreleased topology, or third-party artwork without permission.

## References

- W3C, [Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/2024/REC-WCAG22-20241212/) (W3C Recommendation). Use the success criteria as testable requirements where they apply to a published digital artifact.
- W3C, [Scalable Vector Graphics (SVG) 2](https://www.w3.org/TR/2026/CR-SVG2-20261006/) (Candidate Recommendation Snapshot, 6 October 2026), a developing specification rather than a W3C Recommendation.
- [Repository README](./README.md) for the intended palette, glyph, topology, and visual-lineage scope.
- [Runtime Visual Atlas](https://github.com/SOVRINT-OG/runtime-visual-atlas) for the separate chart-generation repository.
