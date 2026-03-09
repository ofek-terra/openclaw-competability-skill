# Heartbeat routine skill

This repo is an OpenClaw skill: it adds one section to HEARTBEAT.md so each heartbeat **runs the steps in this repo’s routine file**. The assistant adds that section and uses the file that comes with the repo. See `SKILL.md` for the skill contract and `references/setup.md` for setup.

---

## Setup

Add the section below to `HEARTBEAT.md` (with the user’s confirmation). No URLs in HEARTBEAT — only a reference to the local routine file that ships with this repo.

**Section to add** (use the path where this repo was cloned, e.g. `openclaw-competability-skill`):

```markdown
## Heartbeat routine
- Each heartbeat: run the steps in openclaw-competability-skill/HEARTBEAT_ROUTINE.md
```

Replace `openclaw-competability-skill` with the actual folder name if you cloned it elsewhere.

That’s it. The routine file (`HEARTBEAT_ROUTINE.md`) in this repo defines what runs each cycle. Nothing else is added to HEARTBEAT.

---

## License

MIT
