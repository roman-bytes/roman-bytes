# Jacob Roman

**Prompt Engineer & AI builder** · Michigan

I design and ship AI agents and the tools around them: privacy-safe assistants, CMS explorers, and small, focused apps. My background is full-stack TypeScript. Personal work lives under [Roman Bytes](https://romanbytes.dev); consulting is [Roman Forge](https://romanforge.dev).

Open to Prompt Engineer and AI builder roles.

## What I build now

- **AI agents** with tool calling — small, testable systems that do one job well
- **Privacy-safe assistants** designed so the model never sees emails or raw IDs
- **CMS tooling** for understanding content models, fields, and dependencies

## Featured projects

**[mini-cdp](https://github.com/roman-bytes/mini-cdp)** — [live demo](https://mini-cdp.romanbytes.workers.dev/)  
A mini customer data platform that pulls newsletter, website, and mobile-app data into one database, links records that belong to the same person, and shows the result in one place. It includes a Gemini assistant with a PII firewall: requests are checked before they are sent, and tests assert that the model never sees emails or raw IDs. Built with Next.js on Cloudflare Workers (OpenNext), Postgres (Neon), and Drizzle. Parts of the original plan are still unbuilt.

**[kinkeeper](https://github.com/roman-bytes/kinkeeper)**  
An AI agent that helps you nurture the relationships that matter. It tracks people you care about, flags who you are overdue to reach out to, and drafts a short check-in from notes on file. It never sends the message for you. LangGraph ReAct agent with tool calling, Claude, FastAPI, and SQLite. The store and non-agent API routes are unit-tested. Small on purpose; API-only, no UI yet.

**[geo-search-demo](https://github.com/roman-bytes/geo-search-demo)**  
A React + TypeScript map search demo over high-density point data: about 2,500 synthetic “sightings,” clustered in MapLibre GL, with live filters and two-way selection between the map and a results list. All data is generated in the browser from a seeded PRNG — no real people, plates, or locations. Vite; runs with no API token.

**[contentstack-explorer](https://github.com/roman-bytes/contentstack-explorer)**  
A read-only dashboard that introspects a Contentstack instance: model catalog with published entry counts, a field inspector, a dependency graph (depends-on / used-by), and orphans. Uses the Delivery API and a delivery token only — no Management token, no writes. Data is snapped at build time into a static site.

## Stack

TypeScript, React, Next.js, Node.js, Tailwind, Cloudflare Workers, Python, LangGraph, FastAPI, Postgres, SQLite, Vite, Docker. Models I have wired up in public work: Claude and Gemini.

<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="28" alt="TypeScript" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="28" alt="JavaScript" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="28" alt="React" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="28" alt="Next.js" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="28" alt="Node.js" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="28" alt="Python" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" height="28" alt="Tailwind CSS" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="28" alt="Docker" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="28" alt="PostgreSQL" />
</div>

## Links

[romanbytes.dev](https://romanbytes.dev) · [romanforge.dev](https://romanforge.dev) · [X @romanbytes](https://x.com/romanbytes) · [LinkedIn](https://www.linkedin.com/in/jacobroman)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=roman-bytes&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=roman-bytes&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="Top languages" />
</div>
