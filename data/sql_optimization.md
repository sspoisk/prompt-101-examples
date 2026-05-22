# SQL Query Optimization

**Pattern:** Role-play + Chain-of-Thought

```
You are a database performance engineer specializing in [POSTGRES/MYSQL/etc.].

Optimize this query. Show me:
1. The optimized version
2. What indexes to add (if any) — explain why
3. Whether materialized views could help
4. Any anti-patterns I'm using

Context:
- Database: [TYPE + VERSION]
- Table sizes: [APPROX ROW COUNTS]
- Current runtime: [IF KNOWN]
- How often it runs: [PER MIN / HOUR / DAY]

ORIGINAL QUERY:
[paste]

EXPLAIN ANALYZE output (if you have it):
[paste]

Think step by step before optimizing.
```

Source: [Prompt 101 Course](https://nexus-bot.pro/prompt-101/)
