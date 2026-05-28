# Google Ads · Q2 Optimization

![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Updated](https://img.shields.io/badge/updated-May%202026-4C62EA?style=flat-square)
![Maintained by](https://img.shields.io/badge/maintained%20by-marketing-facc0b?style=flat-square)
![Internal](https://img.shields.io/badge/scope-internal-71717a?style=flat-square)

> **Internal workspace tracking FreightSimple's Google Ads optimization initiative.**
> A diagnosis of the FS2026.CA.Search.Core campaign, a complete copy and landing-page strategy, and a 3-week rollout to recover wasted spend and scale what's already working.

---

## 🔗 Live workspace

**👉 [https://freightsimple.github.io/google-ads-q2/](#)** _(replace with actual URL once GitHub Pages is activated)_

The link above is the canonical place to view this work. The hub provides navigation, current status, and the rollout timeline. Always share this URL with the team — never individual files.

---

## 📋 What this is

In May 2026, the FS2026.CA.Search.Core campaign was diagnosed as underperforming despite a reported 3.83× ROAS. Beneath the average were three concurrent issues:

1. **15% of monthly spend** was evaporating across 8 ad groups with zero conversions
2. **Landing pages** were hurting both Quality Score (SEM) and organic rankings (SEO) simultaneously
3. **A premature shift** to a Smart Bidding strategy with insufficient conversion volume

This workspace contains the full analysis, the rewritten ad copy, and the rollout plan. It will continue to live as a single source of truth as the initiative executes through Q2 — performance recaps, landing page briefs, and bid-strategy migration plans will be added here.

---

## 📚 Documents

### 🏠 [`index.html`](./index.html) — Workspace hub
The front door. Includes current performance metrics, a 3-week rollout timeline, links to both documents, and a pipeline of upcoming work. **Share this URL with the team.**

### 📊 [`google-ads-analysis-EN.html`](./google-ads-analysis-EN.html) — Doc 01 · Performance analysis
30-day diagnosis of the FS2026.CA.Search.Core campaign.

**Contains:**
- Executive summary with four key findings
- Current state across six top-level metrics
- ROAS distribution by ad group, with chart
- Root cause analysis on landing pages (with evidence from Google's own reports)
- Risk assessment of the May 25 bid strategy changes
- Three-phase action plan with projected impact
- Four decisions required from leadership

**Audience:** Chris, leadership team
**Length:** 7 sections, ~15 min read

---

### 🛠️ [`google-ads-execution-plan-EN.html`](./google-ads-execution-plan-EN.html) — Doc 02 · Execution plan
The "what" and "when" of the optimization. Companion document to the analysis.

**Contains:**
- Rewritten copy for **10 ad groups** (Generic LTL + 9 carriers)
- Two RSA variants per ad group: Speed angle and Contrarian angle
- Carrier-specific value propositions based on operational strength
- Landing page strategy (final + interim) per ad group
- 3-week deployment schedule sequenced by LP dependency
- Summary table of every change by ad group
- Decisions required from leadership

**Audience:** Marketing team, Chris
**Length:** 6 sections, ~20 min read

---

## 📊 Current state at a glance

| Metric | Value | Direction |
|---|---|---|
| Monthly spend | 3,711 CAD | Stable |
| Conversions/month | 23 | Below target (40+) |
| Reported ROAS | 3.83× | To validate |
| Average CPC | 4.37 CAD | High (Quality Score impact) |
| Wasted spend identified | 545 CAD/mo | Pausing in W1 |
| Top ROAS (underfunded) | 66× | Scaling in W1 |
| Projected value uplift | +6,600 CAD/mo | From reallocation alone |

---

## 🗓️ Rollout schedule

### Week 1 — _Now_
Quick wins, no product changes.
- Pause 8 ad groups with zero conversions
- Launch new copy in Generic LTL, Day & Ross, Manitoulin
- Revert bid strategy to Maximize Conversions
- Activate ad extensions (sitelinks, callouts, snippets)

### Week 2
Build the landing base.
- Build `/ltl-carriers` interim comparison page
- Build `/content/tforce` and `/content/abf`
- Audit empty `/content/*` pages
- First performance check-in

### Weeks 3 & 4
Relaunch carriers, scale winners.
- Relaunch TForce, ABF, Vitran (W3)
- Build remaining LPs: SAIA, XPO, Estes, FedEx Freight, Roadrunner
- Relaunch remaining 6 ad groups (W4)
- Scale budget on "Comparison" ad group

---

## 🛠️ How this workspace stays updated

This is a living workspace. As the initiative executes, new documents get added — performance recaps, landing page briefs, follow-on analyses.

### To add a new document

1. Create the HTML file using the existing FreightSimple visual system (see below)
2. Place it in the repo root
3. Update `index.html` to link to it from the appropriate section (Documents / Pipeline)
4. Update this README with a new entry under **Documents**
5. Commit with a descriptive message

```bash
git add new-doc.html index.html README.md
git commit -m "Add: [document name]"
git push
```

GitHub Pages auto-deploys on push to `main` — the live URL updates in ~60 seconds.

### To suggest changes to an existing document

Open an issue in this repo describing what you'd like changed and why. For copy edits, propose the new wording inline. For structural changes, sketch the intent.

---

## 🎨 Visual system

All documents in this workspace follow the FreightSimple visual system:

- **Display type:** Plus Jakarta Sans (700–900, italic for accents)
- **Body type:** Inter (400–600)
- **Mono / data:** JetBrains Mono (500–700)
- **Primary action:** Blue `#4C62EA`
- **Editorial emphasis:** Gold `#facc0b`
- **Surface:** Cream `#FFF8E7` and white
- **Semantic colors:** Used precisely — red only for losses, green only for wins

New documents added to this workspace should match this system. If something requires a new pattern, validate first against the canonical brand book (in the main marketing repo).

---

## 📁 Repo structure

```
freightsimple-google-ads/
├── README.md                           ← you are here
├── index.html                          ← workspace hub (share this URL)
├── google-ads-analysis-EN.html         ← Doc 01 · Performance analysis
└── google-ads-execution-plan-EN.html   ← Doc 02 · Execution plan
```

---

## 👥 Ownership

**FreightSimple · Marketing**
For questions, decisions, or new doc additions — reach out via Slack `#marketing` or open an issue in this repo.

**Last updated:** May 28, 2026
**Next scheduled update:** Week 1 performance check-in (early June 2026)
