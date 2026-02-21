## Intent Awareness and Behavior Understanding Requirements

This section captures requirements derived from SIGACTs that reveal challenges in understanding the intentions and expected behaviors of autonomous systems during operations. These observations highlight situations where operators could observe what sUAS were doing but lacked sufficient context to understand why those actions were occurring, leading to confusion, misinterpretation of valid behaviors as anomalies, and reduced confidence in supervisory decision-making.

The requirements focus on supporting operators in forming accurate mental models of system behavior by making planned behaviors and their context visible, particularly when autonomous decisions or transitions occur. The goal is to enable operators to interpret system actions correctly, anticipate behavior, and maintain trust in the autonomy while reducing uncertainty during supervision.

Each entry documents the observed issue, an interpretation of the underlying intent-awareness challenge, a main requirement, a derived requirement that refines or supports the capability, and an example non-functional requirement with a measurable outcome.

| ID | SIGACT | Root Problem | Main Requirement | Derived | NFR Example |
|----|--------|-------------|------------------|---------|-------------|
| S11 | TO suffers from loss of sUAS intentionality projection, preventing understanding of movements and leading to confusion about whether sUAS are on course | The Tactical Operator had visibility into broad operational boundaries but lacked insight into the planned behaviors of individual sUAS. Without information about expected system actions, the operator could not distinguish between valid autonomous maneuvers and anomalies, leading to correct behavior being interpreted as erratic or surprising. | The Tactical Operator interfaces shall provide information about the planned behaviors of sUAS during operations. | The system shall provide information that supports operator understanding of why each sUAS is behaving as observed. | Operators shall be able to explain the current behavior of a specified sUAS in at least 98% of trials. |
