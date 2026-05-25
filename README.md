# Hashem Touqan

I build small, useful, local-first tools. The kind I want to use myself.

[LinkedIn](https://www.linkedin.com/in/hashemtouqan/) for the formal bio.

---

## Projects

### Yapperino

Local voice-to-text for Windows. Hold a key, talk, release. Free, runs offline, single .exe.

[Repo](https://github.com/HTouqan/yapperino) · [Download latest](https://github.com/HTouqan/yapperino/releases/latest)

### smeepo

A 28-container personal homelab. Self-hosted media, photo library, mail relay, document workflows, scheduled automation, a custom AI agent, and live integration with my MikroTik router via its API.

[Repo](https://github.com/HTouqan/smeepo)

### bearing-analyzer

Automated industrial bearing inspection rig. Tkinter operator GUI, TMC stepper motor control, Basler vision camera capture, labelled pattern-analysis pipeline. About 1,400 lines of Python. Built as a six-month engineering internship deliverable in Germany.

[Repo](https://github.com/HTouqan/bearing-analyzer)

### Personal MCP server

FastMCP server that exposes my CV, projects, voice, and preferences as searchable documents to Claude and other LLM clients across my devices. SQLite FTS5 backend, `streamable-http` transport behind Traefik with bearer-token auth. Private during development.

### EventForge v3

Long-running personal project. Private.

---

## How I work

- Plan before non-trivial changes. Small fixes I just ship.
- Verify preconditions before measuring anything. Assumption is not verification.
- Anything that runs on its own clock (cron, watchers, polling webhooks) gets explicit approval first. On-demand by default.
- Brief is good. Silent is not.
- I would rather under-claim and be accurate than over-claim and get caught.

---

## On AI-assisted code

A lot of the code in these repos was generated with LLM help and then debugged into shape. The decisions about what each system does, how it fits together, what to keep, what to throw out, and how to recover when something breaks are mine. That is the honest version of "I built this".

I do not claim to hand-type code I generated, or to have built systems from scratch when I assembled them from existing components.

---

<sub>Last meaningful update: May 2026.</sub>
