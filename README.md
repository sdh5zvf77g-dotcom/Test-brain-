# Agent World

**Multi-AI agent workspace** — put a problem in, agents work on it in parallel, compare answers, save findings, and synthesize a stronger final solution.

## Live on GitHub Pages

1. Create a new GitHub repository (public).
2. Upload **all** files from this folder to the **root** of the repo (not inside a subfolder).
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch** → Branch: `main` (or `master`) → Folder: `/ (root)` → Save.
5. Wait 1–2 minutes, then open:  
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

**Important:** Do **not** open the HTML via the GitHub “raw” or “blob” file viewer. That breaks icons and API calls. Use the GitHub Pages URL above.

## Features

- **Multi-agent mode (default)** — select agents, they solve the problem independently in parallel
- **Side-by-side comparison** of every answer
- **Save finding** button on each agent card → persistent Agent findings log
- **Synthesize** — one agent merges the best of all answers into a stronger final result
- Scientific roles + workflow templates
- Auto-save (conversation, findings, API keys) on the device
- Installable PWA with brain icon (iPhone 15 Pro Max ready)

## Setup (one time)

1. Get a free API key: [openrouter.ai/keys](https://openrouter.ai/keys)
2. Open the app → tap **⚙** on any free agent → paste the key
3. The same key works for all free OpenRouter models

## Included agents

| Agent | Notes |
|-------|--------|
| OpenRouter Free | Auto-router |
| Nemotron 3 Ultra / Super / Lightning | Strong free reasoning |
| Gemma 4 31B | Multimodal free |
| Inkling | Long context free |
| North Mini Code | Coding free |
| Qwen3.8 27B | Free |
| Qwen3.8 Max | Paid flagship |
| Ollama Local | No key (needs local Ollama) |

## Files

```
index.html              ← main app (GitHub Pages entry)
agent-world.html        ← same app (backup name)
manifest.webmanifest
README.md
icons/
  apple-touch-icon.png
  icon-192.png
  icon-512.png
  icon-1024.png
  favicon-32.png
```

## License

Free to use. The app only calls endpoints you configure and authorize.
