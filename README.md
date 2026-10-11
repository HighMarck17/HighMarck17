```
┌────────────────────────────────────────────────────────────────────┐
│  @HighMarck17                                                      │
│  backend · systems · data · security · agent tooling               │
├────────────┬───────────────────────────────────────────────────────┤
│  building  │  services · APIs · automation · IoT · agent tooling   │
│  context   │  production data in regulated medtech                 │
│  location  │  Italy                                                │
│  contact   │  highmarck@member.fsf.org                             │
└────────────┴───────────────────────────────────────────────────────┘
```

`// mente algoritmica` — security and privacy by design, enforcement over good intentions, and code that has to prove it works.

I build backend services and APIs, automation, IoT devices, and the tooling
that lets coding agents work against real systems. By day I look after
production data in a regulated medtech environment, where every record has to
stand up to an audit; that discipline of traceability and verification shapes
how I design everything else. Most of my development now runs through agentic
tooling, which I use daily and build myself.

![Python](https://img.shields.io/badge/-Python-31495E?style=flat-square&logo=python&logoColor=white&labelColor=0D1117) ![C++](https://img.shields.io/badge/-C%2B%2B-31495E?style=flat-square&logo=cplusplus&logoColor=white&labelColor=0D1117) ![Rust](https://img.shields.io/badge/-Rust-31495E?style=flat-square&logo=rust&logoColor=white&labelColor=0D1117) ![Bash](https://img.shields.io/badge/-Bash-31495E?style=flat-square&logo=gnubash&logoColor=white&labelColor=0D1117) ![Linux](https://img.shields.io/badge/-Linux-3F5647?style=flat-square&logo=linux&logoColor=white&labelColor=0D1117) ![Docker](https://img.shields.io/badge/-Docker-3F5647?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117) ![Nginx](https://img.shields.io/badge/-Nginx-3F5647?style=flat-square&logo=nginx&logoColor=white&labelColor=0D1117) ![Django](https://img.shields.io/badge/-Django-3F5647?style=flat-square&logo=django&logoColor=white&labelColor=0D1117) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-54465B?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-54465B?style=flat-square&logo=raspberrypi&logoColor=white&labelColor=0D1117) ![Arduino](https://img.shields.io/badge/-Arduino-54465B?style=flat-square&logo=arduino&logoColor=white&labelColor=0D1117)

---

### `$ cat stack.yaml`

```yaml
languages:  [Python, Rust, C++, SQL, Bash, PowerShell, Java]
backend:    [Django, Django REST Framework, OpenAPI, pytest]
data:       [SQL Server, PostgreSQL, ETL, MES/ERP integration, Tableau, SAP BO WebI]
infra:      [Linux, Docker Compose, Nginx, Gunicorn, GitHub Actions, iptables/NAT]
hardware:   [Raspberry Pi, Arduino, ESP32, RFID/NFC, sensors]
security:   [applied and post-quantum crypto in Rust, hardening, network auditing, CTF]
agentic:    [MCP servers, Claude Code, OpenCode, subagents, hooks, skills]
local_llm:  [Ollama, LM Studio, Qwen, DeepSeek]
practices:  [TDD with mutation testing, ADRs, docs-as-code in CI, threat modelling]
exploring:  [multi-agent orchestration, agent security]
```

---

### `$ tree work/`

```
work/
├── backend/
│   ├── services, REST APIs with OpenAPI contracts, system integrations
│   ├── web applications on Django and Django REST Framework
│   ├── MCP servers: the integration layer between LLM agents and real systems
│   └── database design, SQL, testing with pytest
├── automation/
│   ├── Python, Bash and PowerShell scripting
│   ├── extraction, scraping and processing pipelines
│   └── GUI automation and scheduled desktop tasks
├── data/
│   ├── integration across heterogeneous systems (MES / ERP)
│   ├── master data, quality rules, reconciliation, traceability, ETL
│   └── reporting and dashboards for operational decisions
├── hardware/
│   ├── C++ on Arduino and ESP32, GPIO on Raspberry Pi
│   ├── IoT devices: RFID/NFC access control, door entry units,
│   │   encrypted LAN camera links, environmental monitoring
│   └── serial and network protocols on constrained devices
├── security/
│   ├── applied cryptography in Rust: Signal-style constructions,
│   │   post-quantum key exchange
│   ├── hardening public endpoints: rate limiting, honeypots,
│   │   brute-force protection on auth
│   ├── offensive practice: CTF web challenges, recon, injection testing,
│   │   findings written up with remediation
│   ├── anonymity: Tor transport and onion services
│   └── trust boundaries and permissions in agentic systems
└── systems/
    ├── Linux configuration, hardening and deployment
    ├── Docker Compose, Nginx and Gunicorn behind TLS, GitHub Actions
    └── routing, iptables/NAT, Ethernet bridging across Linux and Windows hosts
```

Most of my work is not public: code written for an employer in a regulated
environment is not mine to publish, and unaudited cryptographic implementations
stay private on principle.

---

### `$ cat now.md`

```
building   ▸ home monitoring for fragile people on Raspberry Pi: on-device
             computer vision, local AI as a verification layer, no video
             recording, nothing leaves the house
           ▸ a post-quantum, peer-to-peer encrypted chat in Rust with no
             central server, private until it has been audited
exploring  ▸ multi-agent orchestration frameworks and the security of agents
             that hold real tool access
open to    ▸ consulting and collaboration on backend, data and security work
```

---

### `$ cat agentic.md`

```
◆  harnesses
   Claude Code and OpenCode as daily drivers: workflows, subagents,
   path-scoped rules, skills, MCP servers as the integration layer between
   agents and real systems

◆  persistent context
   a layered memory system for coding agents: a small always-loaded core,
   warm and cold layers on demand, a curator subagent for session briefing,
   hash-based ratification with drift detection on the core

◆  enforcement over prose
   memory files are context, not guarantees. Constraints that must always
   hold live in PreToolUse hooks, permission denials and pre-commit checks

◆  model selection
   local open-weight models where data must not leave the machine, frontier
   models for the hard passes, cheaper tiers for mechanical fan-out.
   Picking the tier is part of the architecture

◆  boundaries
   agents work on development projects outside regulated environments.
   Inside them, AI stays out of the critical path
```

---

### `$ cat contact`

`email ` ▸ [highmarck@member.fsf.org](mailto:highmarck@member.fsf.org)  
`github` ▸ [github.com/HighMarck17](https://github.com/HighMarck17)  
`fsf   ` ▸ Free Software Foundation associate member
