<!-- ══════════════════════════════════════════════════════════════════════════════
     ~/.francisrc — GitHub Profile README
     Theme: Pegasuz Panel × Neon Fire
     Palette: ff5f00 · ff8700 · ffaf00 · ffd700 · 5fffff · 87ff00 · ff0000
     ══════════════════════════════════════════════════════════════════════════════ -->

<!-- ── HEADER: custom animated SVG banner ─────────────────────────────────── -->

<a href="https://github.com/FrancisElegante">
  <img src="./assets/banner.svg" alt="franciselegante — backend engineer · systems operator · multi-tenant saas" width="100%" />
</a>

<!-- ── STATUS BAR (systemctl-style) ───────────────────────────────────────── -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=500&color=FF8700&center=true&vCenter=true&width=760&height=50&lines=francis%40server%3A~%24+systemctl+status+francis;%E2%97%8F+francis.service+-+backend+engineer;+++Active%3A+active+(running);+++Memory%3A+unlimited+%E2%80%A2+CPU%3A+8%2F8+cores;+++Tasks%3A+5+deployments+%E2%80%A2+11+tenants+live" />

<br/>

<img src="https://img.shields.io/badge/●_ACTIVE-ff5f00?style=flat-square&labelColor=0a0a0a&logoColor=white" />
<img src="https://img.shields.io/badge/UPTIME_99.97%25-ff8700?style=flat-square&labelColor=0a0a0a" />
<img src="https://img.shields.io/badge/LOCALE_es__AR.UTF--8-ffaf00?style=flat-square&labelColor=0a0a0a" />
<img src="https://img.shields.io/badge/TZ_UTC--3-ffd700?style=flat-square&labelColor=0a0a0a" />
<img src="https://img.shields.io/badge/ROLE_BACKEND-5fffff?style=flat-square&labelColor=0a0a0a" />
<img src="https://img.shields.io/badge/MODE_PROD-87ff00?style=flat-square&labelColor=0a0a0a" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── WHOAMI ─────────────────────────────────────────────────────────────── -->

## 🔥 `whoami`

```ini
# /etc/francisrc.conf
user            = franciselegante
uid             = 1000
role            = "Backend Engineer & Systems Architect"
domain          = "multi-tenant SaaS · AI autonomy · security labs"
location        = Remote
timezone        = America/Argentina/Buenos_Aires
shell           = /bin/zsh
editor          = nvim
kernel          = Linux
coffee          = "black, no sugar"

[runtime]
node_version    = 20.x
python_version  = 3.12
mysql_version   = 8.0
pm2_apps        = pegasuz-api, pegasuz-staging

[motto]
manifesto       = "Build systems that outlast the teams that create them."
anti_motto      = "It works on my machine is not a deployment strategy."
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── DEPLOYMENTS: systemctl list-units ──────────────────────────────────── -->

## ⚡ `systemctl list-units --type=project`

```
  UNIT                    LOAD      ACTIVE    SUB        DESCRIPTION
