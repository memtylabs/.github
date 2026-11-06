<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/memtylabs/memty/main/assets/memty-wordmark-dark.png">
  <img src="https://raw.githubusercontent.com/memtylabs/memty/main/assets/memty-wordmark-light.png" alt="Memty" width="280">
</picture>

### Your AI memory, owned by you.

We build **Memty**: one private, local memory vault for every AI assistant you use.

[Website](https://memtylabs.github.io/memty/) · [Main repo](https://github.com/memtylabs/memty) · [PyPI](https://pypi.org/project/memty/) · [Changelog](https://github.com/memtylabs/memty/blob/main/memty/CHANGELOG.md)

[![PyPI](https://img.shields.io/pypi/v/memty.svg)](https://pypi.org/project/memty/)
[![Python](https://img.shields.io/pypi/pyversions/memty.svg)](https://pypi.org/project/memty/)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/memtylabs/memty/blob/main/LICENSE)

</div>

---

## 🧠 What is Memty?

Every AI assistant forgets you the moment you switch tabs. Memty fixes that.

It keeps the facts, decisions, and preferences you share with AI in **one SQLite file on your own computer**, and brings that memory to whichever assistant you open next: ChatGPT, Claude, Gemini, Perplexity, Cursor, or any MCP client.

- 🔒 **Local-first.** Your vault lives at `~/.memty/ledger.sqlite3`. No account, no cloud sync, no telemetry.
- 🌐 **Works everywhere.** A browser extension for chat websites, MCP for desktop and coding tools, the clipboard for anything else, and a Python API.
- ✅ **You're in control.** Facts saved from chats are proposals you approve. Edit, mark private, or delete anything.
- 🕶️ **Private by design.** Private facts reach cloud AIs only as `[private]`. Secret facts never leave your machine.

## 🚀 Get started

```shell
pip install memty

memty serve --autostart   # start the local bridge (one time)
memty extension --open    # install the browser extension
memty connect             # optional: Claude Desktop, Claude Code, Cursor, Windsurf
```

Then press **Alt+M** in ChatGPT, Claude.ai, Gemini, or Perplexity to bring your memory into the chat.

## 📦 Projects

| Repository | What it is |
| --- | --- |
| [**memty**](https://github.com/memtylabs/memty) | The memory vault, CLI, MCP server, browser extension, and model-routing SDK |

## 🤝 Contribute

Memty is open source under the MIT license and in active alpha (0.x). Bug reports, ideas, and pull requests are welcome.

- Read the [contributing guide](https://github.com/memtylabs/memty/blob/main/CONTRIBUTING.md)
- Browse [open issues](https://github.com/memtylabs/memty/issues)
- ⭐ Star [memty](https://github.com/memtylabs/memty) if it saves you from repeating yourself

<div align="center">

<sub>Made with care by Memty Labs · Your memory stays yours.</sub>

</div>
