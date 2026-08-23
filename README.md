# Hashem Touqan

I build small, useful, local-first tools. The kind I want to use myself.

By day I design network and orchestration solutions at a regional carrier. Where I'm headed is security and digital forensics, so a lot of what I build here is me getting hands-on with the operations, monitoring, and incident side that the day job doesn't put in front of me.

CCNA 200-301, passed July 2026.

[LinkedIn](https://www.linkedin.com/in/hashemtouqan/) for the formal bio.

---

## Projects

### Yapperino

Local voice-to-text for Windows. Hold a key, talk, release. Free, runs offline, single .exe.

[Repo](https://github.com/HTouqan/yapperino) · [Download latest](https://github.com/HTouqan/yapperino/releases/latest)

### smeepo

A 63-container personal homelab running across two machines. The main box carries everything that matters: photo library, media, mail relay, document workflows, scheduled automation, a local LLM, log and metric collection, and a custom AI agent. The older machine it replaced was demoted to bulk storage over NFS. My MikroTik router is wired into the same automation over its API.

[Repo](https://github.com/HTouqan/smeepo)

### Forensics and network lab

A Velociraptor DFIR server for endpoint evidence collection, and containerlab topologies for routing practice. Three FRR nodes with OSPF converged is where it stands, with BGP and firewall labs staged next. Neither the DFIR server nor the labs are reachable from outside the LAN.

Runs on the homelab, so there is no separate repo for it.

### bearing-analyzer

Automated industrial bearing inspection rig. Tkinter operator GUI, TMC stepper motor control, Basler vision camera capture, labelled pattern-analysis pipeline. About 1,400 lines of Python. Built as a six-month engineering internship deliverable in Germany.

[Repo](https://github.com/HTouqan/bearing-analyzer)

### Personal MCP server

FastMCP server that exposes my CV, projects, voice, and preferences as searchable documents to Claude and other LLM clients across my devices. SQLite FTS5 backend, `streamable-http` transport behind Traefik with bearer-token auth. Running on the homelab; the repo stays private.

### EventForge

An event-management web app I've been building on and off. The backend does what I want. The frontend is being rebuilt around a chosen design direction instead of patched further. Private for now.

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

<sub>Last meaningful update: August 2026.</sub>
