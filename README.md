<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=800&color=7C3AED&center=true&vCenter=true&width=600&height=60&lines=Neovim+Setup" alt="Typing Animation" />
</div>

<p align="center">
  A personalized Neovim configuration — sleek, modern, and built for productivity.
</p>

## About

A Lua-powered Neovim setup using lazy.nvim, the Sonokai colorscheme, Codeium completions, Treesitter highlighting, and a few fun surprises.

<div align="center">

![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![lazy.nvim](https://img.shields.io/badge/lazy.nvim-000000?style=for-the-badge&logo=lazyvim&logoColor=white)

</div>

## Features

<div align="center">

- **Blazing-Fast Performance** — Native Lua config for optimal speed
- **lazy.nvim** — Dynamic plugin loading for fast startup
- **Sonokai Theme** — Clean, vibrant colorscheme
- **Codeium AI** — Auto-completions powered by Codeium
- **Treesitter** — Advanced syntax highlighting
- **Linting & Formatting** — ESLint + Prettier for JS, TS, JSON, Tailwind
- **Duck.nvim** — Hatch a duck with `:StartDuck`
- **Cellular Automaton** — Watch it rain with `:Rain`
- **Emoji.nvim** — Insert emojis on the fly

</div>

## Preview

<div align="center">

![Screenshot 1](https://github.com/user-attachments/assets/8dda11d9-84c9-463c-8d16-1b660db44868)

![Screenshot 2](https://github.com/user-attachments/assets/c22d7f70-4fde-4428-9453-52979140fe7c)

</div>

## Quick Commands

| Command | Action |
|---------|--------|
| `:StartDuck` | Hatch a duck |
| `:StopDuck` | Cook the duck (humanely) |
| `:Rain` | Watch cellular automata rain |

## Getting Started

### Prerequisites

- [Neovim](https://neovim.io/) 0.9+
- Git

### Install

```bash
git clone https://github.com/AmirabbasRouintan/nvim.git ~/.config/nvim
nvim --headless "+Lazy! sync" +qa
```

Open Neovim and let lazy.nvim install all plugins automatically.
