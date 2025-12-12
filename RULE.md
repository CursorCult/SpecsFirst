---
description: "Write specs first; keep spec/design/code in sync"
alwaysApply: true
---

# SpecsFirst Rule

Specifications (requirements) and design must precede, and remain synchronized with, implementation.

Definitions:
- Specification: a written statement of required behavior, constraints, or acceptance criteria.
- Design: the intended structure or approach that satisfies the specification.
- Implementation: source code and tests realizing the design.

Requirements:
1. The codebase must have known, discoverable locations for specifications and for design artifacts. Use existing conventions; if none exist, create them (for example, `SPEC.md` and `DESIGN.md` at the repository root).
2. For any new feature or behavior change, first update the specification to state the requirement precisely.
3. Next, update the design to explain how the implementation will satisfy the updated specification.
4. Only then modify or add implementation.
5. The semantic content of specification, design, and implementation must remain consistent. Conflicts indicate incomplete work.
6. If implementation exists without corresponding specification and design, treat this as a defect: stop, add or update the missing specification/design, then reconcile the code.
