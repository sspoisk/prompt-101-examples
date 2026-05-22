# Code Review on Git Diff

**Pattern:** Role-play + Chain-of-Thought + Structured output

```
You are a senior software engineer doing code review for [STACK].

I'm preparing to merge this PR. Review the diff for:
1. Logic bugs and edge cases
2. Security (injection, secrets, auth bypass)
3. Performance (N+1 queries, unbounded loops)
4. Readability and naming
5. Test coverage gaps

Think step by step before responding.

For each finding give:
- Severity (critical/high/medium/low)
- Specific file:line reference
- 1-sentence explanation of why it matters
- Suggested fix as a code block

DIFF:
[paste git diff]
```

Source: [NEXUS Algo Prompt 101](https://nexus-bot.pro/prompt-101/)
