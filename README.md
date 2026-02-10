# Yevgeniy Gavrilov's Plugin Marketplace

A Claude Code plugin marketplace featuring curated plugins for enhancing your Claude Code experience.

## Available Plugins

- **claude-code-skill-master-plugin** (v1.0.0) - A Claude Code plugin that adds the Skill Master skill — a guided assistant for creating and editing Claude Code skills with proper structure and frontmatter.

## Installation

### Step 1: Add the Marketplace

Add this marketplace to your Claude Code configuration:

```
/plugin marketplace add git@github.com:ygavrilov/claude-code-marketplace.git
```

### Step 2: Install a Plugin

Once the marketplace is added, install plugins from it:

```
/plugin install claude-code-skill-master-plugin@ygavrilov-marketplace
```

## About the Marketplace

This marketplace is powered by Claude Code's plugin distribution system. For more information about creating and distributing plugin marketplaces, see the [Create and distribute a plugin marketplace](https://github.com/claude-ai/claude-code-docs) documentation.

## Author

Yevgeniy Gavrilov  
Email: claude-code@gavrilov.kz
