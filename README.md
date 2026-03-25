# 10 CLI Commands You Have Probably Never Used — But Should (2026)

> A practical guide for Linux beginners, sysadmins, DevOps engineers & terminal power users.

📖 **Read the full article:** [linuxteck.com/useful-linux-terminal-commands](https://www.linuxteck.com/useful-linux-terminal-commands/)

---

## What This Guide Covers

- 10 lesser-known but powerful Linux CLI tools tested on Ubuntu 22.04, Ubuntu 24.04 & RHEL 8
- Install methods for every tool via apt, brew, and cargo
- 2 real command examples per tool — 20 total
- Grouped into 5 themed sections: Pure Joy, Actually Useful, Dashboard & Visibility, Power User Picks, Bonus Wildcard
- A "Who should install what first?" quick-start guide by role
- FAQ section targeting common "People also ask" questions

---

## Tools Covered

| Tool | Best For |
|------|----------|
| cbonsai | Animated ASCII bonsai tree — terminal screensaver |
| glow | Rendering Markdown files beautifully in the terminal |
| navi | Interactive fuzzy cheatsheet browser powered by fzf |
| tldr | Simplified, example-first man pages |
| gping | Real-time ASCII latency graph for network monitoring |
| wtfutil | Fully configurable personal terminal dashboard |
| pv | Live progress bar and ETA for any pipe operation |
| ncdu | Interactive ncurses disk usage analyser |
| bat | Syntax-highlighted, git-aware cat replacement |
| hyperfine | Statistical command benchmarking tool |

---

## Install Quick Reference

| Tool | apt | brew | cargo / go / npm |
|------|-----|------|------------------|
| cbonsai | `apt install cbonsai` | `brew install cbonsai` | — |
| glow | — | `brew install glow` | `go install github.com/charmbracelet/glow@latest` |
| navi | — | `brew install navi` | `cargo install navi` |
| tldr | `apt install tldr` | `brew install tldr` | `npm install -g tldr` |
| gping | — | `brew install gping` | `cargo install gping` |
| wtfutil | — | `brew install wtfutil` | `go install github.com/wtfutil/wtf@latest` |
| pv | `apt install pv` | `brew install pv` | — |
| ncdu | `apt install ncdu` | `brew install ncdu` | — |
| bat | `apt install bat` | `brew install bat` | `cargo install bat` |
| hyperfine | — | `brew install hyperfine` | `cargo install hyperfine` |

> All 10 tools are free, open source, and actively maintained as of 2026.

---

## Who Should Install What First?

| Role | Start With | Why |
|------|------------|-----|
| 🟢 Beginners | `tldr` + `bat` | tldr simplifies man pages; bat makes reading files far more readable |
| 🔵 Sysadmins | `ncdu` + `pv` | ncdu makes disk cleanup visual; pv gives visibility into long pipe operations |
| 🔴 DevOps / Developers | `hyperfine` + `gping` | hyperfine benchmarks commands statistically; gping visualises latency instantly |
| 🟡 Everyone | `wtfutil` | Once comfortable in the terminal, wtfutil turns it into a personal dashboard |

---

## Full Guide

👉 [Read the complete guide on LinuxTeck](https://www.linuxteck.com/useful-linux-terminal-commands/)

---

## Author

**LinuxTeck** — A Complete Linux Learning Blog  
🌐 [www.linuxteck.com](https://www.linuxteck.com)

---

### 🏷️ Add Topics/Tags to Your Repository

1. On your repository page click the **gear icon ⚙️** next to "About"
2. Add these topics:
