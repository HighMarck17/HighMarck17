```
┌────────────────────────────────────────────────────────────────────┐
│  @HighMarck17                                                      │
│  independent developer · backend, systems, data, automation        │
├────────────┬───────────────────────────────────────────────────────┤
│  building  │  backend services · APIs · automation · agent tooling │
│  context   │  IT consulting & data management in regulated medtech │
│  location  │  Italy                                                │
│  contact   │  highmarck@member.fsf.org                             │
└────────────┴───────────────────────────────────────────────────────┘
```

I build software end to end: backend services and APIs, desktop tools,
automation, and things that run on hardware, from requirements analysis to
deployment. My day job is IT consulting and data management in medtech, where
traceability, validation and data integrity are binding requirements, not good
practice. That constraint has shaped how I design everything else.

Most of my current work runs through agentic tooling. I use it daily to build,
and I build the tooling itself.

![Python](https://img.shields.io/badge/-Python-31495E?style=flat-square&logo=python&logoColor=white&labelColor=0D1117) ![C++](https://img.shields.io/badge/-C%2B%2B-31495E?style=flat-square&logo=cplusplus&logoColor=white&labelColor=0D1117) ![Rust](https://img.shields.io/badge/-Rust-31495E?style=flat-square&logo=rust&logoColor=white&labelColor=0D1117) ![Bash](https://img.shields.io/badge/-Bash-31495E?style=flat-square&logo=gnubash&logoColor=white&labelColor=0D1117) ![Linux](https://img.shields.io/badge/-Linux-3F5647?style=flat-square&logo=linux&logoColor=white&labelColor=0D1117) ![Docker](https://img.shields.io/badge/-Docker-3F5647?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117) ![Nginx](https://img.shields.io/badge/-Nginx-3F5647?style=flat-square&logo=nginx&logoColor=white&labelColor=0D1117) ![Django](https://img.shields.io/badge/-Django-3F5647?style=flat-square&logo=django&logoColor=white&labelColor=0D1117) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-54465B?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-54465B?style=flat-square&logo=raspberrypi&logoColor=white&labelColor=0D1117) ![Arduino](https://img.shields.io/badge/-Arduino-54465B?style=flat-square&logo=arduino&logoColor=white&labelColor=0D1117)

---

### `$ cat profile.yaml`

```yaml
building:   [backend services, REST APIs, desktop tools, automation, MCP servers]
languages:  [Python, C++, Rust, SQL, Bash, PowerShell, Java]
also:       [PHP, JavaScript, HTML/CSS, VBA]
web:        [Django, Django REST Framework, OpenAPI, pytest]
data:       [SQL Server, PostgreSQL, ETL, MES/ERP integration, Tableau, SAP BO WebI]
infra:      [Linux, Docker Compose, Nginx, Gunicorn, iptables/NAT, cloud]
hardware:   [Raspberry Pi, Arduino, ESP32, RFID/NFC, serial protocols]
agentic:    [Claude Code, OpenCode, MCP, subagents, hooks, skills]
local_llm:  [Ollama, LM Studio, Qwen, DeepSeek]
learning:   [multi-agent orchestration, agent security, applied cryptography]
```

---

### `$ tree work/`

```
work/
├── backend/
│   ├── services, REST APIs and OpenAPI schemas, system integrations
│   ├── web applications on Django and Django REST Framework
│   ├── desktop applications and internal tooling
│   ├── MCP servers: the integration layer between LLM agents and real systems
│   └── database design, SQL development, testing with pytest
├── automation/
│   ├── scripting in Python, Bash and PowerShell
│   ├── data extraction, scraping and processing pipelines
│   └── GUI automation and scheduled desktop tasks
├── data/
│   ├── integration across heterogeneous systems (MES / ERP)
│   ├── cleansing, validation, traceability, ETL
│   └── reporting and dashboards for decision support
├── hardware/
│   ├── C++ on Arduino and ESP32, low-level GPIO on Raspberry Pi
│   ├── IoT devices: door entry units, LAN camera links over encrypted
│   │   transport, environmental and operational monitoring
│   ├── RFID/NFC access control
│   └── serial and network protocols on constrained devices
├── security/
│   ├── applied cryptography in Rust: Signal-style constructions
│   │   (PQXDH, SPQR, Double Ratchet), post-quantum key exchange
│   ├── hardening public endpoints: rate limiting, CAPTCHA, honeypots,
│   │   disposable-domain filtering, brute-force protection on auth
│   ├── secrets outside the codebase, settings split per environment
│   ├── wireless and network auditing
│   └── trust boundaries and permissions in agentic systems
└── systems/
    ├── Linux configuration and deployment
    ├── containers and reverse proxies: Docker Compose, Nginx, Gunicorn
    └── routing, iptables, NAT, Ethernet bridging and connection sharing
        across Linux and Windows hosts
```

---

### `$ ls public/`

| repo | what it does | stack |
|:--|:--|:--|
| [keepass-kdbx-recover](https://github.com/HighMarck17/keepass-kdbx-recover) | Recover your own KeePass master password from what you remember. AES-KDF and Argon2 aware, CLI and Tkinter GUI. | Python |
| [animal-shelter-webapp](https://github.com/HighMarck17/animal-shelter-webapp) | Neutral Django template for an animal shelter: adoptable animals, contact form, FAQ, REST API. Ships with Docker and Nginx. | Python · Django |
| [rpi-net-bridge](https://github.com/HighMarck17/rpi-net-bridge) | Share a host's internet connection with any Raspberry Pi over Ethernet. bash/iptables on Linux, PowerShell/WinNAT on Windows. | Bash · PowerShell |

Most of my work is not public. Client code in regulated environments is not
mine to publish, and I keep unaudited cryptographic implementations private on
principle: a Signal-protocol implementation nobody has reviewed is a study
exercise, not something to hand people as if it were safe.

---

### `$ cat agentic.md`

```
◆  agent harnesses
   Claude Code and OpenCode as daily drivers: dynamic workflows, subagents,
   path-scoped rules, skills, MCP servers written as the integration layer
   between agents and real systems

◆  persistent context architecture
   a layered memory system I designed and built for coding agents: a small
   always-loaded core, warm and cold layers loaded on demand, path-scoped
   reflex rules, a curator subagent for session briefing and digest,
   hash-based ratification with drift detection on the core

◆  enforcement over prose
   memory files are context, not guarantees. Constraints that must always
   hold go into PreToolUse hooks, permission denials and pre-commit checks,
   not into instructions and good intentions

◆  model selection as a design decision
   started on local open-weight models (Ollama, LM Studio, Qwen, DeepSeek):
   cheap enough to learn the failure modes before paying for them. Frontier
   models do the hard passes now and cheaper tiers the mechanical fan-out,
   but local still earns its place where data must not leave the machine.
   Picking the tier is part of the architecture, not an afterthought

◇  multi-agent orchestration
   LangGraph and CrewAI agent graphs, with human-in-the-loop supervision
   treated as a design constraint. Newer ground than the rest of this list
```

◆ settled, in regular use  ·  ◇ in progress, not consolidated

<details>
<summary><code>$ cat coursework.txt</code></summary>

```
├── LangGraph Academy
├── CrewAI courses
├── Orchestrator Academy
├── advanced Claude Code: workflows, subagents, skills, hooks
├── agent design and orchestration patterns
└── security in agentic workflows: trust boundaries, tool permissions,
    prompt injection, least privilege for autonomous agents
```

Each of these ended up in something I was building at the time. The security
material is the part I take most seriously: autonomous agents with tool access
are a real attack surface.

</details>

---

### `$ cat contact`

`email   ` ▸ [highmarck@member.fsf.org](mailto:highmarck@member.fsf.org)  
`github  ` ▸ [github.com/HighMarck17](https://github.com/HighMarck17)  
`software` ▸ Free Software Foundation associate member
