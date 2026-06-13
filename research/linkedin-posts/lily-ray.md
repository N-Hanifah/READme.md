# Lily Ray — LinkedIn Posts

**Profile:** https://www.linkedin.com/in/lily-ray-44755615/
**Topic Focus:** AI Search, SEO Keywords, Google Sheets AI Integration
**Collected:** June 2026

---

## Post 1
**Date:** June 10, 2026
**URL:** https://www.linkedin.com/posts/lily-ray-44755615_heres-a-little-hack-ive-been-using-to-quickly-activity-7470166067043147776-6kTD

Here's a little hack I've been using to quickly convert SEO keywords into relevant AI prompts at scale directly in Google Sheets.

Use the =AI or =Gemini function - plus this prompt I'll share below - to convert your SEO keywords into associated ways that users might type (or ask out loud) that same question into an AI assistant.

It's not perfect (is any prompt selection, though?), but what I like about it is that it allows you to take keywords with real search volume (import from Ahrefs, Semrush, Similarweb, etc.) and quickly convert them into AI prompts at scale.

Obviously - you can use an LLM to modify the prompt as needed to get a better result.

Prompt:

=AI("You are converting a terse SEO search keyword into the natural-language query a real person would actually type or speak to an AI assistant like ChatGPT, Gemini, or a voice assistant. Rewrite the keyword as a single conversational question or request that preserves the exact search intent and intent type (informational, commercial, transactional, or local). Phrase it the way someone would genuinely ask out loud in a full sentence — not in keyword shorthand. Keep any brand, product, or location named in the keyword, but do NOT invent specifics, constraints, or details that aren't already implied. Do not answer the query. Return only the rewritten prompt as plain text — no quotation marks, no preamble, no explanation, no trailing punctuation beyond a question mark. Keyword:", A2)
