<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0A0E1A,25:061424,50:0D1F35,75:061424,100:0A0E1A&height=300&section=header&text=QAMBER.EXE&fontSize=80&fontColor=00D4FF&animation=blink&fontAlignY=45&desc=→%20Full%20Stack%20Engineer%20·%20Gwadar%2C%20Balochistan%20·%20Building%20where%20it%20matters&descSize=15&descAlignY=67&descColor=FFB800&stroke=00D4FF&strokeWidth=2"/>
</div>

<br/>

<div align="center">

[![3D Space - Interactive Profile](https://img.shields.io/badge/ENTER_3D_GRID-00D4FF?style=for-the-badge&logo=three.js&logoColor=0A0E1A&labelColor=FFB800)](https://qambers-cyber-grid.vercel.app)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-00D4FF?style=for-the-badge&logo=linkedin&logoColor=0A0E1A)](https://linkedin.com/in/qamber-muhammed-hanif/)
&nbsp;
[![Cherág Live](https://img.shields.io/badge/Cherág_Live-FF4D6D?style=for-the-badge&logo=cloudflare&logoColor=white)](https://cherag.pages.dev)
&nbsp;
![Views](https://komarev.com/ghpvc/?username=Qamber02&style=for-the-badge&color=0D2137&label=VIEWS&labelColor=00D4FF)

</div>

<br/>

---

## `> $ whoami`

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                                                                              │
│  $ whoami                                                                    │
│                                                                              │
│  ▶  Qamber Muhammed Hanif                                                    │
│  ▶  BSCS @ University of Turbat  ·  GPA 3.40  ·  Class of 2027              │
│  ▶  Building Karwan — food delivery for markets Foodpanda skipped            │
│                                                                              │
│  $ location --verbose                                                        │
│                                                                              │
│  ▶  25.1264° N, 62.3225° E  ·  Gwadar, Balochistan, Pakistan                │
│  ▶  ~650km from where the apps stop                                          │
│                                                                              │
│  $ cat mission.txt                                                           │
│                                                                              │
│  ▶  Ship production systems, not demos.                                      │
│  ▶  4-agent Claude Code · parallel branches · merge at velocity              │
│                                                                              │
│  $ exit 0                                                                    │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

---

## `> SYSTEM PROFILE`

<table>
<tr>
<td width="55%" valign="top">

I ship **production systems**, not demos.

My market is Gwadar and Turbat — two cities in Balochistan with 500k+ people, zero app-based food delivery, one dictionary for local languages, and students without access to quality tutoring. That's the gap I'm building into.

Current weapons: **Flutter · FastAPI · React · Supabase · Node.js**

Current workflow: **4 parallel Claude Code agents** across isolated git branches — one per feature, merging at velocity.

Current battleground: **Stripe Connect** onboarding, multi-tenant payout flows, and keeping a Render free-tier server warm via UptimeRobot.

```python
class Qamber:
    stack    = ["Flutter", "FastAPI", "React",
                "Supabase", "Node.js", "TypeScript",
                "PostgreSQL"]
    infra    = ["Docker", "Azure", "Cloudflare", "Linux"]
    mission  = "build where the gap is"
    workflow = "4-agent Claude Code, parallel branches"
    gpa      = 3.40
    ships    = True   # not demos
```

</td>
<td width="45%" align="center" valign="top">

```
╔══════════════════════════════════╗
║  LIVE PROJECTS                   ║
╠══════════════════════════════════╣
║  🟢  Karwan     →  IN DEV        ║
║  🟢  Cherág     →  LIVE          ║
║  🔵  Pajjar     →  SHIPPED       ║
╠══════════════════════════════════╣
║  CURRENT STACK                   ║
╠══════════════════════════════════╣
║  Flutter  ████████████░  90%     ║
║  FastAPI  ███████████░░  88%     ║
║  React    ██████████░░░  82%     ║
║  Node.js  █████████░░░░  75%     ║
║  DevOps   ████████░░░░░  65%     ║
╚══════════════════════════════════╝
```

</td>
</tr>
</table>

---

## `> PROJECTS --depth=full`

<!-- ─────────────────────────── KARWAN ─────────────────────────── -->
<details open>
<summary><b>📦 &nbsp; KARWAN — Hyperlocal Food Delivery &nbsp;·&nbsp; Gwadar &amp; Turbat</b></summary>

<br/>

> **The problem:** Foodpanda covers Pakistan up to Quetta. Gwadar is 650km south. Zero app-based food delivery exists in either city. Karwan fills the gap.

```
SYSTEM TOPOLOGY
══════════════════════════════════════════════════════════════════════
                                                                      
  ┌─────────────────────┐    ┌──────────────────────┐                
  │  Flutter             │    │  React               │                
  │  Customer App        │    │  Restaurant Panel    │                
  │  order · track · pay │    │  menu · orders · rev │                
  └──────────┬──────────┘    └──────────┬───────────┘                
             │                          │                             
             ▼                          ▼                             
  ┌──────────────────────────────────────────────────┐               
  │          FastAPI  ·  Core API Gateway            │               
  │          Supabase ·  Realtime DB + Auth          │               
  └────┬─────────────┬──────────────┬───────────────┘               
       │             │              │                                 
       ▼             ▼              ▼                                 
  [Firebase     [JazzCash /    [Twilio         [Azure                 
   FCM Push]     EasyPaisa]    WhatsApp]        Container Apps]       
  push notif    local pay      confirmations    backend host          
                rails                                                 
                                                                      
  ┌──────────────────────────────────────────────────┐               
  │  React Admin Dashboard  ·  ops · disputes · stats│               
  └──────────────────────────────────────────────────┘               
                                                                      
  COMMISSION: 12%  │  RIDERS: restaurant-managed  │  CITIES: 2       
══════════════════════════════════════════════════════════════════════
```

![Flutter](https://img.shields.io/badge/Flutter-0A0E1A?style=flat-square&logo=flutter&logoColor=00D4FF)
![FastAPI](https://img.shields.io/badge/FastAPI-0A0E1A?style=flat-square&logo=fastapi&logoColor=00D4FF)
![Supabase](https://img.shields.io/badge/Supabase-0A0E1A?style=flat-square&logo=supabase&logoColor=FFB800)
![Azure](https://img.shields.io/badge/Azure-0A0E1A?style=flat-square&logo=microsoftazure&logoColor=00D4FF)
![Firebase](https://img.shields.io/badge/Firebase-0A0E1A?style=flat-square&logo=firebase&logoColor=FFB800)
![JazzCash](https://img.shields.io/badge/JazzCash-0A0E1A?style=flat-square&logoColor=FF4D6D)
![Twilio](https://img.shields.io/badge/Twilio-0A0E1A?style=flat-square&logo=twilio&logoColor=FF4D6D)

</details>

---

<!-- ─────────────────────────── CHERÁG ─────────────────────────── -->
<details open>
<summary><b>🔆 &nbsp; CHERÁG — AI Study Platform &nbsp;·&nbsp; Live at cherag.pages.dev</b></summary>

<br/>

> **The problem:** Quality tutoring in Pakistan costs money students don't have. Cherág transforms course material into interactive study sessions — free, AI-powered, accessible anywhere.

```
SYSTEM TOPOLOGY
══════════════════════════════════════════════════════════════════════
                                                                      
  ┌─────────────────────────────────────────────────┐                
  │  React 19 + Vite  ·  Frontend SPA               │                
  │  Knowledge Radar · Feynman Mode · Exam Sim      │                
  │  Video Intelligence                              │                
  └────────────────────────┬────────────────────────┘                
                           │                                          
                           ▼                                          
  ┌─────────────────────────────────────────────────┐                
  │  FastAPI  ·  AI Orchestration Layer              │                
  │                                                  │                
  │  Primary  ──▶  Gemini 2.0 Flash                  │                
  │  Fallback ──▶  DeepSeek + OpenRouter models      │                
  │                (smart failover, never goes down)  │                
  └──────────┬─────────────────────┬────────────────┘                
             │                     │                                  
             ▼                     ▼                                  
  [Supabase + PostgreSQL]    [Cloudflare Pages]   [Azure              
   auth · storage · db       frontend CDN          Container Apps]    
                                                   API host           
                                                                      
  License: MIT  ·  Fork it, run it, extend it                        
══════════════════════════════════════════════════════════════════════
```

![React](https://img.shields.io/badge/React_19-0A0E1A?style=flat-square&logo=react&logoColor=00D4FF)
![Vite](https://img.shields.io/badge/Vite-0A0E1A?style=flat-square&logo=vite&logoColor=00D4FF)
![FastAPI](https://img.shields.io/badge/FastAPI-0A0E1A?style=flat-square&logo=fastapi&logoColor=00D4FF)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Pages-0A0E1A?style=flat-square&logo=Cloudflare&logoColor=FFB800)
![Supabase](https://img.shields.io/badge/Supabase-0A0E1A?style=flat-square&logo=supabase&logoColor=FFB800)
![Gemini](https://img.shields.io/badge/Gemini_2.0-0A0E1A?style=flat-square&logo=google&logoColor=FF4D6D)

</details>

---

<!-- ─────────────────────────── PAJJAR ─────────────────────────── -->
<details>
<summary><b>📖 &nbsp; PAJJAR — Offline Language Dictionary &nbsp;·&nbsp; Balochistan</b></summary>

<br/>

> **The problem:** Languages in Balochistan have no digital preservation. No internet required — works fully offline, community-driven, 100% local storage.

```
SYSTEM TOPOLOGY
══════════════════════════════════════════════════════════════════════
                                                                      
  ┌─────────────────────────────────────┐                            
  │  Flutter  ·  Cross-Platform App     │                            
  │  Dictionary UI · Search · Browse    │                            
  └──────────────────┬──────────────────┘                            
                     │                                                
                     ▼                                                
  ┌─────────────────────────────────────┐                            
  │  SQLite  ·  Local-First Database    │                            
  │  Community entries · Offline sync   │                            
  │  Zero external dependencies         │                            
  └─────────────────────────────────────┘                            
                                                                      
  ARCH: Offline-first  ·  100% local  ·  Community entries           
  GOAL: Long-term preservation of endangered Balochi dialects         
══════════════════════════════════════════════════════════════════════
```

![Flutter](https://img.shields.io/badge/Flutter-0A0E1A?style=flat-square&logo=flutter&logoColor=00D4FF)
![Dart](https://img.shields.io/badge/Dart-0A0E1A?style=flat-square&logo=dart&logoColor=00D4FF)
![SQLite](https://img.shields.io/badge/SQLite-0A0E1A?style=flat-square&logo=sqlite&logoColor=FFB800)

</details>

---

## `> TECH STACK`

<div align="center">

**— MOBILE —**

![Flutter](https://img.shields.io/badge/Flutter-0A0E1A?style=for-the-badge&logo=flutter&logoColor=00D4FF)
![Dart](https://img.shields.io/badge/Dart-0A0E1A?style=for-the-badge&logo=dart&logoColor=00D4FF)

**— FRONTEND —**

![React](https://img.shields.io/badge/React-0A0E1A?style=for-the-badge&logo=react&logoColor=00D4FF)
![TypeScript](https://img.shields.io/badge/TypeScript-0A0E1A?style=for-the-badge&logo=typescript&logoColor=00D4FF)
![Next.js](https://img.shields.io/badge/Next.js-0A0E1A?style=for-the-badge&logo=next.js&logoColor=00D4FF)
![TailwindCSS](https://img.shields.io/badge/Tailwind-0A0E1A?style=for-the-badge&logo=tailwind-css&logoColor=00D4FF)
![Vite](https://img.shields.io/badge/Vite-0A0E1A?style=for-the-badge&logo=vite&logoColor=00D4FF)

**— BACKEND + DATABASE —**

![FastAPI](https://img.shields.io/badge/FastAPI-0A0E1A?style=for-the-badge&logo=fastapi&logoColor=00D4FF)
![Node.js](https://img.shields.io/badge/Node.js-0A0E1A?style=for-the-badge&logo=nodedotjs&logoColor=00D4FF)
![Python](https://img.shields.io/badge/Python-0A0E1A?style=for-the-badge&logo=python&logoColor=FFB800)
![Supabase](https://img.shields.io/badge/Supabase-0A0E1A?style=for-the-badge&logo=supabase&logoColor=FFB800)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A0E1A?style=for-the-badge&logo=postgresql&logoColor=FFB800)
![MongoDB](https://img.shields.io/badge/MongoDB-0A0E1A?style=for-the-badge&logo=mongodb&logoColor=FFB800)
![Firebase](https://img.shields.io/badge/Firebase-0A0E1A?style=for-the-badge&logo=firebase&logoColor=FFB800)

**— CLOUD + INFRA —**

![Docker](https://img.shields.io/badge/Docker-0A0E1A?style=for-the-badge&logo=docker&logoColor=FFB800)
![Azure](https://img.shields.io/badge/Azure-0A0E1A?style=for-the-badge&logo=microsoftazure&logoColor=FFB800)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0A0E1A?style=for-the-badge&logo=Cloudflare&logoColor=FFB800)
![Linux](https://img.shields.io/badge/Linux-0A0E1A?style=for-the-badge&logo=linux&logoColor=FF4D6D)
![Git](https://img.shields.io/badge/Git-0A0E1A?style=for-the-badge&logo=git&logoColor=FF4D6D)

**— AI + INTEGRATIONS —**

![Gemini](https://img.shields.io/badge/Google_Gemini-0A0E1A?style=for-the-badge&logo=google&logoColor=FF4D6D)
![Stripe](https://img.shields.io/badge/Stripe-0A0E1A?style=for-the-badge&logo=stripe&logoColor=FF4D6D)
![Twilio](https://img.shields.io/badge/Twilio-0A0E1A?style=for-the-badge&logo=twilio&logoColor=FF4D6D)
![Cloudinary](https://img.shields.io/badge/Cloudinary-0A0E1A?style=for-the-badge&logo=cloudinary&logoColor=FF4D6D)

</div>

---

## `> GITHUB STATS`

<div align="center">

<img src="https://github-readme-streak-stats-azure-nine-36.vercel.app?user=Qamber02&theme=tokyonight&hide_border=true&border_radius=10&ring=00D4FF&fire=FFB800&currStreakLabel=00D4FF&sideLabels=FFB800&dates=E6EDF3&currStreakNum=00D4FF&sideNums=E6EDF3&background=0A0E1A" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api?username=Qamber02&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A0E1A&title_color=00D4FF&icon_color=FFB800&text_color=E6EDF3&border_radius=10" width="49%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Qamber02&theme=tokyo-night&hide_border=true&bg_color=0A0E1A&color=00D4FF&line=FFB800&point=FF4D6D&area=true&area_color=0D2137" width="100%"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Qamber02&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A0E1A&title_color=00D4FF&text_color=E6EDF3&border_radius=10&langs_count=8"/>

</div>

---

## `> CONNECT`

<div align="center">

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                                                                              │
│   Open to:   Internships  ·  Collaborations  ·  Contracting                 │
│   Focus:     South Asia  ·  Underserved markets  ·  EdTech                  │
│   Timezone:  PKT (UTC+5)                                                     │
│                                                                              │
│   →  linkedin.com/in/qamber-muhammed-hanif                                  │
│   →  qambers-cyber-grid.vercel.app                                          │
│   →  cherag.pages.dev                                                        │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-00D4FF?style=for-the-badge&logo=linkedin&logoColor=0A0E1A)](https://linkedin.com/in/qamber-muhammed-hanif/)
&nbsp;
[![Portfolio →](https://img.shields.io/badge/Portfolio_→-FFB800?style=for-the-badge&logo=vercel&logoColor=0A0E1A)](https://qambers-cyber-grid.vercel.app)

</div>

---

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0A0E1A,25:061424,50:0D1F35,75:061424,100:0A0E1A&height=140&section=footer&text=Built%20from%20Gwadar%20·%20Shipped%20to%20the%20world&fontSize=20&fontColor=00D4FF&animation=twinkling&fontAlignY=55&desc=25.1264°%20N%2C%2062.3225°%20E%20·%20~650km%20from%20where%20the%20apps%20stop&descSize=12&descAlignY=78&descColor=FFB800"/>
</div>
