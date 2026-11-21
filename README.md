# Awesome-Terminal-Multiplexing-AI-Workspaces

# Top Terminal Multiplexing & AI Workspaces Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Terminal Multiplexers, Multi-Agent Coding Workspaces, Persistent PTY Sessions & GPU-Accelerated Split Terminals*  
**Last updated: November 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Terminal Multiplexing & AI Workspaces**. These tools manage split panes, persistent background sessions, vertical workspace tabs, embedded agent browsers, and real-time notification rings for orchestrating parallel CLI coding agents (such as Claude Code, Codex, OpenCode, and Gemini CLI) alongside traditional SSH workflows.

**Examples** include tmux, Zellij, GNU Screen, Byobu, WezTerm Multiplexer, Warp Workspaces, Hyper, iTerm2, Alacritty, and Rio (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for agent-aware terminal workspaces, classic and modern terminal multiplexers, GPU-accelerated workspace terminals, and CLI agent orchestrators — ideal for AI developers, systems engineers, DevOps teams, and terminal-first multitaskers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Warp Workspaces & Oz (`warp.dev`)](https://warp.dev)**  
  Agentic development environment and Rust-based terminal offering cloud-synced Warp Drive workspaces, multi-agent task orchestration, and collaborative team command sharing.

- **[cmux Pro / Cloud (`cmux.com`)](https://cmux.com/)**  
  Commercial cloud companion to `manaflow-ai/cmux` adding Cloud VMs, mobile iOS companion access, and managed cloud agent sandboxes.

- **[Termius](https://termius.com)**  
  Cross-platform SSH and Mosh workspace client featuring multi-pane split sessions, encrypted vault sync, and team server orchestration.

- **[Wave Terminal Cloud / Enterprise](https://waveterm.dev)**  
  AI-native open-core terminal workspace integrating inline web browsers, file previews, and multi-model AI blocks across local and remote SSH hosts.

- **[Gitpod / Ona Workspaces](https://gitpod.io)**  
  Cloud-hosted, ephemeral developer workspaces accessible via browser or SSH/tmux with pre-configured agentic terminal environments.

- **[Coder](https://coder.com)**  
  Enterprise self-hosted and cloud workspace platform provisioning standardized, SSH-accessible Linux development environments for engineers and AI agents.


## Open-Source GitHub Projects

- **[cmux (`manaflow-ai/cmux`)](https://github.com/manaflow-ai/cmux)**  
  Open-source Ghostty-based native macOS terminal built with Swift and AppKit featuring vertical workspace tabs, notification rings for parallel AI coding agents, a scriptable split browser, and a socket/CLI automation API.

- **[tmux (`tmux/tmux`)](https://github.com)**  
  Industry-standard terminal multiplexer allowing multiple persistent terminal sessions, windows, and split panes to be detached, reattached, and scripted inside a single window.

- **[Zellij (`zellij-org/zellij`)](https://github.com)**  
  Modern, batteries-included terminal workspace and multiplexer written in Rust with floating/stacked panes, declarative KDL layouts, multiplayer collaboration, and WebAssembly plugins.

- **[GNU Screen (`gnu.org/software/screen`)](https://gnu.org)**  
  Classic, ubiquitous full-screen window manager and terminal multiplexer that shares a physical terminal between multiple independent shell processes and serial consoles.

- **[Byobu (`dustinkirkland/byobu`)](https://github.com)**  
  User-friendly wrapper and profile configuration around `tmux` and GNU Screen adding live system status bars, hardware notifications, and intuitive function-key shortcuts.

- **[WezTerm (`wez/wezterm`)](https://github.com)**  
  GPU-accelerated cross-platform terminal emulator and built-in multiplexer written in Rust featuring native SSH/TLS multiplexing domains, tabs, splits, and Lua configuration.

- **[iTerm2 (`gnachman/iTerm2`)](https://github.com)**  
  Feature-rich macOS terminal emulator offering deep `tmux -CC` control mode integration, split panes, hotkey windows, triggers, and Python scripting APIs.

- **[Rio (`raphamorim/rio`)](https://github.com)**  
  Hardware-accelerated GPU terminal emulator written in Rust capable of running as a native desktop app or inside browsers via WebAssembly, with built-in splits and tabs.

- **[Alacritty (`alacritty/alacritty`)](https://github.com)**  
  Minimalist, ultra-fast OpenGL terminal emulator written in Rust, widely paired with `tmux` or `Zellij` as the rendering layer for lightweight multiplexed setups.

- **[Hyper (`vercel/hyper`)](https://github.com)**  
  Extensible, hackable terminal emulator built on web technologies (HTML/CSS/JS) with built-in split panes, tabs, and a rich plugin ecosystem.

- **[Ghostty (`ghostty-org/ghostty`)](https://github.com)**  
  Fast, native, GPU-accelerated terminal emulator written in Zig featuring native splits, tabs, and `libghostty` core rendering used by modern agentic terminal workspaces.

- **[limux (`am-will/limux`)](https://github.com/am-will/limux)**  
  GPU-accelerated terminal workspace manager and multiplexer for Linux inspired by `cmux` and powered by Ghostty's rendering engine.

- **[cmux for Windows (`mkurman/cmux-windows`)](https://github.com/mkurman/cmux-windows)**  
  Dark, keyboard-first terminal multiplexer and workspace manager for Windows inspired by `tmux` and `cmux` workflows, built natively with WPF and ConPTY.

- **[TUIOS (`Gaurav-Gosain/tuios`)](https://github.com)**  
  Terminal UI Operating System and tiling window manager written in Go with Vim modal navigation, persistent daemon sessions, and a unified coding agent Inbox.

- **[Wave Terminal (`wavetermdev/waveterm`)](https://github.com)**  
  Open-source AI-native terminal workspace combining traditional shell panes with persistent SSH sessions, inline Markdown/code viewers, and embedded web preview blocks.

- **[abduco & dvtm (`martanne/abduco` & `martanne/dvtm`)](https://github.com)**  
  Lightweight, Unix-philosophy pair of tools separating session detach/attach management (`abduco`) from dynamic tiling terminal window management (`dvtm`).

- **[mtm (`deadpixi/mtm`)](https://github.com)**  
  Micro Terminal Multiplexer written in clean, minimal C with zero external dependencies for ultra-lightweight split panes and tabbed terminal sessions.

- **[tmuxinator / tmuxp (`tmuxinator/tmuxinator` & `tmux-python/tmuxp`)](https://github.com)**  
  Declarative YAML/JSON session managers for `tmux` that automate spinning up multi-pane project layouts, dev servers, and parallel AI agent environments.

- **[zellij-switch & zellij-autolock (`mostafaqanbaryan/zellij-switch`)](https://github.com)**  
  Popular WebAssembly plugins extending Zellij with instant fuzzy session switching and automatic modal keybinding locking for nested editors like Neovim.

### Additional Strong Open-Source Options

- **[AI Agent Orchestrators for tmux & cmux](https://github.com)** like **using-cmux (`hummer98/using-cmux`)**, **claude-squad**, **agent-deck**, and **opencode-tmux** for spawning and monitoring parallel sub-agents in split panes.
- **[Terminal Session & Fuzzy Switchers](https://github.com)** including **sesh (`joshmedeski/sesh`)**, **tmux-sessionizer**, **tms (`jrmoulton/tms`)**, and **zoxide** for instant Git-aware workspace jumping.
- **[tmux Plugin Ecosystem](https://github.com)** such as **TPM (Tmux Plugin Manager)**, **tmux-resurrect**, **tmux-continuum**, and **catppuccin/tmux** for surviving system reboots.
- **[Browser-Based Multiplexed Terminals](https://github.com)** like **ttyd**, **Wetty**, and **Upterm** for secure peer-to-peer terminal sharing and collaborative pair programming.
- Many community **cmux Skills & Extensions (`manaflow-ai/cmux-skills`, `manaflow-ai/cmux-extensions`)** and **Zellij Wasm Layouts** for custom agent status bars.

**Frameworks for building custom systems**: Combine **cmux** (`manaflow-ai/cmux`) or **Zellij** / **tmux**, **sesh** or **tmuxp**, and **Claude Code / OpenCode** agent hooks for a high-throughput, parallel AI coding workspace in the terminal.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Multiplexers with socket APIs (`cmux`, `tmux`, `zellij`) or persistent background daemons allow external scripts and AI agents to send keystrokes and read screen buffers; keep socket permissions restricted to your local user account.
- When running autonomous AI coding agents across multiple terminal workspaces, review agent permissions and sandboxing rules to prevent unintended file or system modifications.

---

**Made for AI developers, terminal power users, systems engineers, and open-source builders.**  
Let's make terminal multitasking and agentic workspaces faster, cleaner, and more open.
