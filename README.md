# Prompt Builder

**Build structured prompts for trustworthy generative AI workflows.**  
Create reusable, transparent and privacy-preserving prompts — block by block.

Live: [caladai.com/herramientas/prompting.html](https://caladai.com/herramientas/prompting.html)

---

## What it is

Prompt Builder is an open source, single-file tool to compose structured prompts for large language models. Instead of writing prompts from scratch every time, you activate the blocks you need — task, role, chain-of-thought, constraints, format, input — and copy the result.

No framework. No dependencies. No backend. One HTML file.

## Features

- **Block-by-block composition** — activate only what you need
- **10 ready-to-use examples** — executive summary, meeting minutes, difficult email, LinkedIn post, text reviewer, and more
- **Bilingual** — English and Spanish, switchable at any time
- **Chat and API modes** — output formatted for direct chat use or for the API (system + user)
- **Templates** — save and reload your own prompt structures locally
- **Chain-of-thought** — step-by-step, rationale, or none
- **Protection** — optional anti-prompt-injection hardening
- **Dark mode**
- **Mobile responsive**
- **Privacy first** — everything runs in your browser; no data leaves your machine

## How to use

### Option A — Use it online
Go to [caladai.com/herramientas/prompting.html](https://caladai.com/herramientas/prompting.html). No login, no account.

### Option B — Run it locally
```bash
git clone https://github.com/gotoCaladai/prompt-builder.git
cd prompt-builder
# open prompt_builder.html in your browser
# or serve it locally:
npx serve .
```
Then open `http://localhost:3000/prompt_builder.html`.

## Contributing

Contributions are welcome. The entire tool lives in a single file (`prompt_builder.html`) — HTML, CSS and JavaScript together.

Ideas for contributions:
- New examples (follow the `fillExampleXxx()` pattern in the JS)
- New languages
- Accessibility improvements
- Additional output formats

## License

MIT — free to use, modify and distribute.

---

Built by [CaladAI](https://caladai.com) · Shared because someone else might find it useful.
