# Requirements Overview

This repository documents requirements derived from analysis of Operationally Significant Events (SIGACTs) observed during multi-operator, multi-UAS supervisory missions. The goal of this artifact is to provide transparency into how observed operational challenges are interpreted and translated into actionable requirements that can inform system design, evaluation, and future research.

The requirements captured here are not intended to represent a complete or finalized specification. Instead, they reflect an evolving understanding of supervisory needs as new observations are analyzed and interpretations are refined. As additional SIGACTs are studied, new requirements may be added and existing ones may be revised.

For each SIGACT, we document:

- The observed issue and its interpreted root problem
- A main requirement capturing the primary capability needed
- One derived requirement that refines or supports the main requirement
- One example non-functional requirement (NFR) with a fit criterion that illustrates how the requirement could be evaluated

This structure is intended to maintain traceability between observed operational breakdowns and the requirements that address them, while keeping the artifact lightweight and extensible.

---

## Requirement Groupings

The requirements are organized into thematic groupings based on operational perspective or type of supervisory challenge. Each grouping contains a table of SIGACT-derived requirements relevant to that area.

| Grouping | Description | Link |
|----------|-------------|------|
| VO/RPIC Awareness Requirements | Requirements related to visual situational awareness, perception, and interpretation from the Visual Observer and Remote Pilot in Command perspectives. | [VO/RPIC Requirements](https://github.com/anonymousresearcher439/MOMUx_RE2026/blob/main/Requirements/VO-RPIC.md) |
| (More coming) | Additional groupings will be added as analysis continues. | — |

---

## Notes

- Placeholders such as *T* (time) and *P%* (performance threshold) indicate values that may be calibrated through experimentation or operational tuning.
- Requirements are intentionally phrased to avoid prescribing specific interface designs unless necessary.
- This artifact is part of a replication package and is intended to support reuse, review, and future refinement.
