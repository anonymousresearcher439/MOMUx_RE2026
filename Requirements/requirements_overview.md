# Requirements Overview

This repository documents requirements derived from analysis of Operationally Significant Events (SIGACTs) observed during multi-operator, multi-UAS supervisory missions. The goal of this artifact is to provide transparency into how observed operational challenges are interpreted and translated into actionable requirements that can inform system design, evaluation, and future research.

The requirements captured here are not intended to represent a complete or finalized specification for each SIGACT. Instead, they serve as examples of how a SIGACT can be translated into requirements, reflecting an evolving understanding of supervisory needs as new observations are analyzed and interpretations are refined.

Where appropriate, requirements are expressed using principles from the Easy Approach to Requirements Syntax (EARS) [LINK COMING] to promote clarity and consistency in specifying system capabilities. Non-functional requirements are illustrated using Robertson and Robertson’s concept of Fit Criteria [LINK COMING] to provide measurable examples of how requirements could be evaluated in practice.

For each SIGACT, we document:

- The observed issue and its interpreted root problem
- A main requirement capturing the primary capability needed
- One derived requirement that refines or supports the main requirement
- One example non-functional requirement (NFR) with a fit criterion that illustrates how the requirement could be evaluated

This structure is intended to maintain traceability between observed operational breakdowns and the requirements that address them, while keeping the artifacts lightweight and extensible.

---

## Requirement Groupings

The requirements are organized into thematic groupings based on operational perspective or type of supervisory challenge. Each grouping contains a table of SIGACT-derived requirements relevant to that area.

| Grouping | Description | Link |
|----------|-------------|------|
| VO/RPIC Awareness Requirements | Requirements related to visual situational awareness, perception, and interpretation from the Visual Observer and Remote Pilot in Command perspectives. | [VO/RPIC Requirements](https://github.com/anonymousresearcher439/MOMUx_RE2026/blob/main/Requirements/VO-RPIC.md) |
| Team Coordination | Requirements related to shared situational awareness and access to mission information across operational roles. | [Teamwork Requirements](https://github.com/anonymousresearcher439/MOMUx_RE2026/new/main/Requirements)|
| Geospatial Understanding and Representation Alignment | Requirements focused on supporting operators in aligning maps, planned trajectories, and real-world observations to reason about aircraft position and movement. | [Spatial Perspectives Requirements](https://github.com/anonymousresearcher439/MOMUx_RE2026/blob/main/Requirements/spatial-perspectives.md) |
| Intent Awareness and Behavior Understanding | Requirements focused on helping operators understand and explain autonomous system behavior during operations. | [Intent Awareness Requirements](https://github.com/anonymousresearcher439/MOMUx_RE2026/blob/main/Requirements/intent-awareness.md) |

---

## Notes

- Placeholders such as *T* (time) and *P%* (performance threshold) indicate values that may be calibrated through experimentation or operational tuning.
- Requirements are intentionally phrased to avoid prescribing specific interface designs unless necessary.
- This artifact is part of a replication package and is intended to support reuse, review, and future refinement.
