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

## Updates

### What Happens When Skill Files Are Updated?

When skill files in a plugin are updated in the repository, users need to update their installed plugins to get the latest changes.

### How to Update Plugins

Users can update plugins in two ways:

**Manual Update:**

```
/plugin update plugin-name@marketplace-name
```

**Interactive Update:**

1. Run `/plugin`
2. Go to the **Installed** tab
3. Manage plugin updates from there

### Auto-Updates

This marketplace has auto-update **disabled by default** for third-party marketplaces. Users can enable it manually:

1. Run `/plugin`
2. Go to the **Marketplaces** tab
3. Select this marketplace
4. Choose **Enable auto-update**

When auto-update is enabled, Claude Code automatically:

- Refreshes the marketplace at startup
- Updates installed plugins from this marketplace automatically
- Shows a notification to restart Claude Code if plugins were updated

## About the Marketplace

This marketplace is powered by Claude Code's plugin distribution system. For more information about creating and distributing plugin marketplaces, see the [Create and distribute a plugin marketplace](https://github.com/claude-ai/claude-code-docs) documentation.

## Author

Yevgeniy Gavrilov  
Email: claude-code@gavrilov.kz
