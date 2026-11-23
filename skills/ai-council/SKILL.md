---
name: ai-council
description: Use when a plan or creative decision would benefit from several AI models working independently — running one brief through multiple assistants (e.g. ChatGPT, Grok, Gemini, an on-device model) and merging the results.
---

# AI Council

Get independent answers from several AI models, then merge them into one stronger plan. By The Ask Why Company.

## Steps
1. **Write one brief** that every model gets verbatim: facts (no secrets), constraints (budget, rules), and an exact deliverable format (headings/tables). Same brief = comparable answers.
2. **Run each model alone** — none sees another's answer. Typical members: a ChatGPT/Codex CLI, Grok CLI, Gemini (e.g. via Google's agent CLI), a small on-device model for short focused tasks (hooks, captions — small context), and Claude as synthesiser. Save each answer to its own file.
3. **Round 2 (optional):** add new information or the owner's feedback as an addendum and re-run, saving as `-r2`.
4. **Merge:** build one document. Where members agree, keep it. Where they disagree, pick the option backed by a primary source or the user's own data, and say which you chose. Flag every number that came from a single unsourced answer as a hypothesis.
5. **Verify** anything time-sensitive (pricing, free tiers, platform rules) with a quick web search before it goes in.
6. **Deliver** the merged plan and keep the member files for reference.

## Tips
- On-device models have small context windows: split long tasks into batches.
- CLI agents may kill background tasks; tell them to work in the foreground.
- Never paste credentials into a brief; never let a member take outward actions (posting, emailing) — the council only advises.
