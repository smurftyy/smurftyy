
```
$ finger xanes
Login:   xanes                            Name:     Oloyede Al-amin Oladapo
Shell:   /bin/zsh                         Location: Lagos, Nigeria
Uptime:  BSc CS @ UNILAG (200L)           Role:     Product Owner @ Blockprint
Focus:   backend · blockchain · infra     Seeking:  backend / devops internship
Split:   51% curious · 49% dev
```
 
```bash
# try my latest — a safety-first disk cleaner for dev machines
$ pipx install devklean && devklean scan
```
 
---
 
## `> cat ~/.config/whoami.yaml`
 
```yaml
name: "Oloyede Al-amin Oladapo (xanes)"
education: "BSc Computer Science — University of Lagos (200L)"
current_role: "Full-Stack Dev & Product Owner @ Blockprint"
 
building:
  - SoulNode     # decentralized identity layer on Cardano (CIP-68 soul-bound tokens)
  - PennyWise    # gamified finance tracker for Nigerian uni students
 
shipped:
  - devklean     # Python CLI that safely reclaims disk space — live on PyPI
  - ShieldPay    # fraud intelligence dashboard — Squad Hackathon 3.0
  - Cynaps       # offline WhatsApp → Obsidian organizer w/ local LLM (Gemma 3 via Ollama)
  - Whispr       # AI-powered Telegram reminder bot (live)
 
interests: [distributed systems, cardano infra, local AI, cryptography]
```
 
---
 
## `> ls ./projects --featured`
 
| Project | Stack | What it does |
|---|---|---|
| [**devklean**](https://github.com/smurftyy/devklean) [![PyPI](https://img.shields.io/pypi/v/devklean.svg)](https://pypi.org/project/devklean/) | Python · Click · Hatchling | CLI that reclaims disk space from dev artifacts (`node_modules`, `.venv`, caches). Trash-backed deletion, symlink protection, typed confirmation for large deletes, `doctor` metadata repair. CI on Linux/macOS/Windows, published via PyPI trusted publishing |
| [**ShieldPay**](https://github.com/smurftyy/ShieldPay) | Python · FastAPI · XGBoost | Fraud intelligence for SME merchants — cross-merchant behavioral fingerprinting, IsolationForest + XGBoost scoring ensemble, hybrid LLM/deterministic dispatcher, continuous retraining loop |
| [**Soul-Node**](https://github.com/smurftyy/Soul-Node) | Aiken · TypeScript · Mesh.js | Decentralized reputation infrastructure on Cardano — CIP-68 soul-bound identity tokens with on-chain anchors and mutable off-chain profiles, per-action attestation NFTs |
| [**Cynaps**](https://github.com/smurftyy/cynaps) | FastAPI · ChromaDB · Ollama | Fully offline WhatsApp → Obsidian academic organizer — classifies messages by course code with a local LLM (Gemma 3), writes interconnected Markdown notes. Zero cloud dependency |
 
<details>
<summary><code>> ls ./projects --all</code></summary>
<br>
| Project | Stack | What it does |
|---|---|---|
| [**cardano-treasury-explorer**](https://github.com/smurftyy/cardano-treasury-explorer) | TypeScript · Blockfrost | CLI dashboard + X-posting bot monitoring the Cardano treasury — balance tracking, governance data, automated updates |
| [**Whispr**](https://github.com/smurftyy/Whispr) | Node.js · Bull/Redis · MongoDB | AI-powered Telegram reminder bot — chrono-node NLP scheduling, queue-based notification system. Live at [@whis_tgbot](https://t.me/whis_tgbot) |
| [**x-hydra-tweet-engine**](https://github.com/smurftyy/x-hydra-tweet-engine) *(research)* | Go · Hydra L2 | Real-time Cardano Hydra Head state broadcasting to X — scoped to research after full node-sync blockers |
| [**Nexus**](https://github.com/smurftyy/Nexus) *(in progress)* | Electron · React · Zustand | No-code generative visual effects desktop app — wraps TouchDesigner via WebSocket bridge |
| [**XBCA**](https://github.com/smurftyy/XBCA) *(in progress)* | Next.js · Supabase · Gemini | Brand identity platform — AI-powered brand kit generator with PDF brand guide export |
 
</details>
---
 
## `> cat ./stack.json | jq`
 
**`.languages`**
 
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)
![Aiken](https://img.shields.io/badge/Aiken-FF6B35?style=for-the-badge&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
 
**`.infra`**
 
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
 
**`.blockchain`**
 
![Cardano](https://img.shields.io/badge/Cardano-0033AD?style=for-the-badge&logo=cardano&logoColor=white)
![Blockfrost](https://img.shields.io/badge/Blockfrost-1B77B0?style=for-the-badge&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)
 
---
 
## `> tail -f /var/log/currently.log`
 
```
[2026-06] shipped devklean v1.0.2 to PyPI — trusted publishing, CI across Linux/macOS/Windows
[2026-06] shipping SoulNode governance contracts on Cardano Preprod
[2026-06] backend infra for PennyWise — scoring engine, OCR pipeline, Supabase Edge Functions
[2026-06] deepening DevOps fundamentals — Docker, CI/CD, Linux administration
[2026-06] open to backend / DevOps internships (remote or Lagos-based)
```
 
---
 
## `> neofetch --socials`
 
```
xanes@github
─────────────────────────────
twitter/x    @Xanes_007
telegram     whispr → @whis_tgbot
email        xanesfkasmurftyy@gmail.com
```
 
<div align="center">
[![Twitter](https://img.shields.io/badge/@Xanes__007-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/Xanes_007)
[![Email](https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xanesfkasmurftyy@gmail.com)
 
</div>
---
 
<div align="center">
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=smurftyy&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=smurftyy&layout=compact&theme=dark&hide_border=true&langs_count=8)
 
![GitHub Streak](https://streak-stats.demolab.com?user=smurftyy&theme=dark&hide_border=true)
 
</div>
```
$ fortune
Constraints you didn't choose are just bugs with authority.
$ exit
```
 
