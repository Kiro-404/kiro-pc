<div align="left">

# Kiro Agent

An AI coding agent that runs on your own API key (BYOK). A VS Code extension and a standalone desktop app.

**Latest release: v0.1.0**

---

## ⬇️ Download

From the [Releases](https://github.com/Kiro-404/kiro-pc/releases/latest) page:

| File | What it is | Who it's for |
|---|---|---|
| **kiro-agent-0.1.0.vsix** | VS Code extension: chat plus real file and command execution | Anyone using VS Code |
| **KiroPC.exe** | Standalone desktop app (23 MB) — run it directly, no install | Instant use |

---

## ⚡ Up and running in two minutes

### A) Inside VS Code

1. Download `kiro-agent-0.1.0.vsix`.
2. Install it from the terminal:

   ```bash
   code --install-extension kiro-agent-0.1.0.vsix --force
   ```

   Or from VS Code: **Extensions ← ⋯ ← Install from VSIX…**
3. Open Kiro with `Ctrl+Alt+K` or the K icon in the activity bar.
4. In the extension settings: pick a provider and model, paste your key, and click **Test connection**.

### B) Desktop app

1. Download `KiroPC.exe` and run it. If SmartScreen appears: **More info ← Run anyway**.
2. Open ⚙ **Settings** ← pick a provider ← enter the model name ← paste your key.
3. Click **Test connection**, then describe your task and press send.

---

## ✅ Requirements

- **Windows 10/11 (64-bit)**
- **VS Code 1.90 or newer** — if you use the extension
- **One API key** from a supported provider:
  `Google Gemini` · `Groq` · `OpenRouter` · `Ollama (local, no key)` · and more
- No accounts with us and no bundled keys — the key is yours and stays on your machine.

---

## ✨ Features

- **Agent chat inside VS Code**: live steps, approvals, and provider/model switching.
- **Real execution**: read/write files, terminal, and browser — not just text.
- **Background-first**: shell commands and APIs are preferred over fragile UI automation.
- **Per-project rules** via `KIRO.md` or `AGENTS.md` in any folder.
- **Skills from GitHub**: download a `SKILL.md` and use it without writing code.
- **MCP**: connect external tools (files, databases, browsers…).
- **Project memory, checkpoints, and cost/token counters**.
- **Kiro Dark** theme included.

---

## 🔒 Security and privacy

- Keys are stored locally on your machine, and requests go straight to the provider you choose.
- No middle server of ours, and no data collection.
- Key files are excluded from the repository and from releases.

---

## 🧾 Terms

- **Free to use** for personal and professional work.
- **The source code is not published**: redistribution, resale, or republishing as your own product is not allowed without written permission.
- The software is provided "as is", without warranty.

---

## 🔑 Verify file integrity (SHA-256)

```
1cbab41cc6c2a07c466100fc16f46d231fd1c7a6a27d12f4ba3e983335f74109  kiro-agent-0.1.0.vsix
58b0153313c2f3ebaec465de5ae37f6e5332bceb58b9b305ef0914fd2382782f  KiroPC.exe
```

On Windows:

```powershell
Get-FileHash .\KiroPC.exe -Algorithm SHA256
```

---

## 💬 Support

- Found a problem or have a suggestion? Open an [Issue](https://github.com/Kiro-404/kiro-pc/issues).
- Before reporting, try **Test connection** in the settings to make sure your key works.

</div>
