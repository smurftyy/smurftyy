
---

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
  - SoulNode    # decentralized identity layer on Cardano (CIP-68 soul-bound tokens)
  - PennyWise   # gamified finance tracker for Nigerian uni students
shipped:
  - ShieldPay   # fraud intelligence dashboard — Squad Hackathon 3.0
  - Cynaps       # offline WhatsApp → Obsidian organizer w/ local LLM (Gemma 3 via Ollama)
  - Whispr       # AI-powered Telegram reminder bot (live)
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
| [**x-hydra-tweet-engine**](https://github.com/smurftyy/x-hydra-tweet-engine) *(research)* | Go · Cardano Node · Hydra L2 | Research prototype — real-time Cardano Hydra Head state broadcasting to X/Twitter; scoped after hitting full node-sync blockers |
| [**Nexus**](https://github.com/smurftyy/Nexus) *(in progress)* | Electron · TypeScript · React · Zustand | No-code generative visual effects desktop app — wraps TouchDesigner via WebSocket bridge |
| [**XBCA**](https://github.com/smurftyy/XBCA) *(in progress)* | Next.js · React · Supabase · Gemini API | Brand identity platform — AI-powered brand kit generator with PDF brand guide export |

---

## `> cat ./stack.json | jq '.languages'`

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)
![Aiken](https://img.shields.io/badge/Aiken-FF6B35?style=for-the-badge&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

## `> cat ./stack.json | jq '.infra'`

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## `> cat ./stack.json | jq '.blockchain'`

![Cardano](https://img.shields.io/badge/Cardano-0033AD?style=for-the-badge&logo=cardano&logoColor=white)
![Blockfrost](https://img.shields.io/badge/Blockfrost-1B77B0?style=for-the-badge&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)

---

## `> cat /var/log/currently.log`

```
[2026-06] shipping SoulNode governance contracts on Cardano Preprod
[2026-06] backend infra for PennyWise — scoring engine, OCR pipeline, Supabase Edge Functions
[2026-06] picking up DevOps fundamentals — Docker, CI/CD, Linux administration
[2026-06] open to backend / DevOps internships (remote or Lagos-based)
```

---

## `> htop --stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=smurftyy&show_icons=true&theme=dark&bg_color=0d1117&title_color=3ECF8E&icon_color=3ECF8E&text_color=c9d1d9&border_color=30363d&include_all_commits=true&count_private=true&hide_border=false" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smurftyy&layout=compact&theme=dark&bg_color=0d1117&title_color=3ECF8E&text_color=c9d1d9&border_color=30363d&hide_border=false&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=smurftyy&theme=dark&background=0d1117&ring=3ECF8E&fire=3ECF8E&currStreakLabel=3ECF8E&sideLabels=c9d1d9&dates=8b949e&border=30363d" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=smurftyy&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=6" />

</div>

---

## `> neofetch --socials`

```
xanes@github
─────────────────────────────
twitter/x    @Xanes_007
email        xanesfkasmurftyy@gmail.com
github       smurftyy
```

<div align="center">

[![Twitter](https://img.shields.io/badge/@Xanes__007-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/Xanes_007)
[![Email](https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xanesfkasmurftyy@gmail.com)

</div>

---

<div align="center">

---

## `> cat ./github-stats.json`

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=smurftyy&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=smurftyy&layout=compact&theme=dark&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=smurftyy&theme=dark&hide_border=true)


![Visitor Count](https://komarev.com/ghpvc/?username=smurftyy&style=for-the-badge&color=3ECF8E&label=VISITORS)

</div>
