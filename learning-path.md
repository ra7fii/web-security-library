# Learning path

Four stages, from fundamentals to your first valid report. Each topic pairs **something to read** with **something to practise**. Everything in the *Practise* column is free.

> Practise only on labs, CTFs and in-scope bug bounty targets. Never test a system without permission.

## Stage 1: Foundations

Goal: understand how the web works and get comfortable with an intercepting proxy.

| Topic | Read | Practise |
|---|---|---|
| HTTP, cookies, sessions | *The Tangled Web* ch. 1–3 | [Web Security Academy](https://portswigger.net/web-security): set up Burp Suite Community |
| Same-origin policy, CORS | *The Tangled Web* ch. 9 and 16 | Academy: CORS labs |
| How testing is structured | [WSTG](docs/testing-guide/OWASP-WSTG-v4.x-2023.pdf) §1–3 | Install [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) locally |
| The risk landscape | [OWASP Top 10](https://owasp.org/Top10/) | Juice Shop 1–2 star challenges |

## Stage 2: Core vulnerability classes

Goal: find and exploit each class by hand, without scanners.

| Topic | Read | Practise |
|---|---|---|
| XSS | *Bug Bounty Bootcamp* ch. 6 · [XSS cheat sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) | Academy: XSS (all apprentice labs) |
| SQL injection | *Bug Bounty Bootcamp* ch. 11 · WSTG `WSTG-INPV-05` | Academy: SQL injection · [DVWA](https://github.com/digininja/DVWA) |
| Access control and IDOR | *Bug Bounty Bootcamp* ch. 10 | Academy: access control |
| CSRF, clickjacking | *Bug Bounty Bootcamp* ch. 8–9 | Academy: CSRF, clickjacking |
| SSRF | *Bug Bounty Bootcamp* ch. 13 | Academy: SSRF |
| Authentication | WSTG §4.4 | Academy: authentication |

## Stage 3: APIs and modern apps

Goal: test the APIs behind mobile and single-page apps.

| Topic | Read | Practise |
|---|---|---|
| API risk model | [API Security Top 10](docs/api-security/OWASP-API-Security-Top-10-2019.pdf) and the [2023 edition](https://owasp.org/API-Security/editions/2023/en/0x00-header/) | Set up [crAPI](https://github.com/OWASP/crAPI) |
| API discovery and BOLA | *Hacking APIs* ch. 6–10 | crAPI challenges |
| GraphQL | *Hacking APIs* ch. 14 | Academy: GraphQL API vulnerabilities |
| Business logic | WSTG §4.10 | Academy: business logic |
| Knowing what "secure" looks like | [ASVS](docs/verification-standard/OWASP-ASVS-5.0.0.pdf) | Compare a Juice Shop feature against the matching ASVS section |

## Stage 4: Bug bounty in practice

Goal: pick a program, find something real and write a report that gets triaged.

| Topic | Read | Practise |
|---|---|---|
| Methodology | [zseano's methodology](https://www.bugbountyhunter.com/methodology/) · [The Bug Hunter's Methodology](https://github.com/jhaddix/tbhm) | [Hacker101 CTF](https://ctf.hacker101.com) (earns private program invites) |
| Recon and automation | *Bug Bounty Playbook* | Map one wide-scope program's assets end to end |
| Learning from others | *Real-World Bug Hunting* | Read 5 reports a day on [Hacktivity](https://hackerone.com/hacktivity) |
| Reporting | *Bug Bounty Bootcamp* ch. 2 · [OWASP Cheat Sheets](https://cheatsheetseries.owasp.org) for fix advice | Submit to a program with a clear scope and fast response times |

Chapter numbers refer to the current editions and may differ slightly between printings.
