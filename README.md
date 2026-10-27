# AI Operating System Starter

A simple folder structure that turns Claude Code or ChatGPT's Codex into an assistant that actually knows your business.

Built by [Patrick Rice](https://www.youtube.com/@patrickriceco). Full walkthrough: [How To Automate Your Business With AI Agents (ZERO Coding Required)](https://www.youtube.com/watch?v=JyZmg2cEG84)

## The idea
Think of an old-school filing cabinet. Every part of your business gets its own folder, and one map file tells the AI who you are and where everything lives. The AI reads that map at the start of every conversation, so you stop re-explaining your business in every prompt.

There are two copies of the map, one per tool:
- `CLAUDE.md` is read by **Claude Code**
- `AGENTS.md` is read by **Codex** (ChatGPT's coding agent)

They start identical. Use whichever tool you prefer. If you use both, keep the two files in sync (just ask the AI to do it).

## Setup with Claude (10 minutes)
1. Download this repo (green **Code** button, then **Download ZIP**) and unzip it somewhere you'll keep it.
2. Rename the folder to your business name.
3. Install the Claude desktop app and open the **Code** tab.
4. Click **Choose folder** and pick this folder.
5. Say: *"Read CLAUDE.md and every CONTEXT.md, then interview me to fill them in for my business."*

## Setup with ChatGPT (10 minutes)
1. Download and rename the folder (steps 1 and 2 above).
2. Install the Codex app from OpenAI and sign in with your ChatGPT account.
3. Open this folder as your project.
4. Say: *"Read AGENTS.md and every CONTEXT.md, then interview me to fill them in for my business."*

That's it. Talk to it like a person. You don't need long prompts.

## What's inside
```
CLAUDE.md              the map the AI reads every time
Vision/                goals and priorities
Sales-and-Marketing/   offers, pricing, brand voice
Clients/               one folder per client (copy _Example-Client)
Finance/               money notes (live numbers stay in your tools)
Operations/            SOPs and checklists
Team/                  roles and ownership
Knowledge/             your second brain
Archive/               old stuff
```

## Tips
- **Fill Operations first.** Explain a process out loud, paste the transcript, and ask the AI to write the SOP.
- **Fix rules where they live.** When the AI gets something wrong, have it update the right CONTEXT.md so it sticks.
- **Rename anything.** These folders are a starting point, not a standard.

## License
MIT. Use it, change it, share it.
