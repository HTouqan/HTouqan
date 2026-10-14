# Proposed additions, not approved

Nothing in this file is on the profile README. Each line is something I noticed in your public repos that could go on the profile later. None of it goes into README.md unless you say yes to that line.

Tick the ones you want, strike the rest.

## smeepo (HTouqan/smeepo)

- [ ] Alert audit: a week of alerts was checked line by line, 7 of 44 turned out to be true, and the noisy checks were fixed.
- [ ] Backups: daily restic snapshots go to a local repository and to off-site object storage, and restores from both have been run.
- [ ] Verification script: one script runs 24 checks, covering the VPN tunnel, public routes, disk, remote access, and the command daemon, before anything counts as done.
- [ ] Incident write-ups: three short case studies, including the MikroTik DNS-NAT outage and the move to a second machine.
- [ ] Inbound path: public services reach the box only through a Cloudflare tunnel into Traefik, with no ports forwarded on the router.
- [ ] Observability: OpenObserve holds logs and metrics, fed by Vector and an OpenTelemetry collector.
- [ ] Lab detail: VPN migration labs are listed as staged, next to the BGP and firewall labs.
- [ ] Forensics roadmap: a forensics workstation under KVM for disk and memory analysis is on the smeepo roadmap.
- [ ] DFIR tooling: Velociraptor output is described as feeding Volatility and the Zimmerman tools.
- [ ] Hardware: a Ryzen 7 8845HS hub with 64 GB of RAM, and a MikroTik RB5009 on RouterOS 7.22.

## yapperino (HTouqan/yapperino)

- [ ] Current release: v0.3.0, dated 2026-07-03 in the changelog. It warns when the mic is muted instead of failing quietly.
- [ ] Model choice: four Whisper model sizes, from small.en to large-v3, picked from the tray window.
- [ ] Licence: MIT.

## bearing-analyzer (HTouqan/bearing-analyzer)

- [ ] Dates: the repo says it was built over 2023 and 2024.
- [ ] Public release: published in white-label form, with branding, captured data, and logs removed and the code otherwise unchanged.
- [ ] Licence: MIT.

## Hub-and-spoke links

- [ ] smeepo's footer links back with the text "Profile README". yapperino and bearing-analyzer use "github.com/HTouqan". Using the same text in all three would be tidier. That change would happen in those repos, not here.
