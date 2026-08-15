# Marko Stankovic

### AI engineer. I build AI systems and prove they work.

[markostankovic.org](https://markostankovic.org) · [Book a call](https://markostankovic.org/call) · [LinkedIn](https://www.linkedin.com/in/marko-builds/) · [contact@markostankovic.org](mailto:contact@markostankovic.org)

---

[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)](https://claude.com/claude-code)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)](https://archlinux.org)

---

### How I work

I run a personal AI operating system I built on Claude Code. It drives my whole build pipeline: a library of reusable automation skills, multi-agent orchestration, custom subagents, and integrations into email, calendar, and GitHub.

One loop runs while I sleep. It picks the next unblocked issue off a backlog, implements it test-first, and has to pass an automated code review before anything gets committed. Whole feature branches ship this way.

Driving agents is the easy half. The harder half is judging what they produce, so the discipline around them is where the work goes: test-driven tracer bullets, a zero-context red-team review on every non-trivial plan, and nothing counts as done without fresh passing evidence.

It started as [Nate Herk's AIS-OS](https://github.com/nateherkai/AIS-OS) starter kit, three skills and a framework. Mine has grown well past that: hooks, an issue backlog, and the overnight loop above.

**Most of that system is private, because it runs my life and not just my code.** So what you see below are the pieces I pulled out of it, plus the products it helped build.

---

### Products

**[DeployLog](https://deploylog.dev)**: release notes from your deploys. Full-stack SaaS built end-to-end. A hosted page, an embeddable widget, an [npm CLI](https://github.com/marko-builds/deploylog-cli) that turns git commits into release notes with an LLM, and a GitHub Action. Launching.

**Habitagram**: habit tracking as a journey. A React Native app where your habits move a boat across illustrated landscapes that shift with the time of day. The art is rendered from code, not drawn. Near launch.

---

### Open source

**[skill-vibe-test](https://github.com/marko-builds/skill-vibe-test)**: does your Claude Code skill still steer the model after 10 turns, or has it quietly stopped working? Scripted conversation, LLM judge, decay chart. I wrote it because I kept guessing at the answer. One of my own skills failed it.

**[adpreflight](https://github.com/marko-builds/adpreflight)**: checks a hand-coded HTML5 playable ad against network rule packs before you submit it, so the rejection lands on your machine instead of in an email three days later. One command, no clone. Every limit cites its primary source and retrieval date inline, rules are marked cited or derived so you can see which are inferred, and a third exit code means "no verdict established" rather than letting an unearned pass through.

**[duskpaper](https://github.com/marko-builds/duskpaper)**: generative animated wallpapers for Wayland, rendered on your machine, at your resolution, with your seed. The public face of the procedural engines behind Habitagram's art.

**[BlenderBridge](https://github.com/marko-builds/BlenderBridge)**: one-click validated Blender to Unreal asset ingest. Naming enforcement, normal maps, lightmap UVs, and a pre-flight report. Hybrid C++ and Python editor plugin.

---

### Background

Three years on game systems in Unity and Unreal before this (BSc Game Development, ex-Replai): save, survival, and inventory systems behind clean interfaces, documented with ADRs and tests. The habits came with me. The engine changed.

---

### Toolbox

Claude Code · Anthropic API · MCP · multi-agent workflows · evals

TypeScript / Node (Next.js, Supabase) · Python · React Native · C# · C++ · Unity · Unreal Engine 5 · Blender

CLI-first on Arch Linux, automation everywhere.
