<div align="center">

# Web Security Library

**A curated, legally redistributable library for web application security and bug bounty hunting.**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](LICENSE)
[![OWASP](https://img.shields.io/badge/source-OWASP-000000.svg)](https://owasp.org)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

Every file hosted in this repository is published under an open license that allows redistribution. Commercial books are **listed and linked, never hosted**: buy them from the publisher or author so the people who write them keep writing.

## Contents

- [Library (hosted here)](#library-hosted-here)
- [Free resources (linked)](#free-resources-linked)
- [Reading list (commercial books)](reading-list.md)
- [Learning path](learning-path.md)
- [Repository layout](#repository-layout)
- [Contributing](#contributing)
- [License and attribution](#license-and-attribution)

## Library (hosted here)

| Document | Version | What it is for | File |
|---|---|---|---|
| OWASP Web Security Testing Guide (WSTG) | 4.x (2023-09-28) | The reference methodology for testing web apps, organised by test case ID (`WSTG-INPV-05` and so on). | [PDF](docs/testing-guide/OWASP-WSTG-v4.x-2023.pdf) |
| OWASP Application Security Verification Standard (ASVS) | 5.0.0 (2025) | A checklist of security requirements; useful for knowing what "secure" should look like before you test. | [PDF](docs/verification-standard/OWASP-ASVS-5.0.0.pdf) |
| OWASP API Security Top 10 | 2019 | The classic API risk list (BOLA, broken auth, mass assignment and more). | [PDF](docs/api-security/OWASP-API-Security-Top-10-2019.pdf) |

> The **2023** edition of the API Security Top 10 is published as a website only; read it at [owasp.org/API-Security](https://owasp.org/API-Security/editions/2023/en/0x00-header/).

## Free resources (linked)

These are free to read but are not re-hosted here, either because they are websites or because their terms do not clearly allow redistribution.

| Resource | By | Why it is worth your time |
|---|---|---|
| [Web Security Academy](https://portswigger.net/web-security) | PortSwigger | Free, hands-on labs for every major vulnerability class. Written by the team behind *The Web Application Hacker's Handbook*. |
| [XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) | PortSwigger | Interactive, filterable list of XSS vectors by browser and context. |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org) | OWASP | Concise defensive guidance per topic; great for writing fix recommendations in reports. |
| [OWASP Top 10](https://owasp.org/Top10/) | OWASP | The most widely cited list of web application risks. |
| [zseano's methodology](https://www.bugbountyhunter.com/methodology/) | zseano | A practical, beginner-friendly approach to choosing targets and finding bugs. Free download from the author. |
| [The Bug Hunter's Methodology](https://github.com/jhaddix/tbhm) | Jason Haddix | Recon and testing methodology from one of the best-known hunters. |
| [Hacker101](https://www.hacker101.com) | HackerOne | Free video lessons plus a [CTF](https://ctf.hacker101.com) that earns private program invites. |
| [Bugcrowd University](https://www.bugcrowd.com/hackers/bugcrowd-university/) | Bugcrowd | Free training modules on methodology and reporting. |
| [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) | Community | Payload and bypass reference for every vulnerability class. |
| [HackTricks](https://book.hacktricks.wiki) | Community | Huge, searchable wiki of techniques. |
| [HackerOne Hacktivity](https://hackerone.com/hacktivity) | HackerOne | Thousands of disclosed real-world reports. Read them daily. |

## Reading list

The best commercial books on the subject, with a short summary, who each one is for and where to buy it: **[reading-list.md](reading-list.md)**.

## Learning path

A four-stage path from fundamentals to your first valid report, pairing each topic with a book chapter and a free lab: **[learning-path.md](learning-path.md)**.

## Repository layout

```
.
├── docs/
│   ├── testing-guide/          OWASP WSTG
│   ├── verification-standard/  OWASP ASVS
│   └── api-security/           OWASP API Security Top 10
├── reading-list.md             Commercial books (links only)
├── learning-path.md            Study plan with labs
├── CONTRIBUTING.md
└── LICENSE                     CC BY-SA 4.0
```

## Contributing

Suggestions are welcome. The one hard rule: **only add files whose license explicitly allows redistribution**, and link to everything else. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License and attribution

The OWASP documents in `docs/` are © the OWASP Foundation and their respective contributors, and are redistributed unmodified under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license. Original sources:

- WSTG: [github.com/OWASP/wstg](https://github.com/OWASP/wstg/releases/tag/20230928)
- ASVS: [github.com/OWASP/ASVS](https://github.com/OWASP/ASVS/releases/tag/v5.0.0_release)
- API Security Top 10: [github.com/OWASP/API-Security](https://github.com/OWASP/API-Security)

The README, reading list and learning path are also released under CC BY-SA 4.0. This project is not affiliated with or endorsed by OWASP or any publisher listed here.

> **Legal use only.** Test only systems you own or are explicitly authorised to test, and follow each bug bounty program's scope and rules.
