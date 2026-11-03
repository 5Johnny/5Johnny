<div align="center">

<a href="https://potatoverse.cloud">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:130d0a,55:f97316,100:ec5a9c&height=200&section=header&text=Jona%20Cohen&fontSize=70&fontColor=f4ead9&fontAlignY=38&desc=builder%20of%20the%20Potatoverse&descSize=22&descAlignY=60&animation=fadeIn" />
</a>

<br/>

[![Potatoverse](https://img.shields.io/badge/potatoverse.cloud-one_account%2C_every_potato-f97316?style=for-the-badge&logo=cloudflare&logoColor=white)](https://potatoverse.cloud)
[![GitLab](https://img.shields.io/badge/GitLab-jac--lab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/jac-lab)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-SLUG)
[![Email](https://img.shields.io/badge/Email-Reach_out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jonathancohen102@gmail.com)

</div>

---

## 🥔 About me

```yaml
# docker-compose.yml — the only service that never gets an image pin
services:
  jona:
    image: human:latest
    description: >
      I build the Potatoverse: a growing universe of small, sharp cloud
      tools, every one of them a potato, every one of them played
      completely straight.
    interests:
      - hosted AI agents that pass the "one click, no internals" test
      - MCP connectors over bespoke scrapers
      - running, and the maths of running slower on purpose
      - property and prediction markets, mostly as excuses to build databases
    environment:
      - STACK=FastAPI + Postgres + Terraform + Hetzner + Cloudflare
      - CI=GitLab, one pipeline shape for everything
      - VOICE=dry
    healthcheck:
      test: ["CMD", "curl", "-f", "https://potatoverse.cloud/healthz"]
    restart: unless-stopped
```

---

## 🌱 What's live in the verse

One account, every potato. Sign in once at [potatoverse.cloud](https://potatoverse.cloud) and the session follows you into every spud below.

| Spud | What it does | Status |
|---|---|---|
| [**Potato Farm**](https://farm.potatoverse.cloud) | Grow your own potatobot. A hosted AI agent on its own VM, provisioned with Terraform, paid for with Stripe, brain of your choice. The farm fits five. | ![](https://img.shields.io/website?url=https%3A%2F%2Ffarm.potatoverse.cloud%2Frobots.txt&up_message=growing&down_message=fallow&up_color=e8b14a&down_color=7d6a56&label=&style=flat-square) |
| [**Sweet Potato**](https://sweet.potatoverse.cloud) | Five shots a day. Make them count. Upload a photo, an AI scores it out of 100, you earn Potato Chips. | ![](https://img.shields.io/website?url=https%3A%2F%2Fsweet.potatoverse.cloud%2F&up_message=scoring&down_message=asleep&up_color=ec5a9c&down_color=7d6a56&label=&style=flat-square) |
| [**Potato Sack**](https://sack.potatoverse.cloud) | Your sporty spud running coach. Longest run in, today's pace out. Connects to Strava so it knows whether you're a bit mashed or full of steam. | ![](https://img.shields.io/website?url=https%3A%2F%2Fsack.potatoverse.cloud%2F&up_message=pacing&down_message=resting&up_color=4ade80&down_color=7d6a56&label=&style=flat-square) |
| [**openGym**](https://gym.potatoverse.cloud) | The gym. Sets, reps, body weight, a passkey instead of a password, and an AI coach with your own key. Upstream is [DuarteSantos8/openGym](https://github.com/DuarteSantos8/openGym), hosted here unmodified. Used daily. | ![](https://img.shields.io/website?url=https%3A%2F%2Fgym.potatoverse.cloud%2F&up_message=lifting&down_message=rest%20day&up_color=a3e635&down_color=7d6a56&label=&style=flat-square) |
| [**Couch Potato**](https://couch.potatoverse.cloud) | The serious business of doing absolutely nothing. A browser game about a potato on a sofa, framed as a cloud-ops dashboard. Snacks nominal. | ![](https://img.shields.io/website?url=https%3A%2F%2Fcouch.potatoverse.cloud%2F&up_message=loafing&down_message=offline&up_color=5cc8ff&down_color=7d6a56&label=&style=flat-square) |
| [**Hot Potato**](https://admin.potatoverse.cloud) | The control room. The delete button you handle with oven mitts. | ![](https://img.shields.io/website?url=https%3A%2F%2Fadmin.potatoverse.cloud%2F&up_message=warm&down_message=cold&up_color=f97316&down_color=7d6a56&label=&style=flat-square) |
| [**potatoverse.cloud**](https://potatoverse.cloud) | The front door. The catalogue, plus Potaccounts: GitHub, Google, or a magic link, and one `@handle` across the whole verse. | ![](https://img.shields.io/website?url=https%3A%2F%2Fpotatoverse.cloud%2F&up_message=open&down_message=closed&up_color=f4ead9&down_color=7d6a56&label=&style=flat-square) |

*Status badges knock on every app's front door, live. If one says "fallow", I already know.*

---

## 🔬 What I'm working on

> 🔌 &nbsp; **Connect your apps** — Potato Farm integrations as real MCP connectors with OAuth, not browser puppetry. The bar is the dumbo test: one click, no internals, nothing that looks hung.
>
> 🧠 &nbsp; **Bring-your-own brain** — the bot's model lives off the VM. Claude, OpenAI, or a free cloud model, and only the winning key ever ships to the box.
>
> 🏡 &nbsp; **Potato Plot** — every flat sold near Hampstead tube for two years, one row per flat, and a scorer that says whether a new listing is a good deal. Research, not a public spud yet.
>
> 🏋️ &nbsp; **Strava → gym sync** — every run on Strava is filed into openGym as a cardio entry the next morning. A headless Claude does it at 05:10 on a timer; rerunning adds nothing twice.

---

## 🛠️ Toolbox

<div align="center">

### Languages & runtime
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![HTML/CSS/JS](https://img.shields.io/badge/HTML%2FCSS%2FJS-no_build_step-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)
![ruff](https://img.shields.io/badge/ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

### Infra & delivery
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=for-the-badge&logo=hetzner&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Bitwarden](https://img.shields.io/badge/Bitwarden_Secrets-175DDC?style=for-the-badge&logo=bitwarden&logoColor=white)
![restic](https://img.shields.io/badge/restic_backups-1F2937?style=for-the-badge)

### Agents & AI
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_Cloud-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Hermes Agent](https://img.shields.io/badge/Hermes_Agent-6D28D9?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP_connectors-0EA5E9?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude_Code-1F2937?style=for-the-badge&logo=anthropic&logoColor=white)

### Money & integrations
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Strava](https://img.shields.io/badge/Strava-FC4C02?style=for-the-badge&logo=strava&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.1-059669?style=for-the-badge)

</div>

---

## 🚚 How every spud ships

```
FastAPI app  →  GitLab CI (validate → lint → test → build → release)
             →  image pinned in lab-ignition
             →  ACTION=ignite
             →  Cloudflare Tunnel  →  *.potatoverse.cloud  →  /healthz 200
```

One pipeline shape, one compose file, one VM. A new spud is a new compose profile and an image pin. The code lives on [GitLab](https://gitlab.com/jac-lab); this is the shop window.

---

<div align="center">

### *"Consistency beats heroics. Little and often wins the sack."*
**— Potato Sack, evergreen coach tip**

<br/>

**one account, every potato.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ec5a9c,45:f97316,100:130d0a&height=120&section=footer" />

</div>
