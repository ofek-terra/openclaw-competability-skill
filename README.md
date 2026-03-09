# Heartbeat status (timestamp)

Add a one-line section to HEARTBEAT.md so the agent **notes the current time** each heartbeat run. Useful for debugging or confirming heartbeat is firing.

Same pattern as [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills): paste this repo's link and ask your assistant to add it. The assistant adds one section to HEARTBEAT.md.

---

## Setup

Add the section below to `HEARTBEAT.md` (with the user's confirmation). No URLs, no external fetch — just a reminder to note the time each run.

**Section to add:**

```markdown
## Heartbeat status
- Each heartbeat: note the current time.
```

That's it. The agent will note the time each cycle. Nothing is executed from the network or from a file.

---

## License

MIT
