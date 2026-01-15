# PromptSpec

**From vague ideas to powerful AI prompts — without guesswork.**

PromptSpec is a lightweight, browser-based tool that helps you turn unclear ideas into precise, production-ready AI prompts *before* you ever talk to an LLM.

Instead of iterating endlessly with “try again” prompts, PromptSpec forces clarity upfront — so AI tools finally do what you expect them to do.

👉 **Live version:**  
https://aliemre1188.github.io/PromptSpec/

---

## What problem does this solve?

Most AI failures are not model failures.  
They are **specification failures**.

Unclear intent leads to:
- vague prompts  
- inconsistent outputs  
- fragile results  
- wasted time  

PromptSpec solves this by structuring your thinking **before** AI gets involved.

---

## What PromptSpec does

PromptSpec guides you through a structured specification covering:

- Your real objective
- Target environment (ChatGPT, Cursor, Windsurf, no-code tools, automation, etc.)
- Skill level and assumed knowledge
- Hard constraints and non-negotiables
- Desired output structure and verbosity
- Risk tolerance and execution style

Based on this, PromptSpec generates a **meta-prompt**.

You paste this meta-prompt into any LLM, and the LLM:
1. Tells you exactly **where to paste the resulting master prompt**
2. Outputs **one clean, self-contained master prompt**
3. Follows explicit rules, structure, and constraints

---

## How to use PromptSpec (recommended)

1. Open the live page  
   👉 https://aliemre1188.github.io/PromptSpec/
2. Fill out the form (mandatory fields are validated)
3. Click **“Copy prompt and paste to any LLM”**
4. Paste the copied text into:
   - ChatGPT
   - Claude
   - Gemini
   - Cursor / Windsurf
   - No-code or automation tools
5. Follow the instructions produced by the LLM

No signup. No setup. No friction.

---

## How to run it locally

PromptSpec is a single static HTML file.

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. Use it exactly like the hosted version

There are:
- no dependencies
- no build steps
- no tooling requirements

---

## Privacy & data handling

PromptSpec is **privacy-first and GDPR-safe by design**.

- No backend
- No analytics
- No cookies
- No API calls
- No data transmission

All processing happens **locally in your browser**.

For convenience, form state may be stored in `localStorage` so your inputs persist across reloads.  
You can delete this at any time using the **Reset** button or by clearing browser storage.

---

## Design principles

- **Specification before generation**  
  Clear thinking beats prompt iteration.

- **Deterministic, not “AI magic”**  
  PromptSpec itself uses no AI.

- **Client-side only**  
  If a server is not needed, it should not exist.

- **Model-agnostic**  
  Works with any current or future LLM.

---

## Who this is for

- Developers using AI coding assistants
- No-code and vibe-coding builders
- Consultants and strategists
- Anyone tired of rewriting the same prompt ten times

---

## Project status

PromptSpec is a **complete, working prototype** and an intentional proof-of-work project.

Possible future extensions (not implemented here):
- Prompt templates
- Team prompt standards
- Prompt validation and linting
- Versioned specifications

---

## Author

Built by **Emre Aksoy**  
www.emreaksoy.de

---

## License

MIT — free to use, adapt, and extend.