─ ──────────────────────  ────────  ────────  ─────────  ─────────────────────────────────────────
● pegasuz.service         loaded    active    running    Multi-tenant SaaS Core (11 tenants)
● pegasuz-brain.service   loaded    active    running    Autonomous AI orchestration (private)
● wifilab.service         loaded    active    running    WiFi audit lab · pentesting commander
● cansat-messi.service    loaded    active    deployed   Satellite prototype (team MESSI)
● lampone.service         loaded    active    deployed   Terminal-noir personal portfolio
```

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🔴 `pegasuz.service`

<img src="https://img.shields.io/badge/PRODUCTION-ff5f00?style=for-the-badge&labelColor=0a0a0a" /> <img src="https://img.shields.io/badge/11_tenants-5fffff?style=for-the-badge&labelColor=0a0a0a" />

**Multi-tenant SaaS platform** · Production core serving real businesses. Database-per-tenant isolation, JWT cross-validation, feature flags per client, 18 Prisma migrations, zero cross-tenant leaks.

```
Stack:    Node.js · Express · Prisma · MySQL · Vue 3
Scale:    11 tenants · 24+ entities · 34 routes · 42 services
Runtime:  PM2 · Nginx · Ubuntu VPS
```

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=ff8700)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat&logo=prisma&logoColor=ff8700)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

</td>
<td width="50%" valign="top">

### 🟠 `pegasuz-brain.service`

<img src="https://img.shields.io/badge/RESEARCH-ff8700?style=for-the-badge&labelColor=0a0a0a" /> <img src="https://img.shields.io/badge/PRIVATE-ff0000?style=for-the-badge&labelColor=0a0a0a" />

**Autonomous AI orchestrator** · Parallel research project. Delegates, validates and learns across coding cycles. Memory tiers (state/knowledge/experience), dual-model pipeline, violation scoring, cycle reflection.

```
Layers:   T1 state · T2 knowledge · T3 experience · T4 intuition
Cycle:    remember → generate → validate → apply → learn → reflect
Runtime:  tmux · bash · python · LLM proxies
```

![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=ffd700)
![tmux](https://img.shields.io/badge/-tmux-1BB91F?style=flat&logo=tmux&logoColor=white)
![LLM](https://img.shields.io/badge/-LLM-ff5f00?style=flat&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🟡 [`wifilab.service`](https://github.com/FrancisElegante/WIFI-lab)

<img src="https://img.shields.io/badge/SECURITY_LAB-ffaf00?style=for-the-badge&labelColor=0a0a0a" /> <img src="https://img.shields.io/badge/GPU_CRACKING-87ff00?style=for-the-badge&labelColor=0a0a0a" />

**WiFi audit commander** · Web panel orchestrating pentesting lab: adapter management, real-time scanning, deauth/handshake/PMKID attacks, GPU hashcat cracking, post-exploitation, threat intelligence with CVE/OUI/WiGLE analysis.

```
Backend:  Python 3.12 · Flask 3.0 · Flask-SocketIO · SQLite WAL
Frontend: Vue 3.5 · Vite · Pinia · TypeScript · Tailwind 4
Hardware: Archer T4U v3 · TL-WN722N v2 · 2x RTX 3090
Arsenal:  aircrack-ng · hashcat · bettercap · hydra · nmap
```

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=ffd700)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=ff8700)
![Socket.IO](https://img.shields.io/badge/-SocketIO-010101?style=flat&logo=socket.io&logoColor=ff5f00)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![NVIDIA](https://img.shields.io/badge/-RTX_3090-76B900?style=flat&logo=nvidia&logoColor=white)

</td>
<td width="50%" valign="top">

### 🛰️ [`cansat-messi.service`](https://cansatmessi.pegasuz.com.ar/)

<img src="https://img.shields.io/badge/CANSAT_V2.0-ffd700?style=for-the-badge&labelColor=0a0a0a" /> <img src="https://img.shields.io/badge/team_MESSI-5fffff?style=for-the-badge&labelColor=0a0a0a" />

**Scale satellite prototype** · National CanSat project, team MESSI from Cipolletti, Río Negro. Prototype satellite at can-scale with onboard telemetry, payload systems, and mission monitoring. Public site hosted on Pegasuz tenant.

```
Mission:  Atmospheric telemetry · payload deployment · descent control
Tenant:   cansatmessi.pegasuz.com.ar (served by pegasuz.service)
Team:     MESSI · Cipolletti · Río Negro · Argentina
Scale:    Can-sized · real-flight prototype
```

![Embedded](https://img.shields.io/badge/-Embedded-8B0000?style=flat&logoColor=white)
![Sensors](https://img.shields.io/badge/-Sensors-5fffff?style=flat&labelColor=0a0a0a)
![Telemetry](https://img.shields.io/badge/-Telemetry-ff8700?style=flat&labelColor=0a0a0a)
![Vue](https://img.shields.io/badge/-Vue-4FC08D?style=flat&logo=vue.js&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🟢 `lampone.service`

<img src="https://img.shields.io/badge/PORTFOLIO-87ff00?style=for-the-badge&labelColor=0a0a0a" /> <img src="https://img.shields.io/badge/TERMINAL_NOIR-ff8700?style=for-the-badge&labelColor=0a0a0a" />

**Terminal-noir personal portfolio** · Built as a system booting up, not a webpage loading. Visible code culture at readable opacity, architectural typography (Bebas Neue at screen-filling scale), signal green dominance, scanlines, magnetic cursor, char-by-char reveals via GSAP SplitText. Zero generic startup language.

```
Aesthetic:  late-night SSH session · glowing CRT · mechanical keyboards
Motion:     scanlines · char-reveal · magnetic cursor · atmospheric gradients
Stack:      Vue 3 · Vite · GSAP · Lenis · SplitText · JetBrains Mono + Bebas Neue
```

![Vue](https://img.shields.io/badge/-Vue_3-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white)
![GSAP](https://img.shields.io/badge/-GSAP-88CE02?style=flat&logo=greensock&logoColor=white)
![Lenis](https://img.shields.io/badge/-Lenis-ff8700?style=flat&labelColor=0a0a0a)
![Pinia](https://img.shields.io/badge/-Pinia-FFD859?style=flat&logo=pinia&logoColor=black)

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── STACK ──────────────────────────────────────────────────────────────── -->

## 🧰 `dpkg -l | grep stack`

<div align="center">

### Backend · Runtime

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffd700)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=ff8700)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=ff5f00)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=ff8700)

### Databases

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Frontend

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Ops · Infrastructure · Security

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=ff8700)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Tools · Arsenal

![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=ff5f00)
![NVIDIA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white)
![nvim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── STATS ──────────────────────────────────────────────────────────────── -->

## 📊 `htop --user=francis`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=FrancisElegante&show_icons=true&hide_border=false&include_all_commits=true&count_private=true&bg_color=0a0a0a&title_color=ff5f00&icon_color=ff8700&text_color=ffaf00&border_color=ff5f00" />
<img height="180" src="https://github-readme-streak-stats.herokuapp.com?user=FrancisElegante&hide_border=false&background=0a0a0a&stroke=ff5f00&ring=ff8700&fire=ff0000&currStreakLabel=ff8700&sideLabels=ffaf00&currStreakNum=ffd700&dates=5fffff&sideNums=87ff00" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FrancisElegante&layout=compact&hide_border=false&bg_color=0a0a0a&title_color=ff5f00&text_color=ffaf00&border_color=ff5f00&langs_count=10" height="180" />
<img src="https://github-profile-trophy.vercel.app/?username=FrancisElegante&theme=matrix&no-frame=false&no-bg=true&margin-w=4&row=2&column=3" height="180" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=FrancisElegante&bg_color=0a0a0a&color=ff8700&line=ff5f00&point=ffd700&area=true&area_color=ff0000&hide_border=false&border_color=ff5f00&custom_title=%24%20journalctl%20-u%20francis%20--since%3D%22last%20year%22" width="96%" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── PRINCIPLES: tail -f ────────────────────────────────────────────────── -->

## 📜 `tail -f /var/log/principles.log`

```diff
[2026-04-16 16:42:01] INFO  src/core/engineering.ts
+ Database-per-tenant isolation over shared schema shortcuts
+ Explicit contracts over implicit magic
+ Read-only diagnostics before write operations
+ Invariants as code, not as folklore
+ Boring tech that ships over novel tech that promises
+ Tests that prove isolation, not tests that prove coverage
+ Fail in voice, not in silence

