<div align="center">

# Claude Unreal

### Control Unreal Engine 5 with natural language.

An **MCP server** that lets **Claude Code** — or any MCP client (Cursor, Cline, Windsurf, Antigravity) — drive the Unreal Editor directly: spawn actors, wire Blueprints, build UMG menus, tune Niagara VFX, direct Sequencer cameras, sculpt landscapes, grow PCG worlds, and package builds.

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.7%20%26%205.8-0E1128?logo=unrealengine&logoColor=white)](https://www.unrealengine.com)
[![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-server-6E56CF)](https://modelcontextprotocol.io/)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey)]()
[![Get it on Fab](https://img.shields.io/badge/Fab-Get%20it%20%E2%80%94%20%2499-FF6B00)](https://www.fab.com/listings/4ee41200-fc67-480d-8857-4319ec5cdf72)

**[Website](https://echoulen.github.io/claude-unreal/)** ·
**[Documentation](https://echoulen.github.io/claude-unreal/docs/)** ·
**[Get it on Fab](https://www.fab.com/listings/4ee41200-fc67-480d-8857-4319ec5cdf72)** ·
**[YouTube](https://www.youtube.com/@Yooadev)**

<a href="https://youtu.be/V5CfOqai6Q0">
  <img src="https://img.youtube.com/vi/V5CfOqai6Q0/maxresdefault.jpg" alt="Claude Unreal showreel" width="640">
</a>

**▶ [Watch the 52-second showreel](https://youtu.be/V5CfOqai6Q0)**

</div>

---

## What it is

You type what you want in plain English. The agent does it in your live Unreal Editor — no boilerplate, no clicking through menus, no writing editor utilities.

```
> Build me a walled town from this spline, with a gate facing the road
> Turn this spaghetti Blueprint into a clean, commented graph
> Light this scene for golden hour and give me a cinematic flythrough
```

Claude Unreal exposes **16 typed MCP tools** for the hot path (spawn / move / inspect / screenshot) plus a bundled **`cu` CLI** reaching all **486 commands across 23 categories** — Blueprint, UMG, Niagara, Sequencer, materials, lighting, landscape, PCG, packaging, and more. The split keeps session-start context small while preserving full editor control.

On **UE 5.8** it can also mount its entire toolset onto Unreal's built-in official MCP server, so any agent that already speaks UE's official MCP gets the whole surface from one endpoint.

## Watch it work

Every episode is one unscripted session — the agent builds it live.

| # | Episode | # | Episode |
|---|---|---|---|
| 20 | [67-House Medieval Town (Town Planner)](https://youtu.be/2EFuMX3zanE) | 10 | [Builds a Locomotion State Machine (Anim BP)](https://youtu.be/_hFzSk0BhYk) |
| 19 | [Interactive House Picker (Workflows)](https://youtu.be/I7JZoKy3mpU) | 9 | [Builds a Brand Reveal (Materials + 3D Text)](https://youtu.be/Ohu41IaiGtA) |
| 18 | [Grows a Medieval Town (PCG Splines)](https://youtu.be/P_t38d9YEt4) | 8 | [Directs a Cinematic Camera (Sequencer)](https://youtu.be/iU3twT9ayfg) |
| 17 | [Builds a Volcanic Caldera (Niagara Eruption)](https://youtu.be/0VAk1lwIG20) | 7 | [Grows a Procedural Forest (PCG)](https://youtu.be/o2df5KTY7ks) |
| 16 | [Builds a Photoreal Alpine Scene (Water + PCG)](https://youtu.be/5ylAx-yAaBk) | 6 | [Builds an Animated Material](https://youtu.be/ZglR9ZndtZc) |
| 15 | [Builds a Procedural Terrain World (Landscape)](https://youtu.be/KxN_jKzGyCU) | 5 | [Builds a Pause Menu (UMG)](https://youtu.be/IxQuL_By5uk) |
| 14 | [Mounting on UE 5.8's Official MCP Server](https://youtu.be/XaCHZUSsFp8) | 4 | [Tunes Niagara VFX (Standard vs Stateless)](https://youtu.be/tjgaBGr2j-Y) |
| 13 | [Cleans Up a Spaghetti Blueprint](https://youtu.be/PNlYYRKdSog) | 3 | [Builds Enhanced Input Controls](https://youtu.be/C_8y6O_4lHs) |
| 12 | [Builds a Walled Town from One Spline](https://youtu.be/ILctPrTZjos) | 2 | [Places Actors from Natural Language](https://youtu.be/WgFBCEFLkQk) |
| 11 | [Assembles a Castle (Level Instances)](https://youtu.be/1BVWA_CBbTo) | 1 | [Automates Blueprint Editing](https://youtu.be/ktWlLYWJQks) |

**[▶ All episodes on YouTube](https://www.youtube.com/@Yooadev)**

## Get it

**[Get Claude Unreal on Fab — $99, one-time, full source included](https://www.fab.com/listings/4ee41200-fc67-480d-8857-4319ec5cdf72)**

Requirements: Unreal Engine 5.7 or 5.8, Python 3.10+ (auto-installed by `uv`), and an MCP client (Claude Code, Cursor, Cline, Windsurf, …).
Setup takes about two minutes — the plugin auto-configures `.mcp.json` for your project on first launch, so an agent started from your own terminal, VS Code, or Cursor gets identical editor control.

📖 **[Full installation guide →](https://echoulen.github.io/claude-unreal/docs/installation/)**

---

# Support

This repository is the **public support tracker** for Claude Unreal.

> The plugin ships via [Fab Marketplace](https://www.fab.com/listings/4ee41200-fc67-480d-8857-4319ec5cdf72) and its source is **not** hosted here.
> This repo exists so customers can file bug reports, request features, and ask questions without needing access to the private source repo.

## Before filing an issue

1. Check the [troubleshooting guide](https://echoulen.github.io/claude-unreal/docs/troubleshooting/) — most install / connection issues are covered.
2. Confirm your **Unreal Engine version** (5.7+) and the **ClaudeUnreal plugin version** (`Edit → Plugins → ClaudeUnreal`).
3. Capture the exact **tool call** that failed and the relevant **Output Log** excerpt — these are the two things we'll need first when reproducing.

## Filing an issue

**[→ File an issue](https://github.com/yO-oa/claude-unreal-support/issues/new/choose)** — pick the template that matches:

- **Bug report** — something broke or behaves unexpectedly.
- **Feature request** — propose a new tool / command or extend an existing one.
- **Question** — usage / setup / how-to.

## Scope

This repository **only** tracks support for the Claude Unreal plugin:

- ✅ Plugin install / launch / MCP connection issues
- ✅ Bugs in `cu` CLI / MCP tools
- ✅ Feature requests for new editor commands
- ✅ Docs gaps / inaccuracies

We can't help with:

- ❌ General Unreal Engine questions — see [Unreal Engine docs](https://docs.unrealengine.com/)
- ❌ Claude Code / Claude Desktop billing or account issues — see [Anthropic support](https://support.anthropic.com/)
- ❌ MCP protocol questions unrelated to this plugin — see [modelcontextprotocol.io](https://modelcontextprotocol.io/)

## Response time

Best-effort, typically within a few business days. Issues filed with complete repro steps and Output Log excerpts are picked up first.
