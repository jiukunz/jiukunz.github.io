# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal static site for **jiukun.me**, deployed via GitHub Pages. GitHub account: `jiukunz`.

## Deployment

- Repository: `jiukunz/jiukunz.github.io` on GitHub
- Remote: `git@github.com:jiukunz/jiukunz.github.io.git`
- Branch: `main`
- GitHub Pages serves from root (`/`)
- Custom domain: `jiukun.me` (CNAME file in repo root)

## Development

This is a static site — no build step required unless a framework (Astro, etc.) is added later.

- Local preview: open `index.html` in browser, or use `npx serve .`
- Push to `main` triggers GitHub Pages deployment

## Architecture

Flat file structure. Static HTML/CSS/JS served directly by GitHub Pages.
