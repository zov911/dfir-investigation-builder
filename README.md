# Investigation Scenario Builder: DFIR Artifact Triage Planner

**Live demo:** https://zov911.github.io/dfir-investigation-builder/

A vendor-neutral digital forensics and incident response (DFIR) planner. Pick a case type and the platforms in scope, and get a prioritized evidence-collection checklist. Each artifact lists where it lives, what it proves, how to parse it with free or open-source tools, and its MITRE ATT&CK techniques.

## Features

- **8 case types:** IP theft, financial fraud, ransomware & malware, business email compromise, insider threat, data breach, harassment / HR and missing person
- **42 artifacts across 5 platforms:** Windows 10/11 & Server, macOS, Linux/ESXi, iOS/Android, and cloud (Microsoft 365, Google Workspace)
- **Current artifacts (2026):** SRUM, Amcache, BAM, new Teams (LevelDB), cloud sync clients, RMM tool logs, rclone/MEGA exfil, Windows Recall, macOS Biome, on-device Google Timeline, generative-AI usage
- **Scenario-specific reasoning:** the same artifact gets a different priority and explanation depending on the case
- **MITRE ATT&CK mapping:** each technique links to attack.mitre.org
- **Analyst notes:** common pitfalls, e.g. ShimCache ≠ execution on Windows 10+, or Windows 11 reporting "Windows 10" in the registry
- **Workflow tools:** progress tracking saved in the browser, search/filter, case ID and examiner fields, shareable links, export to Markdown or CSV, print/PDF

## Tech

A single self-contained `index.html`: vanilla HTML, CSS and JavaScript with no build step and no dependencies (Google Fonts only). Works offline once loaded.

## Disclaimer

Reference guide only. Validate artifact locations and behavior against your forensic tooling, OS build, and your jurisdiction's legal and evidentiary requirements.

---

## Want a tool like this for your business?

I design and build interactive tools for B2B teams: calculators, configurators, triage planners and lead-generation tools.

**Reach out → [zov911.com](https://zov911.com)**

© 2026 zov911. All rights reserved.
