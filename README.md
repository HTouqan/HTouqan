# Hashem Touqan

I build small local-first tools, the kind I want to use myself.

My day job is network and orchestration design at a regional carrier. I'm moving toward security and digital forensics. A lot of what I build here is hands-on practice with the operations and incident side, which the day job doesn't put in front of me.

CCNA 200-301, passed July 2026.

[LinkedIn](https://www.linkedin.com/in/hashemtouqan/) for the formal bio.

---

## Projects

### Yapperino

Local voice-to-text for Windows. Hold a key, talk, release. It's free and comes as a single .exe. The first launch downloads a speech model, and after that it works offline.

[Repo](https://github.com/HTouqan/yapperino) · [Download latest](https://github.com/HTouqan/yapperino/releases/latest)

### smeepo

My homelab runs 63 containers across two machines. The main box runs every service: media, the photo library, a mail relay, document workflows, scheduled automation, a local LLM, log and metric collection, and a custom AI agent. The older machine it replaced now only serves bulk storage over NFS. My MikroTik router is wired into the same automation over its API.

[Repo](https://github.com/HTouqan/smeepo) · [Architecture diagram](https://github.com/HTouqan/smeepo/blob/main/docs/architecture.svg)

### Forensics and network lab

A Velociraptor DFIR server for collecting evidence from endpoints, and containerlab topologies for routing practice. So far, OSPF has converged across three FRR nodes. BGP and firewall labs are staged next. Neither the DFIR server nor the labs are reachable from outside the LAN.

It runs on the homelab, so it has no repo of its own. The [smeepo README](https://github.com/HTouqan/smeepo#forensics-and-network-lab) covers it.

### bearing-analyzer

An automated rig for inspecting industrial bearings. A stepper motor on a TMC driver turns the bearing in front of a Basler vision camera. A Tkinter GUI drives the capture cycle, and a labelled pattern-analysis pipeline processes the images. About 1,400 lines of Python. I built it as the deliverable for a six-month engineering internship in Germany.

[Repo](https://github.com/HTouqan/bearing-analyzer)

### Personal MCP server

A FastMCP server that serves my CV, projects, voice, and preferences as searchable documents to LLM clients on any of my devices. It has a SQLite FTS5 backend and uses `streamable-http` transport behind Traefik, with bearer-token auth. It runs on the homelab. The repo stays private.

### EventForge

An event-management web app I've been building on and off. The backend does what I want. I'm rebuilding the frontend from a design I've settled on instead of patching it further. Private for now.

---

## How I work

- I plan before non-trivial changes. Small fixes I just ship.
- I check preconditions before I measure anything. An assumption is not a check.
- Anything that runs on its own clock (cron, watchers, polling webhooks) gets explicit approval first. The default is on demand.
- I keep updates short, but I don't go quiet.
- I would rather under-claim and be accurate than over-claim and get caught.

---

## On AI-assisted code

A lot of the code in these repos was generated with LLM help and then debugged into shape. I decide what each system does and how the parts fit together. I also decide what to keep and what to throw out, and I work out how to recover when something breaks. That is what I mean when I say I built something.

I do not claim to have hand-typed code I generated. I also do not claim to have built a system from scratch when I assembled it from existing components.

---

<sub>Last meaningful update: October 2026.</sub>
