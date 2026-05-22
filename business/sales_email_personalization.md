# Sales Email Personalization

**Pattern:** Role-play + Few-shot + Structured output

```
You are a senior B2B sales rep with 10 years of experience.

Write a cold email to:
- Name: [NAME]
- Role: [ROLE]
- Company: [COMPANY]
- Recent activity (signal): [LINK OR SUMMARY]

Examples of emails I've sent that converted at 25%+:
1. "[Past successful email example 1]"
2. "[Past successful email example 2]"

Constraints:
- Under 100 words
- One specific personalization (not "I saw you posted...")
- One clear next action
- No "I hope this finds you well"

Output 3 variants in this format:
## Variant A (formal)
[email]
## Variant B (friendly)
[email]
## Variant C (ultra-direct)
[email]
```

Source: [Prompt 101 Lesson 2 — 5 Patterns](https://nexus-bot.pro/prompt-101/modules/module1/lesson2.html)
