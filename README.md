# WARGATE

A real-time strategy and autobattler game, built solo, in the browser. No engine, no framework, no install: around 31,000 lines of vanilla HTML and JavaScript.

**Play it here:** https://YOUR-USERNAME.github.io/wargate/

## What it is

WARGATE blends RTS control with autobattler flow. You build your force, position it, and fight through scripted campaign missions or open skirmish battles against an active enemy AI.

- Two full campaign missions with scripted objectives and events
- Skirmish mode for open battles
- Custom unit AI: targeting, movement, and battle flow written from scratch
- Economy and force-building systems
- Runs entirely client-side in any modern browser

## How it was built

This project is partly a game and partly a proving ground for an AI-first way of building software.

I'm a product manager with a computer science background, not a working engineer. WARGATE was built with Claude Code as a genuine pair: working against the full codebase, with structured project context, and with my own design judgment and review on everything that shipped. No generated code went in that I couldn't explain.

It's where I've tested how far AI-assisted development scales as a codebase grows past 30,000 lines, what breaks when context gets large, and how much a non-engineer can realistically ship alone. The workflow lessons transfer directly to how I work as a PM: when an idea is ambiguous, build the working thing instead of writing another document.

## Running locally

Clone the repo and open `index.html` in a browser. That's it. Everything runs client-side.

```
git clone https://github.com/YOUR-USERNAME/wargate.git
cd wargate
```

Then open `index.html`, or serve it locally if you prefer:

```
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Status and roadmap

The HTML/JS build is mature and playable. Next explorations: a MonoGame (C#) port, and a 3D remake of skirmish mode.

## About

Built by Stephen Finch, a product leader working in AI and data-heavy B2B SaaS. More at [linkedin.com/in/stephenfinch1](https://linkedin.com/in/stephenfinch1).
