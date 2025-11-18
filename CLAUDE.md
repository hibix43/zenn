# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Answer's language

日本語で回答してください。

## Project Overview

This is a Zenn content repository for publishing technical articles. Zenn is a Japanese technical blogging platform where developers can write and publish articles in Markdown format.

## Repository Structure

- `articles/` - Contains individual Markdown articles with frontmatter metadata
- `books/` - Directory for Zenn book content (currently empty)
- `images/` - Static assets and images used in articles
- `package.json` - Project configuration with zenn-cli dependency

## Key Commands

Since this repository uses zenn-cli for content management:

```bash
# Install dependencies
npm install

# Preview articles locally (if zenn-cli supports it)
npx zenn preview

# Create a new article
npx zenn new:article

# Create a new book
npx zenn new:book
```

## Article Format

Articles are written in Markdown with YAML frontmatter containing:

- `title` - Article title
- `emoji` - Display emoji
- `type` - Either "tech" (technical) or "idea" (idea/opinion)
- `topics` - Array of topic tags
- `published` - Boolean for publication status

## Development Notes

- Articles are primarily written in Japanese
- Content focuses on technical topics, particularly Flutter/mobile development
- Images are organized in subdirectories under `images/` by topic
- The repository follows Zenn's content structure and conventions

## External Resources

- [Zenn Platform](https://zenn.dev/)
- [Zenn CLI Guide](https://zenn.dev/zenn/articles/zenn-cli-guide)
