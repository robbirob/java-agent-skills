---
name: java-clean-code
description: "Use when reviewing created or modified Java code for clean code issues such as long methods, naming, duplication, and complexity."
---

# Java Clean Code Review

WHEN:
- Java code is created or modified

CHECK:
- Method length <= 30 lines
- Class length <= 300 lines
- No boolean parameters
- No magic numbers
- Early return preferred
- Nesting <= 3 levels
- Meaningful names

FAIL IF:
- God classes
- Long methods
- Duplicate logic
- Unclear naming

OUTPUT:
- HIGH
- MEDIUM
- LOW
