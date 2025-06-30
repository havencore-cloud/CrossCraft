# CrossCraft: An Open Source Compiler for Universal Minecraft Modding

A proposal for uniting Java and Bedrock modding under one open, creator-friendly tool.

---

## The Problem

Minecraft is one of the greatest sandboxes for creativity the world has ever known. But Minecraft modding today is fractured:

- **Java Edition** lets players freely create deep, powerful mods — but they only work on PC, and writing them requires coding in Java.
- **Bedrock Edition** runs on mobile, consoles, and modern Windows — but modding is limited to Add-Ons (JSON + scripts), with no deep engine changes possible.

Modders who want to create for both editions must double their work.  
Players are left behind: mods they love on Java often don't exist on Bedrock.

---

## Our Vision

CrossCraft is an open source project to build:

- A universal mod definition language (YAML/DSL) that lets creators define blocks, items, entities, and recipes once.
- A compiler that outputs:
  - Java code compatible with Forge/Fabric (Java Edition)
  - JSON + official scripts compatible with Bedrock Add-Ons (where supported)

---

## What CrossCraft Will — and Won't — Do

- Open source and ethical — No reverse-engineering or violating terms of service.
- Respect the limitations of Bedrock's official APIs — no runtime hacks or injected code.
- Make it easier for creators to build for both editions at once.
- Warn when a feature can't map cleanly (e.g., custom AI not supported on Bedrock).

CrossCraft will **not**:
- Inject code into Bedrock, reverse-engineer its internals, or break platform rules.
- Promise feature parity where it's impossible — it will make limitations transparent.

---

## Architecture Overview

- **Input**: A high-level mod definition file (e.g. `my_mod.yaml`)
- **Compiler**: Converts to edition-specific outputs
- **Outputs**:
  - Java Edition: Forge/Fabric code skeleton
  - Bedrock: Add-On JSON + scripts (where possible)

---

## Roadmap

1. Define the DSL (YAML or custom syntax)
2. Build minimal compiler: support for basic blocks + items
3. Expand: recipes, entities, loot tables
4. Build helper tools (web editor, validator)
5. Grow through community contributions

---

## Call to Action

We're inviting modders, developers, artists, testers, and dreamers to join us.  
Whether you can code, write docs, or test output — your help matters.

---

## License

We propose using the **MIT License** — permissive, pro-creator, open.

---

## Get Involved

- GitHub: [link coming once repo created]
- Chat: [we can set up a Discord / Matrix / etc. if desired]

---

## Why Open Source?

Because Minecraft was built on community. CrossCraft will be too.  
Together, we can make modding more accessible, fair, and fun.

---

## Next Steps

- We will work on CrossCraft on weekends.
- First goal: working proof-of-concept compiler for basic blocks.

---

## Closing Thought

> "The best way to predict the future is to build it." — Alan Kay
