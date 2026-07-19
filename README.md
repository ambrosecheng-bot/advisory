# Ambrose Advisory — Launch Package

AI-powered business advisory for UK small businesses, run by **Ambrose Cheng CPA**
(30 years' accounting experience, KPMG-trained). This folder holds everything built
for the **1 August 2026 launch** in Southampton.

**🌐 Live website:** <https://ambrosecheng-bot.github.io/advisory/>

> **Business model at a glance**
> Sole trader, trading as *Ambrose Advisory* · Strictly AI consulting (no
> accountancy/bookkeeping services — a deliberate AML-scope decision) · Clients own
> their Claude subscription; we set up and train · Fixed project £2,000–2,500 +
> monthly retainer £500–700 · Milestone: **£8k/month by Mar 2027**, long-term £30k/month.

---

## Folder map

| Folder | What's inside |
|---|---|
| `01 Sales Kit/Website/` | `index.html` — bilingual (EN/中文) responsive one-page website, deploy-ready |
| `01 Sales Kit/Content/` | `Ambrose_Advisory_Content_Bank_August_2026.docx` — 12 ready-to-post pieces (8 EN + 4 中文) |
| `02 Clients/` | One folder per prospect/client (empty at launch) |
| `03 Templates/` | Sector-neutral master of the Health Check report template |
| `Southampton Dental Clinics/` | Full dental sales kit (see below) |
| `Southampton Essential Trades/` | Full trades sales kit (plumbing / heating / electrical) |
| `Southampton Restaurants/` | Original restaurant kit (in reserve — restaurants dropped as launch sector for recession exposure; kit still usable) |

Pre-existing folders (`000 …`, `01 HK CPA firms`, etc.) predate the launch package
and are unrelated to it.

## The sales kits

Each launch-sector folder contains the same three-piece kit:

1. **Pitch deck** (`…PainPoints_Claude_Solutions.pptx`, 9 slides) — five sector-specific
   pain points, each paired with the Claude ecosystem solution. Market-stats slide is
   evidence-based (BDA/FSB/NHS data, 2025–26).
2. **Client-facing guide** (`…Free_…_Health_Check….docx`, 2pp) — sent when a free
   health check is booked. Sets expectations: the five scored areas, the hour's flow,
   what to have ready, the promises.
3. **Report template** (`…Health_Check_Report_Template….docx`, 1p) — filled in and
   sent within 24 hours of every visit. Violet bracketed text = replace per client;
   traffic-light dots: keep one per row, delete the other two.

**Lead pain point per sector:** dental → NHS UDA clawback risk (the run-rate tracker
is the signature offer); trades → late payments / debtor days.

## The sales workflow

```
Content post / directory listing
        ↓
Free Health Check booked  →  send the sector guide
        ↓
1-hour visit (five traffic-light scores + one live AI demo)
        ↓
Report from template within 24 hours (fixed-price recommendation)
        ↓
2–4 week implementation project  →  monthly retainer
```

Cap diagnostics at 3–4/week. Track conversion: below ~1 in 3, the demo isn't landing;
above 1 in 2, start charging for the diagnostic and credit it against the project.

## Website

**Live now:** <https://ambrosecheng-bot.github.io/advisory/> (GitHub Pages, deployed
from `01 Sales Kit/Website/index.html`). To update the site, edit the local file and
push it to the `advisory` repo under the `ambrosecheng-bot` GitHub account.

Remaining upgrades when the domain is registered:

1. Register `ambroseadvisory.co.uk` + set up custom-domain email.
2. Point the domain at GitHub Pages (repo Settings → Pages → Custom domain) so the
   site lives at the branded address — better for trust and local SEO.
3. Replace the Gmail address with the domain email (ask Claude to sweep all
   deliverables in one pass) and add a booking link (e.g. Calendly).

## Brand

- **Colours:** espresso `#2B1D1A` · terracotta `#B85042` (+tint `#F8ECEA`) ·
  teal `#028090` (+tint `#E4F1F2`) · sand `#E7E8D1`
- **Fonts:** Calibri (EN) · Microsoft JhengHei (中文)
- **Voice:** accountant-first, plain English, no jargon; "you deal with a qualified
  accountant, not a salesperson"; every offer ends with the free health check.
- **Positioning line:** *30 years of accounting expertise × Claude AI automation.*
- Bilingual EN/中文 service (English · 廣東話 · 普通話) is a deliberate moat for
  Chinese-owned UK businesses.

## Pre-launch checklist (owner actions)

- [ ] Register domain + custom email
- [ ] Open business bank account (Starling / Monzo / Tide)
- [ ] Professional indemnity insurance (technology/management consultancy cover)
- [ ] ICO data-protection registration (~£40/yr)
- [ ] HMRC self-assessment registration (sole trader)
- [ ] Google Business Profile + LinkedIn + Facebook page
- [ ] Deploy website · schedule Week-1 posts from the content bank

Watch the **£90k VAT threshold** as revenue ramps; fold VAT registration into the
Ltd-conversion decision.

## Working with Claude on this business

Session memory (goals, folder conventions, setup decisions) persists in the Claude
project tied to the `Samlot Development Limited` working directory. For fewer
permission prompts, start future sessions directly in this folder.

Useful next automations (in order of leverage):
1. Fill a report template from visit notes (dictate on the drive back → finished report).
2. Monthly content-bank generation (September onwards).
3. Client-facing UDA run-rate tracker — the first productised deliverable.

---
*Package built 19 July 2026 with Claude Code. Deliverables QA'd by rendering through
PowerPoint/Word; website structure-validated.*
