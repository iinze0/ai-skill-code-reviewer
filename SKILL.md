---
name: code-reviewer
description: "Perform thorough code reviews focusing on bugs, security issues, performance, style, and maintainability. Use when reviewing pull requests, functions, or code snippets in any language."
type: workflow
lifecycle: active
---

# Code Reviewer

Deliver structured, actionable code reviews.

## Core Workflow

1. Identify language, context, and intent of the code.
2. Check for:
   - Correctness and edge cases
   - Security vulnerabilities (injection, auth, data exposure)
   - Performance issues
   - Readability, naming, and structure
   - Error handling and logging
3. Provide feedback in priority order (critical → minor).
4. Suggest concrete improvements or refactors with examples when helpful.
5. Note positive aspects as well.

## Output Format

- **Critical**: Must fix
- **Suggestions**: Should consider
- **Nits**: Style/minor

Be specific and constructive. Reference line numbers or sections when possible.