[2026-04-16 16:42:01] WARN  src/core/anti-patterns.ts
- Generic startup language ("elevate", "revolutionize", "empower")
- AI autonomy without supervision checkpoints
- Migrations without parity verification across tenants
- Monoliths masquerading as microservices
- Features without feature flags
- "It works on my machine" as deployment strategy
! God-objects over 1500 lines in single files
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,20,30&height=2" width="100%" />

<!-- ── PS AUX ─────────────────────────────────────────────────────────────── -->

## 🔧 `ps aux | grep francis | head -5`

```
USER      PID    %CPU   %MEM   STATE     TIME      COMMAND
francis   1001   94.3%  42.1%  RUNNING   1847h     schema-parity automation for pegasuz
francis   1002   88.7%  38.5%  RUNNING   1203h     autonomous orchestration cycles · brain
francis   1003   76.2%  31.8%  RUNNING   892h      motion layer refactor · lampone-v2
francis   1004   81.5%  44.2%  RUNNING   1521h     wifilab intelligence scoring engine
francis   1005   12.0%  04.0%  IDLE      ---       writing more at the shell prompt
```

<br/>

<!-- ── FOOTER ─────────────────────────────────────────────────────────────── -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffd700,30:ffaf00,60:ff8700,100:ff0000&height=140&section=footer&text=%24%20logout&fontColor=0a0a0a&fontSize=28&fontAlignY=68&animation=fadeIn" />

<div align="center">

<img src="https://komarev.com/ghpvc/?username=FrancisElegante&color=ff5f00&style=for-the-badge&label=VISITORS" />
<img src="https://img.shields.io/github/followers/FrancisElegante?style=for-the-badge&color=ff8700&labelColor=0a0a0a&label=FOLLOWERS" />
<img src="https://img.shields.io/github/stars/FrancisElegante?style=for-the-badge&color=ffd700&labelColor=0a0a0a&label=STARS" />

<br/><br/>

<sub>`[EOF]` · `connection closed by remote host` · `exit 0`</sub>

</div>

<!-- ══════════════════════════════════════════════════════════════════════════════
     END ~/.francisrc
     ══════════════════════════════════════════════════════════════════════════════ -->
