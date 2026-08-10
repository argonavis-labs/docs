# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Writing voice

All docs content must follow the style guide in `STYLE_GUIDE.md`. The voice is Kent's, built from his blog at [ewakened.com](https://ewakened.com). Read the style guide before writing or editing any page.

The short version:
- Write like a real person, not a content team
- No em dashes. Use periods or commas.
- No corporate jargon ("leverage", "synergy", "from day one")
- No fake enthusiasm ("game changer", "nails it")
- Mix short punchy lines with longer explanatory ones
- Open with the specific thing the reader came for, no preamble
- Ask the reader's question, then answer it: "Why the difference? Simply cost."
- Be specific: real numbers, real times, real app names
- Trust the reader. Don't over-explain.
- Use contractions. Write like you talk.

## Terminology

- "Runner" not "the Runner app" or "our product"
- "workspace" not "project" or "environment"
- "connected apps" not "integrations" or "connectors" (user-facing)
- "automation" not "scheduled task" or "cron job" (user-facing)

## Style rules

- Use active voice and second person ("you")
- Sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Keep card/link descriptions to one line

## Content boundaries

- Don't document internal admin features
- Don't reference internal tooling (Composio, MCP internals) in user-facing pages
- The MCP page (`connections/connect-your-own-mcp.mdx`) is the exception for technical users
