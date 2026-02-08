---
name: sql-formatter-prettifier-my-queries-are
description: sql formatter / prettifier, my queries are always a mess and i want something that formats them consistentl...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: sql formatter / prettifier, my queries are always a mess and i want something that formats them consistently. bonus if it can also validate basic syntax

# Context
should handle postgres-specific stuff like CTEs and window functions not just basic sql

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: script-heavy-builder description: A builder that generates Agent Skills composed of multiple composable shell scripts following Unix philosophy. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.