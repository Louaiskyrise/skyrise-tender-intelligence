# Skyrise Tender Intelligence Platform

Business development platform for **Skyrise Capital PM** and **FS Consulting Engineers** — monitoring infrastructure consulting tenders across Africa and the Middle East.

## Features

- **Opportunities** — 20+ live tenders across World Bank, AfDB, AFD, UNDP, dgMarket, Devex with relevance scoring, filtering, and watchlist
- **BD Pipeline** — Kanban-style tracker: Reviewing → Bid Prep → Submitted → Won/Lost (persisted in localStorage)
- **AI Prospector** — Claude-powered tender intelligence and consortium partner matching (requires Anthropic API key)
- **Capabilities** — Consortium partner profiles: Skyrise, FS Consulting, CPCS, Vulcan, Chico Engineering, Good Engineering + capability matrix
- **Automation** — Step-by-step Zapier and Make workflow setup, ready-to-paste dgMarket RSS URL with all parameters, Claude API relevance scorer payload
- **Sources** — Direct links to all 6 monitored procurement portals
- **Alerts** — Email digest configuration

## Usage

Open `index.html` directly in any modern browser — no server or build step required.

To activate the AI Prospector, enter your [Anthropic API key](https://console.anthropic.com/) in **Settings**.

## dgMarket RSS Feed

```
https://www.dgmarket.com/tenders/rssfeed.do?noticeType=gpr&country=DJ,ET,KE,TZ,SN,CI,CM,MA,DZ,SA,AE,UG,RW&sector=TRN,WTR,ENE,URB,ENV&donor=WB,AFDB,AFD,UNDP,EU&language=en,fr&maxAge=30
```

Paste this URL into Zapier (RSS trigger) or Make (RSS Feed module) — see the Automation tab for full workflow instructions.

## Coverage

**Geographies** — Djibouti, Ethiopia, Kenya, Tanzania, Senegal, Côte d'Ivoire, Cameroon, Morocco, Algeria, Saudi Arabia, UAE, Uganda, Rwanda  
**Sectors** — Transport, Port & Maritime, Water & Sanitation, Infrastructure, PMO, Engineering Supervision, Advisory & Studies, Environment & ESIA  
**Financiers** — World Bank, AfDB, AFD, UNDP, EU
