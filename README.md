# Claude Code Plugin: Project Context

> **Rapid Project Orientation** - Scan CLAUDE.md files and surface the context developers need.

A focused Claude Code plugin that analyzes CLAUDE.md documentation and summarizes the most important details about a project's scope, structure, dependencies, and conventions. Install it when you want quick situational awareness without loading a larger plugin marketplace.

## Plugins

- `project-context` - Scan `CLAUDE.md` files to produce a structured, shareable project brief.
- Coming soon — additional plugins will be added as they are developed.

## Overview

- **Token Efficient** - Loads just one command into context when installed.
- **Developer Onboarding** - Produces a concise, structured brief of the project documentation.

## Key Features

- Locates every `CLAUDE.md` file from the project root downward.
- Extracts document structure, architectural cues, conventions, and dependency information.
- Provides a ready-to-share project context analysis, or prompts for documentation if missing.

## Quick Start

### Step 1: Add the Marketplace

Add this marketplace to Claude Code:

``` bah
/plugin marketplace add iasonasgeorgiadis/plugins
```

### Step 2: Install Plugins

Browse available plugins in Claude Code and select the ones you want to install: 

```bash
/plugin 
```


### Step 3: Run the Command

For example, you can install the project-context plugin. This plugin exposes a single command for scanning project documentation:

```bash
/project-context:scan-context
```

Claude will search for `CLAUDE.md` files, analyze their contents, and respond with a structured project context brief.
