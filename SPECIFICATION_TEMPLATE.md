Specification Template

Purpose

A specification translates an idea into an executable plan.

The objective is not merely to describe what should be built, but to communicate enough context that another human or AI can make correct implementation decisions without unnecessary clarification.

A good specification reduces ambiguity while preserving appropriate implementation freedom.

⸻

1. Problem Statement

What problem are we solving?

Describe the current situation, why it matters, and why action is needed.

⸻

2. Objective

What should exist when this work is complete?

Describe the desired outcome rather than the implementation.

⸻

3. Background

What context is necessary to understand this task?

Include relevant history, previous decisions, existing architecture, related projects, or business rationale.

Assume the implementer has never participated in previous discussions.

⸻

4. Scope

Clearly define boundaries.

Included

What is part of this work?

Excluded

What is intentionally not part of this work?

⸻

5. Users / Stakeholders

Who benefits from this work?

Who will use it?

Who might be affected by it?

⸻

6. Requirements

Describe functional requirements.

Prefer clear, testable statements.

Example:

* The system shall…
* The application should…
* The user must be able to…

⸻

7. Constraints

List constraints that cannot be violated.

Examples:

* Technology stack
* Performance limits
* Compatibility requirements
* Budget
* Timeline
* Regulatory requirements

⸻

8. Design Principles

What principles should guide implementation?

Examples:

* Reveal complexity progressively.
* Derive information instead of asking users.
* Simplicity over cleverness.
* Preserve user trust.

⸻

9. Assumptions

Document assumptions explicitly.

Unknown assumptions become future bugs.

⸻

10. Risks

What could go wrong?

What trade-offs exist?

What uncertainties remain?

⸻

11. Success Criteria

How will success be measured?

Examples:

* Feature behaves as described.
* Existing functionality remains unaffected.
* Performance remains within acceptable limits.
* User can complete the workflow without additional guidance.

⸻

12. Acceptance Tests

Describe observable conditions that determine whether the specification has been successfully implemented.

Examples:

* Given…
* When…
* Then…

Acceptance tests should focus on externally visible behavior.

⸻

13. Deliverables

List expected outputs.

Examples:

* Source code
* Documentation
* Tests
* Architecture diagrams
* Updated README
* Screenshots
* Migration notes

⸻

14. Open Questions

Capture unresolved decisions.

Separate unknowns from assumptions.

⸻

15. Future Extensions

Record ideas deliberately deferred.

This preserves future opportunities without expanding current scope.

⸻

Definition of a Good Specification

A good specification enables another competent person—or an AI agent—to:

* understand the problem,
* understand why it matters,
* know what success looks like,
* understand important constraints,
* make reasonable implementation decisions,
* recognize when the work is complete,
* avoid solving the wrong problem.

The best specifications maximize clarity while minimizing unnecessary prescription.

They define what and why precisely, while leaving appropriate freedom in how the solution is implemented.