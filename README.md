# Hashem Touqan

Network automation and orchestration engineer at e& UAE. Based in Sharjah. Computer Engineering background (German Jordanian University, with an exchange semester at WHZ Zwickau in Germany), with prior hands-on Python and embedded work in Mannheim.

This page is my technical portfolio. The carrier work pays the bills; the personal infrastructure linked below is where the wrench-turning lives. LinkedIn keeps the formal version of my CV — this is the long-form, honest version with the actual technical depth.

[LinkedIn](https://www.linkedin.com/in/hashemtouqan/) · Sharjah, UAE · Open to EU opportunities

---

## At a glance

| | |
|---|---|
| **Current role** | Network Automation and Orchestration Engineer · e& UAE · since March 2025 |
| **Team** | Business Service Automation — design and rollout of enterprise connectivity products into the carrier's BSS/OSS orchestration stack |
| **Internal-accurate framing** | Solution Analyst — hybrid product-analyst / business-analyst function bridging product, vendors, and network engineering |
| **Education** | B.Sc. Computer Engineering (GJU, 2018–2024), exchange semester at WHZ Zwickau, Germany |
| **Languages** | Arabic (native), English (fluent), German (B1 — Goethe-Institut certificates held) |
| **Career direction** | Solution Analyst → Solution Designer → Solution Architect, with a personal track in self-hosted infrastructure and AI-agent tooling |

---

## Projects

| Project | What it is | Repo | Status |
|---|---|---|---|
| **smeepo** | A 28-container personal homelab: self-hosted media, photos, mail relay, document workflows, scheduled automation, a custom AI agent, and live integration with a MikroTik router over its API | [HTouqan/smeepo](https://github.com/HTouqan/smeepo) | Public README, code TBD |
| **bearing-analyzer** | Automated industrial bearing inspection rig — Tkinter operator GUI, TMC stepper motor control, Basler vision camera capture, labelled pattern-analysis pipeline. Originally built as my six-month engineering internship deliverable in Germany (~1,400 lines of Python) | [HTouqan/bearing-analyzer](https://github.com/HTouqan/bearing-analyzer) | Public, code released |
| **Personal MCP server** | Python FastMCP server exposing my CV, projects, voice, and preferences as searchable documents to Claude and other LLM clients across my devices. SQLite FTS5 backend, `streamable-http` transport behind Traefik with bearer-token auth | (private during development) | In active build |
| **EventForge v3** | Long-running personal project | (private) | Active |

---

## Now

What I am actively working on, as of this README's last update:

- **At work:** contributing to the design and onboarding of enterprise connectivity products into e&'s end-to-end service orchestration stack, including Cloud Connect Internet (CCI) over Microsoft Azure ExpressRoute and Internet Dedicated Access (IDA) automation flows.
- **Personal:** building the personal MCP server above; the corpus content is drafted, FastMCP scaffolding is next.
- **Learning:** completing the remaining courses of the Google Cybersecurity Professional Certificate, plus carrier-side material on MEF service definitions, MPLS-VPN service models, and the Nokia / Cisco orchestration stacks I touch at work.
- **Adjacent workstreams:** a focused photo-library cleanup of an inherited Samsung S9-era metadata mess on a multi-TB Immich library.

---

## Day job — e& UAE, Business Service Automation

I sit on a team that owns the design layer between product, vendor partners, and the engineers who run the production network. The job is taking a new or modified enterprise connectivity product and defining how it gets provisioned end-to-end — from the customer-facing CRM and order manager, down through the End-to-End Service Orchestrator (E2ESO), the Transport Domain Orchestrator (TDO), and the vendor-specific Network Management Systems.

Concretely: sitting in vendor and product-owner meetings, capturing architecture and limitations, writing them up as internal technical proposals, translating vendor API behaviour (Azure ExpressRoute, Nokia altiplano, Cisco controllers) into the parameters and workflow the orchestration team needs, and tracking the edge cases that should end up in the design rather than in production incidents.

**Honest framing:** the role is coordination and design, not coding. I have the engineering background to follow the technical content in detail; I am not writing the orchestration software myself. Career trajectory the team supports is Solution Analyst → Solution Designer → Solution Architect.

**Product portfolio I regularly touch:** CCI (Cloud Connect Internet) · IDA (Internet Dedicated Access) · GVPN L3 / IPconnect L3 · NaaS (the umbrella for MEF E-Line / EVC services) · TDO (Transport Domain Orchestrator).

<details>
<summary><strong>Vocabulary I work in</strong> (click to expand)</summary>

**Programme and ops:** BRD, TP (Technical Proposal), HLD / LLD, PPM ID, SPOC, CR, BSS transformation phases (cat A / B1 / B2 / C), Brownfield vs Greenfield, gold products, automation drop, feasibility check.

**Service and orchestration stack:** BSS, OSS, CRM, CBCM, OM (Order Manager), WFMS, E2ESO, TDO, NMS, NRM (eNRM, Granite resource inventory), CMDS, CGW, PMS, Concept Wave, vEDA, NSP (Nokia Service Platform), velocity templates, EDA (Ericsson Dynamic Activation), NFMP.

**Carrier networking:** EMIX, ExpressRoute, MSEE, ERD, MPLS, BGP, BFD, VRF, OSPF, jumbo frames, MEF, E-Line, EPL, EVPL, EVC, ENNI, UNI (UNI-C, UNI-N), OVC, CIR / EIR / CBS / EBS / PIR, 802.1Q C-Tag, 802.1ad Q-in-Q / S-Tag, All-to-One Bundling, Service Multiplexing, VPRN, VPLS, VLL, pCPE, uCPE, IPAM, IPVPN, SDWAN (viptela / Fortinet flavours), spoke SDP, hub-and-spoke, IPv4 / IPv6 dual stack, SBC, VQM, BNG, BRAS, RRT.

**Vendor and product:** Cisco controllers, Nokia altiplano (TL1, OLT, ONT, GPON), Microsoft Azure (ExpressRoute, Service Principals, MSEE), Ericsson NRM, Netcracker (typically authors TPs that the BSA team reviews), VSaaS, NVR / OTT NVR, UTM, MSS.

</details>

---

## Skills, honestly calibrated

Calibration scale used below: **Strong** = uses regularly and unblocked; **Working** = has shipped real things with it but reaches for docs often; **Familiar** = covered in coursework or a small project, recognisable but not load-bearing; **Curious** = read about it, has not shipped anything with it.

| Area | Level | Notes |
|---|---|---|
| Carrier service design (BSS/OSS, E2ESO/TDO, MEF, MPLS, BGP, BFD, VRF, Q-in-Q) | Working | Daily driver at e& |
| MikroTik RouterOS administration via API | Working | The homelab router is wired into my automation stack |
| Cisco IOS-style CLI, NetConf/RESTCONF, Nokia altiplano vocabulary | Familiar | CCNA material studied; certificate not yet held |
| Python (scripting, automation, real-time data) | Working | Internship + homelab + personal projects |
| Bash / shell | Working | The homelab automation backbone |
| Docker and Docker Compose, systemd, Postgres + pgvector, Traefik, reverse-proxy/TLS | Working (within homelab scope) | Daily |
| Google Cloud Platform IAM, Google Workspace admin, Security Command Center | Working | From a five-month security & compliance contributor stint at an AI startup before e& |
| Saudi cybersecurity framework structure (SAMA CSF, NCA ECC, CMA CSF) | Familiar | Read during the same engagement |
| Dart/Flutter, Kotlin, C/C++ | Familiar (reading level) | Coursework, plus several days reading a Flutter codebase end-to-end |
| Kubernetes, large-scale cloud architecture | Curious | Deliberately stayed on plain Docker Compose for the homelab so far |
| LLM-based agents, Model Context Protocol authoring | Working | Building my own MCP server; integrate Anthropic and OpenAI tooling regularly |
| Obsidian as primary personal knowledge base | Strong | ~150-file vault, daily driver |
| Confluence, Jira, Microsoft 365 | Working | Daily at e& |

**What I am explicitly not strong at:** production software engineering at scale, large-team release engineering, Kubernetes-grade infrastructure, deep security engineering, deep DBA work. I can talk about all of these; I should not be sold as a senior practitioner of any of them.

---

## How I work

- **Plan before large changes.** For non-trivial implementation tasks I align on a plan first, then execute. For small fixes, just do it.
- **Verify before measuring.** Before kicking off any time-bound or KPI-tracked activity, I run an explicit pre-flight pass to confirm preconditions are met. Assumption is not verification.
- **Audit recipients before sending into a long thread.** Once external parties are added to a thread, prior context becomes exposed; the cost of a re-check is small, the cost of a miss is large.
- **Ask before adding anything that runs on its own clock.** Cron jobs, watchers, webhook polls — all need explicit approval. On-demand by default.
- **Short over long.** Brief is good, silent is not. Skip the trailing summaries. No "Certainly!" openings.
- **Honest scope over impressive scope.** I would rather under-claim and be calibrated than over-claim and be exposed.

---

## On AI-assisted development

Worth stating directly because it shapes how to read this whole page:

A meaningful share of the scripts, configurations, and side-project code I work on is generated with LLM assistance and then debugged into shape. The decisions about what each system does, how the pieces fit together, what to keep, what to throw out, and how to recover when something breaks are mine. I think that is the honest contemporary version of "I built this", and I would rather state it plainly than imply otherwise.

What I do not do: claim to have hand-typed code I generated, or claim to have built systems from scratch that I assembled from off-the-shelf components and configuration.

---

## Contact

LinkedIn is the best channel for anything formal: <https://www.linkedin.com/in/hashemtouqan/>

---

<sub>Last meaningful update: May 2026. The vocabulary section, the project list, and the skills table are kept in sync with reality on a roughly monthly cadence.</sub>
