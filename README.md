# ⚠️ DEPRECATED

This rule has been replaced by [Hodor](https://github.com/CursorCult/Hodor).

Hodor provides a unified "golden thread" traceability rule that subsumes SpecsFirst.

---

# Part of the [CursorCult](https://github.com/CursorCult)

# SpecsFirst

Write specs first; keep spec/design/code in sync.

**Install**

```sh
pipx install cursorcult
cursorcult link SpecsFirst
```

Rule file format reference: https://cursor.com/docs/context/rules#rulemd-file-format

**When to use**

- You want requirements to drive design and implementation, not trail them.
- You keep finding “mystery behavior” with no written rationale.
- You want a clear map from intention → structure → code.

**What it enforces**

- Every feature update starts by updating the specification.
- Design changes follow specs, and code follows design.
- Spec, design, and implementation stay semantically consistent.

**Credits**

- Developed by Will Wieselquist. Anyone can use it.
