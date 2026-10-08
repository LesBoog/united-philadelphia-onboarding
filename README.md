# United Real Estate Philadelphia — Agent Onboarding Portal

Premium SaaS-style agent recruiting and onboarding experience for **United Real Estate Philadelphia**.

**Repository:** https://github.com/LesBoog/united-philadelphia-onboarding

## Features

- Homepage focused on economic advantage vs traditional brokerages (KW, HomeSmart, Compass, RE/MAX)
- Brokerage comparison tool with illustrative presets (editable)
- Commission calculator (estimates only)
- Onboarding Center — 7-step progress dashboard with checklists
- Technology, Leads, First 30 Days, Training sections
- Recruiter dashboard (access-gated) — step progress only; no private agent PII
- Mobile-responsive, Stripe/HubSpot-inspired product UI

## Files in this repo

| File | Description |
|------|-------------|
| `README.md` | This file |
| `onboarding-dashboard.html` | Standalone onboarding center |
| `index.html` | Entry redirect helper |
| `load-portal.html` | Loader for chunked portal assembly |

## Add the full portal (required)

The complete single-file portal is **`united-onboarding.html`** (~70KB).  
Upload it to this repository:

1. Open https://github.com/LesBoog/united-philadelphia-onboarding
2. Click **Add file → Upload files**
3. Drop `united-onboarding.html` from your project artifacts
4. Commit

Or from a terminal (with GitHub CLI or git):

```bash
git clone https://github.com/LesBoog/united-philadelphia-onboarding.git
cd united-philadelphia-onboarding
# copy united-onboarding.html into this folder
git add united-onboarding.html
git commit -m "Add full agent onboarding portal"
git push
```

## Local preview

```bash
python3 -m http.server 8765
# Open http://localhost:8765/united-onboarding.html
```

## Recruiter dashboard

- Footer link **Recruiter**, or `#recruiter`
- Demo access code: `UNITED`
- Shows first name + last initial and step progress only

## Important notes

- All commission figures are **estimates**. Confirm terms with United Real Estate Philadelphia.
- Program availability, fees, and offerings are subject to change.
- Each office is independently owned and operated.

## Contact

**Lester Washington** — Talent Acquisition Specialist  
Phone: 484-367-7727  
Email: Lwashington@unitedrealestate.com
