```
██████╗  █████╗ ███╗   ██╗██████╗  █████╗
██╔══██╗██╔══██╗████╗  ██║██╔══██╗██╔══██╗
██████╔╝███████║██╔██╗ ██║██║  ██║███████║
██╔═══╝ ██╔══██║██║╚██╗██║██║  ██║██╔══██║
██║     ██║  ██║██║ ╚████║██████╔╝██║  ██║
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝ ╚═╝  ╚═╝
```
> *"If you believe your AI stack is secure — I have a few questions."*
---
## 🐼 whoami
```bash
$ cat /etc/panda.conf
role:     Red Teamer & AI Security Researcher
focus:    Offensive tooling · TLS analysis · CVE intel · AI agent security
status:   Building CyberAI — AI-native pentest platform
belief:   "Completely safe" is a hypothesis, not a fact
```
I build tools that real pentesters use. From OOB detection and TLS fingerprinting
to CVE intelligence pipelines — and now wrapping all of it with AI.
---
## 🛠 Projects

### 👻 [phantom-grid](https://github.com/user70616E6461/phantom-grid)
> Free self-hosted Burp Collaborator alternative
Captures OOB DNS & HTTPS callbacks, stores interactions in SQLite,
reassembles exfiltrated payloads. No Burp Suite Pro required.
```
Stack:    JavaScript · SQLite · DNS · HTTPS
Use case: SSRF · blind XXE · OOB command injection
```
---
### 🧠 [phantom-intel](https://github.com/user70616E6461/phantom-intel)
> CVE Threat Intelligence Platform — NVD API 2.0
Pulls and enriches CVE data from NVD API 2.0. Fast path from
"target identified" to "known attack surface mapped".
```
Stack:    Python · NVD API 2.0
Use case: Recon automation · vuln mapping · pentest reporting
```
---
### 🔭 [reality-probe](https://github.com/user70616E6461/reality-probe)
> TLS Analyzer & XTLS Reality Configuration Tool
Probes domains for TLS 1.3 · HTTP/2 ALPN · X25519 · CDN presence.
Scores candidates (IDEAL → POOR) and generates ready configs for
Xray-core, sing-box, Mihomo, and NekoRay. 120+ built-in domains,
multi-source discovery, web dashboard with real-time progress.
```
Stack:    Python · Flask · cryptography
Use case: XTLS Reality SNI selection · proxy config generation
```
---
### 🛡️ [MAS-Sentry-Toolkit](https://github.com/user70616E6461/mas-sentry-toolkit) `[IN PROGRESS]`
> Multi-Agent System Security Auditing Framework
Professional research framework for auditing MAS security.
Introduces **ABFP** (Agent Behavioral Fingerprinting Protocol) —
a novel method for passive/active identification and anomaly detection
of agents via behavioral layer analysis: topic graphs, timing cadence,
payload signatures, and FSM state inference.
```
Stack:    Python · MQTT · AMQP · Docker
Use case: MAS/IoT/Robotic security auditing · rogue agent detection
          · impersonation detection · STRIDE threat modeling
```
---
### 🤖 [CyberAI](https://github.com/user70616E6461/CyberAI) `[IN PROGRESS]`
> AI-powered pentest platform
AI orchestration layer over the phantom stack. Automates recon,
correlates findings from phantom-intel and phantom-grid,
surfaces actionable attack paths. Multi-agent architecture —
built by someone who red-teams AI, not just with it.
```
Stack:    Python · LLM APIs · multi-agent orchestration
Status:   Active development
```
> The platform I'm most focused on right now.
---
## 🔴 Research
```
[ ACTIVE ]   phantom-grid — OOB detection & callback capture
[ ACTIVE ]   phantom-intel — CVE threat intelligence pipeline
[ ACTIVE ]   reality-probe — TLS analyzer & XTLS Reality config tool
[ BUILDING ] CyberAI — AI-native pentest platform
[ BUILDING ] MAS-Sentry-Toolkit — ABFP behavioral fingerprinting
[ STUDYING ] Prompt injection · agent hijacking · LLM attack surface analysis
```
---
## 📈 Activity
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=user70616E6461&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=e24b4a&icon_color=7F77DD&text_color=c9d1d9)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=user70616E6461&theme=dark&hide_border=true&background=0d1117&ring=e24b4a&fire=e24b4a&currStreakLabel=7F77DD)
---
## 🤝 Contact
Open an issue in any repo with `[CONTACT]` in the title.
---
<sub><code>70616E6461</code> → <code>panda</code> · Red panda. Red team.</sub>
