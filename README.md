# Pocket Actions Layer (PAL) – Prototype

A clickable product prototype for an "Actions Layer" in Pocket: once a voice recording finishes, PAL turns it into structured follow-ups – a Notion page, a task list, a Slack update and CRM notes – that you can review, edit inline and send in one pass.

**Live demo:** https://pocket-pal-prototype.vercel.app

## What to look at

- The flow from a finished recording → suggested actions → review → push to tools
- Inline editing of generated tasks before anything is sent
- Per-destination toggles (e.g. turning CRM sync on/off)

All AI output in the prototype is mocked; nothing is sent anywhere.

## Run locally

It's a single static page with no build step – open `index.html` in a browser. React 18 and Tailwind load from CDN.

## Note

Independent product concept; not affiliated with or endorsed by Pocket.
