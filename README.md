# Hashem Touqan

Network Automation and Orchestration Engineer at e& UAE. Based in Sharjah. Computer Engineering background from German Jordanian University with an exchange semester at WHZ Zwickau in Germany.

This is the long version of my CV. LinkedIn has the formal one. The stuff below is what I actually spend nights and weekends on.

[LinkedIn](https://www.linkedin.com/in/hashemtouqan/) · Sharjah, UAE · Open to EU opportunities

---

## Quick facts

| | |
|---|---|
| **Role** | Network Automation and Orchestration Engineer, e& UAE, since March 2025 |
| **Team** | Business Service Automation. We design how new enterprise connectivity products get provisioned through the carrier's BSS/OSS stack. |
| **Internal title** | Solution Analyst. Hybrid product-analyst and business-analyst function. Sits between product, vendors, and the network engineers. |
| **Education** | B.Sc. Computer Engineering, GJU 2018-2024. Exchange semester at WHZ Zwickau, Germany. |
| **Languages** | Arabic (native), English (fluent), German (B1, Goethe-Institut) |
| **Direction** | Solution Analyst → Solution Designer → Solution Architect. Parallel personal track in self-hosting and AI tooling. |

---

## Projects

### smeepo

A 28-container personal homelab. Self-hosted media, photo library, mail relay, document workflows, scheduled automation, a custom AI agent, and live integration with my MikroTik router via its API. Daily-driver infrastructure that I built single-handed.

[HTouqan/smeepo](https://github.com/HTouqan/smeepo)

### Yapperino

Local voice-to-text app for Windows. Hold a key, talk, release. Your words paste into whatever app has focus. Free, runs offline, single .exe. Built and shipped in a working session so I and a few friends could stop paying for a SaaS subscription to do what Whisper does for free.

[HTouqan/yapperino](https://github.com/HTouqan/yapperino) · [Release v0.1.0](https://github.com/HTouqan/yapperino/releases/tag/v0.1.0)

### bearing-analyzer

Automated industrial bearing inspection rig from my six-month internship in Germany. Tkinter operator GUI, TMC stepper motor control, Basler vision camera capture, labelled pattern-analysis pipeline. About 1,400 lines of Python.

[HTouqan/bearing-analyzer](https://github.com/HTouqan/bearing-analyzer)

### Personal MCP server

FastMCP server that exposes my CV, projects, voice, and preferences as searchable documents to Claude and other LLM clients across my devices. SQLite FTS5 backend, `streamable-http` transport behind Traefik with bearer-token auth. Live for my own use, repo private during development.

### EventForge v3

Long-running personal project. Private.

---

## What I am doing now

- **Work:** designing and onboarding enterprise connectivity products into e&'s end-to-end service orchestration stack. Cloud Connect Internet over Microsoft Azure ExpressRoute, Internet Dedicated Access automation flows.
- **Personal:** shipping the MCP server above. Corpus drafted. FastMCP scaffolding next.
- **Learning:** finishing the Google Cybersecurity Professional Certificate. Reading carrier material on MEF service definitions, MPLS-VPN models, and the Nokia and Cisco orchestration stacks I touch at work.
- **Side project:** cleaning up a multi-terabyte Immich library with Samsung S9-era metadata problems.

---

## Day job at e& UAE

I sit on a team that owns the design layer between product, vendor partners, and the engineers who run the production network. The job is taking a new or modified enterprise connectivity product and defining how it gets provisioned end-to-end. From the customer-facing CRM and order manager, down through the End-to-End Service Orchestrator (E2ESO), the Transport Domain Orchestrator (TDO), and the vendor-specific Network Management Systems.

In practice: vendor and product-owner meetings, capturing architecture and limitations, writing internal technical proposals, translating vendor API behaviour (Azure ExpressRoute, Nokia altiplano, Cisco controllers) into the parameters and workflow the orchestration team needs, and tracking edge cases that should end up in the design rather than as production incidents.

The role is coordination and design, not software engineering. I have the engineering background to follow the content in detail. I am not writing the orchestration code itself. The team supports a Solution Analyst to Solution Designer to Solution Architect path.

**Products I touch regularly:** CCI (Cloud Connect Internet), IDA (Internet Dedicated Access), GVPN L3 and IPconnect L3, NaaS (MEF E-Line and EVC services), TDO.

<details>
<summary><strong>Vocabulary I work in</strong> (click to expand)</summary>

**Programme and ops:** BRD, TP (Technical Proposal), HLD / LLD, PPM ID, SPOC, CR, BSS transformation phases (cat A / B1 / B2 / C), Brownfield vs Greenfield, gold products, automation drop, feasibility check.

**Service and orchestration stack:** BSS, OSS, CRM, CBCM, OM (Order Manager), WFMS, E2ESO, TDO, NMS, NRM (eNRM, Granite resource inventory), CMDS, CGW, PMS, Concept Wave, vEDA, NSP (Nokia Service Platform), velocity templates, EDA (Ericsson Dynamic Activation), NFMP.

**Carrier networking:** EMIX, ExpressRoute, MSEE, ERD, MPLS, BGP, BFD, VRF, OSPF, jumbo frames, MEF, E-Line, EPL, EVPL, EVC, ENNI, UNI (UNI-C, UNI-N), OVC, CIR / EIR / CBS / EBS / PIR, 802.1Q C-Tag, 802.1ad Q-in-Q / S-Tag, All-to-One Bundling, Service Multiplexing, VPRN, VPLS, VLL, pCPE, uCPE, IPAM, IPVPN, SDWAN (viptela / Fortinet flavours), spoke SDP, hub-and-spoke, IPv4 / IPv6 dual stack, SBC, VQM, BNG, BRAS, RRT.

**Vendor and product:** Cisco controllers, Nokia altiplano (TL1, OLT, ONT, GPON), Microsoft Azure (ExpressRoute, Service Principals, MSEE), Ericsson NRM, Netcracker (typically authors TPs that the BSA team reviews), VSaaS, NVR / OTT NVR, UTM, MSS.

</details>

---

## Skills, calibrated

Scale: **Strong** = uses regularly, unblocked. **Working** = has shipped real things with it, reaches for docs often. **Familiar** = covered in coursework or a small project, recognisable but not load-bearing. **Curious** = read about it, has not shipped anything with it.

| Area | Level | Notes |
|---|---|---|
| Carrier service design (BSS/OSS, E2ESO/TDO, MEF, MPLS, BGP, BFD, VRF, Q-in-Q) | Working | Daily driver at e& |
| MikroTik RouterOS via API | Working | The homelab router runs my automation stack |
| Cisco IOS-style CLI, NetConf/RESTCONF, Nokia altiplano vocab | Familiar | CCNA material studied, certificate not yet held |
| Python (scripting, automation, real-time data) | Working | Internship, homelab, personal projects |
| Bash / shell | Working | The homelab automation backbone |
| Docker, Docker Compose, systemd, Postgres + pgvector, Traefik, reverse-proxy/TLS | Working (homelab scope) | Daily |
| Google Cloud Platform IAM, Google Workspace admin, Security Command Center | Working | From a five-month security and compliance stint at an AI startup before e& |
| Saudi cybersecurity frameworks (SAMA CSF, NCA ECC, CMA CSF) | Familiar | Read during the same engagement |
| Dart/Flutter, Kotlin, C/C++ | Familiar (reading level) | Coursework, plus reading a Flutter codebase end-to-end |
| Kubernetes, large-scale cloud architecture | Curious | Deliberately stayed on plain Docker Compose for the homelab so far |
| LLM agents, Model Context Protocol authoring | Working | Building my own MCP server. Integrate Anthropic and OpenAI tooling regularly |
| Obsidian as primary personal knowledge base | Strong | ~150-file vault, daily driver |
| Confluence, Jira, Microsoft 365 | Working | Daily at e& |

**What I am explicitly not strong at:** production software engineering at scale, large-team release engineering, Kubernetes-grade infrastructure, deep security engineering, deep DBA work. I can talk about any of these. I should not be sold as a senior practitioner of any of them.

---

## How I work

- Plan before non-trivial changes. Small fixes I just ship.
- Verify preconditions before measuring anything. Assumption is not verification.
- Check the recipient list before sending into a long email thread. Cheap pre-flight.
- Anything that runs on its own clock (cron, watchers, polling webhooks) gets explicit approval first. On-demand by default.
- Brief is good. Silent is not. Skip the trailing summary if the diff already speaks.
- I would rather under-claim and be accurate than over-claim and get caught.

---

## On AI-assisted code

A lot of the scripts, configs, and side-project code on this page was generated with LLM help and then debugged into shape. The decisions about what each system does, how it fits together, what to keep, what to throw out, and how to recover when something breaks are mine. That is the honest version of "I built this".

I do not claim to hand-type code I generated, or to have built systems from scratch when I assembled them from existing components.

---

## Contact

LinkedIn for anything formal: <https://www.linkedin.com/in/hashemtouqan/>

---

<sub>Last meaningful update: May 2026.</sub>
