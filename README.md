# DrRacket Config

Modern keybindings for DrRacket with REPL integration. Provides Emacs-style incremental evaluation — send expressions and selections directly to the REPL without leaving the editor.

![Racket](https://img.shields.io/badge/Racket-9F1D20?logo=racket&logoColor=white) [![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

**English** · [中文](README.zh-CN.md)

## Features

- **Send to REPL** — Evaluate expressions incrementally, Emacs-style
  - Send the current top-level expression
  - Send the selected region
  - Optionally shift focus to the REPL panel after sending

## Requirements

| Dependency | Purpose / Version |
|------------|-------------------|
| DrRacket | 7.0 or later |

## Quick Start

### 1. Clone

```bash
git clone https://github.com/turlamai/drracket-config.git
cd drracket-config
```

### 2. Load the keybindings in DrRacket

- Go to **Edit** → **Keybindings** → **Add User-defined Keybindings...**
- Select `drracket-keybindings.rkt` from the cloned directory
- Restart DrRacket

## Keybindings

| Shortcut | Action |
|----------|--------|
| `Ctrl+C, Ctrl+E` | Send current expression to REPL |
| `Ctrl+C, Ctrl+R` | Send selected code to REPL |
| `Ctrl+C, Alt+E` | Send expression and focus REPL |
| `Ctrl+C, Alt+R` | Send selection and focus REPL |

**Usage:**

- Place cursor in or near an expression
- Press `Ctrl+C` then `Ctrl+E` to evaluate it in the REPL
- Or select code and press `Ctrl+C` then `Ctrl+R`

**Note:** You must run the program at least once (F5) to initialize the REPL before using these keybindings.

## Tips

- **View all active keybindings:** Edit → Keybindings → Show Active Keybindings

## Updating

```bash
cd /path/to/drracket-config
git pull
```

Then restart DrRacket.

## License

Licensed under the [MIT License](LICENSE).
