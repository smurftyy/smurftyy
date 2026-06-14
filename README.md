```
$ cat /etc/hostname
xanes

$ finger xanes
Login:    xanes                           Name:     Oloyede Al-amin Oladapo
Shell:    /bin/zsh                        Location: Lagos, Nigeria
Curious:  51%                             Dev:      49%
Focus:    backend systems · blockchain    Role:     Product Owner @ Blockprint
          distributed infra · AI         Seeking:  Backend / DevOps internship
```

---

```yaml
# whoami
name: "Xanes"
education: "BSc Computer Science — University of Lagos (200L)"
current_role: "Full-Stack Dev & Product Owner @ Blockprint"
building:
  - SoulNode        # decentralized identity layer on Cardano (CIP-68 soul-bound tokens)
  - PennyWise       # gamified finance tracker for Nigerian uni students
shipped:
  - ShieldPay       # fraud intelligence dashboard — Squad Hackathon 3.0
  - Cynaps          # offline WhatsApp → Obsidian organizer w/ local LLM (Gemma 3 via Ollama)
  - Whispr          # AI-powered Telegram reminder bot (live)
interests:
  - backend engineering & distributed systems
  - blockchain infrastructure (Cardano · Aiken · Hydra L2)
  - AI systems & local model deployment
  - cryptography & security
```

---

## `> ls ./projects/`

| Project | Stack | What it does |
|---|---|---|
| [**ShieldPay**](https://github.com/smurftyy/ShieldPay) | Python · XGBoost · IsolationForest · FastAPI | Fraud intelligence dashboard — cross-merchant behavioral fingerprinting, ML scoring ensemble (IsolationForest + XGBoost 0.40/0.60), hybrid LLM/deterministic agent dispatcher |
| [**Cynaps**](https://github.com/smurftyy/cynaps) | FastAPI · ChromaDB · Gemma 3 · whatsapp-web.js | Offline WhatsApp-to-Obsidian academic organizer — classifies messages by course code, runs fully local via Ollama, no cloud dependency |
| [**Whispr**](https://github.com/smurftyy/Whispr) | Node.js · Bull/Redis · Express · MongoDB | AI-powered Telegram bot with smart reminders, chrono-node NLP scheduling, and queue-based notification system |
| [**Soul-Node**](https://github.com/smurftyy/Soul-Node) | Aiken · TypeScript · Supabase · Mesh.js | Decentralized reputation infrastructure — CIP-68 soul-bound identity tokens on Cardano, per-action attestation NFTs |
| [**x-hydra-tweet-engine**](https://github.com/smurftyy/x-hydra-tweet-engine) *(research)* | Go · Cardano Node · Hydra L2 | Research prototype — exploring real-time Cardano Hydra Head state broadcasting to X/Twitter; scoped down from full deployment after discovering hard node-sync blockers |
| [**Nexus**](https://github.com/smurftyy/Nexus) *(in progress)* | Electron · TypeScript · React · Zustand | No-code generative visual effects desktop app — wraps TouchDesigner via WebSocket bridge |
| [**XBCA**](https://github.com/smurftyy/XBCA) *(in progress)* | Next.js · React · Supabase · Gemini API | Brand identity platform — AI-powered brand kit generator with PDF brand guide export |

---

## `> cat ./stack.json | jq '.languages'`

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white)
![Aiken](https://img.shields.io/badge/Aiken-FF6B35?style=flat-square&logoColor=white)

## `> cat ./stack.json | jq '.infra'`

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## `> cat ./stack.json | jq '.blockchain'`

![Cardano](https://img.shields.io/badge/Cardano-0033AD?style=flat-square&logo=cardano&logoColor=white)
![Blockfrost](https://img.shields.io/badge/Blockfrost-1B77B0?style=flat-square&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=flat-square&logo=ipfs&logoColor=white)

---

## `> cat /var/log/currently.log`

```
[2026-06] shipping SoulNode governance contracts on Cardano Preprod
[2026-06] backend infra for PennyWise — scoring engine, OCR pipeline, Supabase Edge Functions
[2026-06] picking up DevOps fundamentals — Docker, CI/CD, Linux administration
[2026-06] open to backend / DevOps internships (remote or Lagos-based)
```

---

## `> neofetch --socials`

```
xanes@github
─────────────────────────────
twitter/x    @Xanes_007
email        xanesfkasmurftyy@gmail.com
github       smurftyy
```

[![Twitter](https://img.shields.io/badge/@Xanes__007-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/Xanes_007)
[![Email](https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:xanesfkasmurftyy@gmail.com)

---

![Visitor Count](https://komarev.com/ghpvc/?username=smurftyy&style=flat-square&color=363636&label=visitors)
