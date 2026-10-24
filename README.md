# PCI Scorer

**Interactive Pivot Control Index™ scoring tool, paste a transcript, get a scored breakdown.**

A live demo tool for [PivotControl AI](https://github.com/ACGLOVER2/pivotcontrol-ai).

---

## What It Does

Paste a sales call transcript excerpt, select your role and call type, and get a full Pivot Control Index™ analysis in under 60 seconds:

- PCI composite score (0 to 100) with Executive / Capable / Developing / At Risk rating
- Five-metric breakdown with score bars and specific observations
- Key observations and recommendations tied to actual transcript moments
- Language playback, moments of authority and moments to rebuild with reframed versions
- 30-day development plan with weekly focus areas and success signals
- Executive readiness trajectory

---

## Live Demo

→ **[pivotcontrol-ai.github.io/pci-scorer](https://pivotcontrol-ai.github.io/pci-scorer)** *(deploy via GitHub Pages)*

---

## How to Deploy

### GitHub Pages (recommended)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your scorer is live at `https://YOURUSERNAME.github.io/pci-scorer`

### Local
Open `index.html` directly in any browser. No build step required.

---

## How It Works

The scorer uses the Anthropic Claude API to analyze transcripts against the PCI framework. It applies role-specific rubrics based on your selected role and call type, the same methodology documented in the [PivotControl AI](https://github.com/ACGLOVER2/pivotcontrol-ai) and [Account Intelligence Layer](https://github.com/ACGLOVER2/account-intelligence-layer) repos.

**Supported roles:**
- Account Director, SC-Led Call
- Account Director, AD-Led Call
- Solutions Consultant
- Enterprise AE
- Founder / Executive Seller

**Supported call types:**
- SC-Led Executive Demo
- Discovery Call
- Executive Business Review
- Negotiation / Commercial Close
- Founder / Executive Intro
- Technical Discovery (SC)
- Renewal / Expansion

---

## The PCI Framework

The Pivot Control Index™ measures five dimensions of communication authority:

| Metric | What It Measures |
||-|
| Interruption Recovery | How cleanly authority is reclaimed after being interrupted or corrected |
| Structural Clarity | Whether responses are organized and compressed under pressure |
| Strategic Framing | Whether answers stay at executive/outcome level vs drifting tactical |
| Authority Signal Stability | Whether tone, pacing, and language confidence hold |
| Narrative Reclaim | Whether the speaker redirects conversation or follows the questioner's frame |

→ Full framework documentation: [PCI_FRAMEWORK.md](https://github.com/ACGLOVER2/pivotcontrol-ai/blob/main/framework/PCI_FRAMEWORK.md)

---

## Part of the PivotControl AI Portfolio

| Repo | What It Contains |
||-|
| [pivotcontrol-ai](https://github.com/ACGLOVER2/pivotcontrol-ai) | Framework, methodology, beta case studies |
| [account-intelligence-layer](https://github.com/ACGLOVER2/account-intelligence-layer) | Schema and data model for account-specific coaching |
| **pci-scorer** | This repo, interactive scoring tool |

---

## Built By

**Alaquondria Glover**, Founder, PivotControl AI  
*Authority Under Pressure for Enterprise Sellers*

---

*PCI Scorer uses the PivotControl AI framework. Proprietary methodology. All rights reserved.*

---

**Anonymization.** Organization names in this repository are replaced with sector and size descriptors. Individual names are replaced with bracketed role tokens such as `[AD]`, `[SC]` and `[Technical Lead]`, including inside verbatim quotes. Quantities, scores, timestamps and dollar figures are unchanged because they are load bearing in the findings and identify no one. No partner, customer, distributor or individual is identifiable from this repository.
