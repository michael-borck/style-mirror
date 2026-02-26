# Style Mirror

AI-powered writing style analyzer and content generator. Paste your writing, extract your "Style DNA", then generate new content that matches your voice.

**[Try it live](https://stylemirror.serveur.au)**

## How It Works

1. **Source** — Feed in your writing through one of five pathways:
   - **Analyze Text** — Paste existing writing to extract your style
   - **Quick Write** — Respond to a prompt so the AI can study your voice
   - **Questionnaire** — Set tone and formality with sliders
   - **Mimic Persona** — Adopt the style of a famous writer or character
   - **Presets** — Choose from Academic, Marketing, or Storyteller profiles

2. **Style DNA** — The app extracts a structured profile: tone, structure, vocabulary, grammar, and quirks. You can edit any field before generating.

3. **Generate** — Pick a topic and format (email, blog post, essay, tweet) and the AI writes content matching your style profile.

## Supported LLM Providers

Style Mirror is provider-agnostic. Configure your preferred backend in the app:

| Provider | API Key | Notes |
|----------|---------|-------|
| **Google Gemini** | Required | Free tier at [ai.google.dev](https://ai.google.dev) |
| **Ollama** (local) | None | Free & private. Run `OLLAMA_ORIGINS=* ollama serve` for CORS |
| **OpenAI-compatible** | Varies | Works with Groq (free tier), Together.ai, LM Studio, etc. |

Configuration is saved to `localStorage` so you don't re-enter it each visit.

## Setup

No build step. It's a single HTML file.

**GitHub Pages:**
Enable Pages in your repo settings (Settings > Pages > deploy from `main`). Done.

**Local:**
```bash
git clone https://github.com/michael-borck/style-mirror.git
open style-mirror/index.html
```

## Tech Stack

- Single static HTML file — no backend, no build tools
- [Tailwind CSS](https://tailwindcss.com) (CDN) — styling
- [Lucide Icons](https://lucide.dev) — iconography
- [Marked.js](https://marked.js.org) — markdown rendering
- Space Grotesk + JetBrains Mono — typography
- Neobrutalist design system

## License

MIT — see [LICENSE](LICENSE) for details.
