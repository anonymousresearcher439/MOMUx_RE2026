# Requirements Derivation Process

This page describes the process used to derive candidate requirements from Operationally Significant Events (SIGACTs). The goal is transparency: to show how observations were interpreted, how candidate requirements were generated, and how they were refined through expert reasoning and interactive analysis.

## Process Summary

Requirement derivation followed an iterative socio-technical workflow. For each SIGACT, the research team developed an initial interpretation of the underlying problem, used GPT-5.2 to generate and challenge candidate framings, and then iteratively refined wording and scope until the requirement was sufficiently clear, distinct, and traceable to the observation.

## Step 1 — Interpret the SIGACT (Research Team)

For each SIGACT, the research team first reasoned about what the event revealed, drawing on operational context and study knowledge. Typical questions included:

- What happened and what evidence supports that interpretation?
- Is the breakdown perceptual, cognitive, coordination-related, or representational?
- Is this best addressed through system capabilities or procedures/training?
- What risks or downstream consequences did the breakdown introduce?
- Is the issue specific to the study context or likely to generalize?

This step anchored the process in expert judgment rather than automated synthesis.

## Step 2 — Generate Candidate Framings (Initial Prompts to GPT-5.2)

The team then used structured prompts to explore candidate interpretations and requirement directions. Prompts emphasized framing and scoping before drafting, for example:

- Does this overlap with existing requirements?
- Which category does it belong in?
- Is it in scope or procedural?
- What distinguishes it from similar SIGACTs?

GPT-5.2 was used to propose alternative framings, surface assumptions, and suggest candidate requirement structures.

## Step 3 — Iterative Refinement (Interactive Dialogue)

Most requirements were shaped through back-and-forth refinement. Iterations focused on improving clarity and ensuring requirements were genuinely derived (not restatements). Common refinement moves included:

- Tightening language to reduce ambiguity and repetition
- Separating “as observed” SIGACT wording from broader interpretation in the root problem
- Checking distinctness to avoid duplication across nearby SIGACTs
- Testing whether wording was overly prescriptive (prematurely committing to design)
- Revising derived requirements so they meaningfully refined the main requirement

Typical discussion questions included:

- Are we describing the observation or interpreting it?
- What is the minimal system capability needed?
- Is the derived requirement truly derived or just rephrased?
- Would a reviewer view this as redundant or out of scope?

## Step 4 — Fit Criteria (Evaluation-Oriented)

Fit criteria were discussed with emphasis on measurability and operational relevance, avoiding vague “understanding” language. In several cases, exact thresholds were intentionally deferred. Following a Twin Peaks mindset, detailed performance targets were treated as design-time decisions that depend on architectural tradeoffs and feasibility.

## Step 5 — Scope Decisions and Procedural Outcomes

For each SIGACT, the team explicitly decided whether the issue was addressed via:

- System requirement(s)
- Procedural guidance (out of scope for the current system)
- A hybrid framing
- Deferred consideration

This led to the creation of a Procedural category to preserve traceability for important observations that were not translated into system requirements under the current scope.

## Step 6 — Consolidation and Consistency Checks

Finally, requirements were reviewed across the artifact for:

- Conceptual overlap and redundancy
- Category coherence
- Traceability and narrative consistency
- Opportunities to merge closely related SIGACTs that reflected a common underlying issue

## Notes on Iteration

The number of iterations varied by SIGACT; many requirements required multiple rounds of discussion and revision before stabilizing. Iterations typically focused on scope, distinctness, and wording precision rather than generating large volumes of text.

## Limitations

The requirements represent interpretations based on observed events and expert judgment. Alternative interpretations are possible, and the artifact may evolve as additional operational experience is gained or system scope changes.

**Note:** This process description was developed with assistance from GPT-5.2 to summarize the interactive workflow. The document was reviewed and approved by the research team.
