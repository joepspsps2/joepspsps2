# Hi, I'm Joe Lin 👋

I build and run a network of public websites in Taiwan **by directing a team of AI coding agents** (Claude Code & Codex). I set the architecture, data standards and review gates; the agents write most of the code.

- 🔭 Writing **[老喬報 Joe's Report](https://joelin.cc)** — notes on Taiwan wealth, business in the AI era, and building websites
- 🤖 Up to **21 AI agents running at once**; 10,000+ contributions in the past year (mostly private repos)
- 🌏 Based in Taipei, Taiwan · [more about me](https://me.joelin.cc)

## What I've built

| Site | What it does |
|---|---|
| [joelin.cc](https://joelin.cc) | Main site & newsletter 老喬報 |
| [photobooth.joelin.cc](https://photobooth.joelin.cc) | Photo booth & ID photo booth finder — Taiwan, Japan, Korea and Southeast Asia, multilingual |
| [fansupport.joelin.cc](https://fansupport.joelin.cc) | Birthday & fan-support database for idols, cheerleaders, VTubers and character IPs |
| [atlas.joelin.cc](https://atlas.joelin.cc) | Understand places in perspective — compare places through familiar geographic reference points |
| [clinic.joelin.cc](https://clinic.joelin.cc) | Taiwan clinics, hospitals & pharmacies by district, from official health-ministry registry data |
| [edu.joelin.cc](https://edu.joelin.cc) | Taiwan kindergarten supply statistics across 368 districts, with a decade of change |
| [trash.joelin.cc](https://trash.joelin.cc) | Garbage truck schedules for all 22 cities and counties in Taiwan |
| [concafe.joelin.cc](https://concafe.joelin.cc) | Concept & maid café database — Taiwan, Japan, Korea, Vietnam, Indonesia |
| [flexspace.joelin.cc](https://flexspace.joelin.cc) | Company registration addresses & small office spaces in Taiwan |
| [tools.joelin.cc](https://tools.joelin.cc) | Small everyday tools |
| [events.joelin.cc](https://events.joelin.cc) | Event sign-ups |

## Platform & internal tools

| Tool | What it does |
|---|---|
| [id.joelin.cc](https://id.joelin.cc) | Single sign-on for all my sites — a multi-tenant identity provider (OAuth 2.0 / OIDC) |
| [forms.joelin.cc](https://forms.joelin.cc) | Survey & form platform |
| [meet.joelin.cc](https://meet.joelin.cc) | Meeting scheduling |
| Short links *(private)* | Redirect service behind the QR codes on my cards and posters |
| Search data pipeline *(private)* | Pulls Google Search Console, GA4 and Cloudflare data into Postgres, classifies keywords, and produces weekly SEO reports |
| Report center *(private)* | Internal analytics dashboard |
| Watchdog *(private)* | Monitors logins, deployments and uptime across the network; alerts to Discord |
| Site kit *(private)* | Starter kit every new site is generated from — sitemaps, search-engine pings, lint rules |

## How I build

- **One knowledge base as the control tower.** A private wiki holds every decision, rule and hand-off, so dozens of parallel agent sessions stay consistent.
- **Evidence first.** Public facts must trace back to official or primary sources; agents are told to stop when a premise can't be verified.
- **Gates instead of reminders.** Every change gets an automated security review, sites are built from a shared starter kit, and lint and deploy checks block releases instead of relying on someone to remember.

---

📫 [LinkedIn](https://www.linkedin.com/in/joepspsps2/) · [X](https://twitter.com/joepspsps2) · [joelin.cc](https://joelin.cc)
