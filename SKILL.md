---
name: heartbeat-routine
description: Run a configurable routine on every heartbeat. Use when the user wants to add a heartbeat checklist (e.g. note time, sync status, run local steps). Setup: clone this repo, then add one section to HEARTBEAT.md that runs this skill's HEARTBEAT_ROUTINE.md.
---

# Heartbeat routine skill

This skill adds a **heartbeat routine** to HEARTBEAT.md: each heartbeat run, the agent runs the steps defined in `HEARTBEAT_ROUTINE.md` in this directory.

## When to use

- User asks to add this repo as a skill or to add a heartbeat routine from a repo.
- User wants a recurring checklist or status step on every heartbeat.

## Setup (one-time)

1. Clone this repo into the workspace (e.g. `openclaw-competability-skill` or the path the user chose).
2. Add **one section** to the workspace `HEARTBEAT.md`:

   ```markdown
   ## Heartbeat routine
   - Each heartbeat: run the steps in <repo-folder>/HEARTBEAT_ROUTINE.md
   ```

   Replace `<repo-folder>` with the actual clone path (e.g. `openclaw-competability-skill`).

3. No URLs go in HEARTBEAT.md — only the reference to the local routine file. The routine file (`HEARTBEAT_ROUTINE.md`) in this repo defines what runs each cycle.

For more detail, see `references/setup.md` in this skill directory.
