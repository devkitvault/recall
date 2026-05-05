# Recall - Cloud-Synced CLI Command Vault

Recall is a CLI command manager that helps developers save, search, organize, and run terminal commands from anywhere.  
It combines a fast local CLI workflow with a secure cloud vault for cross-device sync.

## Why Recall

- Save reusable commands with names and tags
- Search and run commands instantly from your terminal
- Organize commands with groups, templates, snippets, aliases, and env sets
- Sync across machines with your Recall account
- Scale from personal workflows to team vaults

## Install Recall CLI

### Installation Types

- Script install (recommended): fastest setup for most users
- npm package: install via `@devkitvault/recall`
- Native binaries: direct download from GitHub Releases

### macOS / Linux

```sh
curl -fsSL https://devkitvault.com/recall/install.sh | sh
```

### Windows (PowerShell)

```powershell
irm https://devkitvault.com/recall/install.ps1 | iex
```

### npm

```sh
npm install -g @devkitvault/recall
```

### GitHub Releases

Download platform binaries from the releases page:  
`https://github.com/devkitvault/recall/releases`

## Quick Start

```sh
# authenticate
recall auth login

# save a command
recall save "git log --oneline -10" --name git-log --tags git

# list and search
recall list
recall list --search docker
recall list --tag git

# run a saved command
recall run git-log
```

## Core Features

- Command vault with tagging and fast search
- Templates for parameterized commands
- Snippets and aliases for repeatable workflows
- Environment sets for reusable terminal variables
- Team-ready org vault support
- Web dashboard and VS Code extension support

## Feature Comparison

| Feature | Free | Pro | Team |
| --- | --- | --- | --- |
| Save commands | Yes | Yes | Yes |
| List and search commands | Yes | Yes | Yes |
| Run saved commands | Yes | Yes | Yes |
| Command groups | No | Yes | Yes |
| Templates | No | Yes | Yes |
| Snippets | No | Yes | Yes |
| Env sets | No | Yes | Yes |
| Org vaults | No | No | Yes |
| VS Code extension support | Yes | Yes | Yes |

## Pricing

- Free: core command save, list, search, and run
- Pro: advanced organization and productivity features
- Team: collaboration-ready vault features for teams

See full pricing at `https://devkitvault.com/recall`.

## Product Links

- Website: `https://devkitvault.com/recall`
- Dashboard: `https://recall.devkitvault.com`
- API: `https://api.devkitvault.com`
- VS Code Extension: `https://marketplace.visualstudio.com/items?itemName=devkitvault.recall-cmd`

## Keywords

CLI command manager, terminal command history, command vault, shell productivity, developer tools, command snippets, reusable terminal workflows.
