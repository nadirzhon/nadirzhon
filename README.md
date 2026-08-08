<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│    ███╗   ██╗ █████╗ ██████╗ ██╗██████╗                    │
│    ████╗  ██║██╔══██╗██╔══██╗██║██╔══██╗                   │
│    ██╔██╗ ██║███████║██║  ██║██║██████╔╝                   │
│    ██║╚██╗██║██╔══██║██║  ██║██║██╔══██╗                   │
│    ██║ ╚████║██║  ██║██████╔╝██║██║  ██║                   │
│    ╚═╝  ╚═══╝╚═╝  ╚═╝╚═════╝ ╚═╝╚═╝  ╚═╝                   │
│                                                             │
│         Security · Automation · Systems                     │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## About

Security researcher and automation engineer. I build tools at the intersection of **offensive security**, **AI automation**, and **systems engineering** — from low-level network analyzers to high-level orchestration pipelines.

Currently focused on:

- **Penetration testing tooling** — scanners, honeypots, traffic analyzers
- **AI-powered automation** — n8n workflows, LLM integrations, agent pipelines  
- **Algorithmic systems** — data collection, signal processing, execution engines
- **Infrastructure** — Docker, VPS hardening, VPN, monitoring stacks

---

## ⭐ Featured — [offsec-mcp](https://github.com/nadirzhon/offsec-mcp)

**Offensive-security tooling for AI agents, over the Model Context Protocol.**

[![CI](https://github.com/nadirzhon/offsec-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/nadirzhon/offsec-mcp/actions/workflows/ci.yml)
![MCP](https://img.shields.io/badge/MCP-server-8A63D2?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Give Claude, Cursor, or any MCP client the ability to run recon, pull CVE intelligence,
analyze JavaScript, and scan ports — **only against targets you're authorized to test.**
10 tools, an authorization-scope guard enforced in code, and a passing test suite.

> *"Enumerate subdomains of example.com, check which are live, and flag any running software with a critical CVE."* → the agent chains `recon_subdomains` → `http_probe` → `cve_search` for you.

```bash
uvx offsec-mcp   # run it instantly — no clone needed
```

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Security**

![Scapy](https://img.shields.io/badge/Scapy-000000?style=flat-square&logo=python&logoColor=white)
![Paramiko](https://img.shields.io/badge/Paramiko-3776AB?style=flat-square&logo=python&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-003E54?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**AI & Automation**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

---

## Security Portfolio

| Project | Description | Stack |
|---------|-------------|-------|
| [**offsec-mcp**](https://github.com/nadirzhon/offsec-mcp) ⭐ | MCP server exposing recon, CVE intel & scanning to AI agents — scope-guarded | Python, FastMCP |
| [custom-port-scanner](https://github.com/nadirzhon/custom-port-scanner) | Multithreaded TCP/UDP scanner with banner grabbing | Python, Socket |
| [osint-aggregator](https://github.com/nadirzhon/osint-aggregator) | Multi-source recon: Shodan, VirusTotal, WHOIS, DNS | Python, APIs |
| [web-vuln-scanner](https://github.com/nadirzhon/web-vuln-scanner) | OWASP Top 10 scanner: SQLi, XSS, headers | Python, BS4 |
| [ssh-honeypot](https://github.com/nadirzhon/ssh-honeypot) | SSH honeypot with geo-enrichment + Telegram alerts | Paramiko |
| [jwt-security-analyzer](https://github.com/nadirzhon/jwt-security-analyzer) | JWT audit: alg:none, weak secrets, forging | PyJWT |
| [phishing-url-detector](https://github.com/nadirzhon/phishing-url-detector) | ML-based phishing classifier, 96%+ accuracy | sklearn |
| [password-auditor](https://github.com/nadirzhon/password-auditor) | Hash cracker + policy analyzer + mutation engine | Python |
| [log-analyzer-siem](https://github.com/nadirzhon/log-analyzer-siem) | Mini-SIEM: SSH/nginx log analysis, anomaly detection | Python |
| [network-anomaly-detector](https://github.com/nadirzhon/network-anomaly-detector) | Real-time ARP spoof, port scan, DNS tunnel detection | Scapy |
| [ctf-writeups](https://github.com/nadirzhon/ctf-writeups) | HTB/THM writeups + reusable PoC tools | Markdown |

---

## Areas of Interest

```
Offensive Security    ████████████████░░░░  80%
Network Analysis      ███████████████░░░░░  75%
AI / ML Systems       █████████████░░░░░░░  65%
Backend Engineering   ████████████████████  90%
Infrastructure        ███████████████░░░░░  75%
```

---

## Live deployments

Not just tooling — production sites and systems, shipped and running.

| Project | What it is | Live |
|---------|-----------|------|
| [AUTONOMA studio](https://nadirzhon.github.io/) | Bilingual engineering-studio site — 3D hero, cost calculator, blog | [nadirzhon.github.io](https://nadirzhon.github.io/) |
| [Svetopis](https://nadirzhon.github.io/svetopis/) | Photographer portfolio: gallery, moments feed, online booking | [live](https://nadirzhon.github.io/svetopis/) |
| [Stroyflex](https://nadirzhon.github.io/stroyflex/) | Wholesale construction-chemistry catalogue, 617 SKU | [live](https://nadirzhon.github.io/stroyflex/) |

---

## Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nadirzhon&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nadirzhon&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

</div>

---

## Learning Path

- [ ] eJPT → OSCP
- [ ] HackTheBox Pro Labs
- [ ] Applied Cryptography
- [ ] Kernel-level security (eBPF, seccomp)
- [x] OWASP Top 10
- [x] Network traffic analysis
- [x] Docker / VPS hardening

---

<div align="center">

*Building tools. Breaking things. Fixing them.*

</div>
