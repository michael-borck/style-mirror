# Style Mirror

<!-- BADGES:START -->
[![client-side](https://img.shields.io/badge/-client--side-blue?style=flat-square)](https://github.com/topics/client-side) [![communication-tools](https://img.shields.io/badge/-communication--tools-blue?style=flat-square)](https://github.com/topics/communication-tools) [![conversation-analysis](https://img.shields.io/badge/-conversation--analysis-blue?style=flat-square)](https://github.com/topics/conversation-analysis) [![frontend](https://img.shields.io/badge/-frontend-blue?style=flat-square)](https://github.com/topics/frontend) [![html](https://img.shields.io/badge/-html-e34f26?style=flat-square)](https://github.com/topics/html) [![javascript](https://img.shields.io/badge/-javascript-f7df1e?style=flat-square)](https://github.com/topics/javascript) [![style-analysis](https://img.shields.io/badge/-style--analysis-blue?style=flat-square)](https://github.com/topics/style-analysis) [![text-processing](https://img.shields.io/badge/-text--processing-blue?style=flat-square)](https://github.com/topics/text-processing) [![web-app](https://img.shields.io/badge/-web--app-blue?style=flat-square)](https://github.com/topics/web-app) [![writing-analysis](https://img.shields.io/badge/-writing--analysis-blue?style=flat-square)](https://github.com/topics/writing-analysis)
<!-- BADGES:END -->

AI-powered writing style analyzer and content generator. Paste your writing, extract your "Style DNA", then generate new content that matches your voice.

**[Try it live](https://stylemirror.serveur.au)**

## How It Works

The app follows a three-column workflow: **Source → Style DNA → Generate**.

### Step 1: The Source

Choose one of five tabs to define your writing style (the icon row at the top of the first column):

| Tab | Icon | What it does |
|-----|------|-------------|
| **Analyze** | Search | Paste an existing piece of your writing (email, essay, blog post) and the AI extracts your style |
| **Quick Write** | Pencil | Respond to a writing prompt so the AI can study your voice from scratch |
| **Questionnaire** | Checklist | No AI needed — use sliders to set tone (serious↔humorous) and formality (casual↔academic) |
| **Mimic** | People | Pick a famous writer or character (Hemingway, Oscar Wilde, Rick Sanchez...) and the AI builds their style profile |
| **Presets** | Template | One-click profiles for common styles: Academic, Marketing, or Storyteller |

### Step 2: Style DNA

The middle column shows your extracted style profile — tone, structure, vocabulary, grammar, and quirks. Every field is editable, so you can tweak it before generating.

### Step 3: Generate

Pick a topic and format (paragraph, email, blog post, essay, or tweet) and hit **Generate**. The AI writes content matching your style profile. Copy or download the result.

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
