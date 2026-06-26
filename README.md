# Avartana — अवर्तन
### *Digital Product Passport for Electronics*

> **"Giving e-waste a second life, one device at a time."**

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-10B981?style=flat-square" alt="MIT License" />
  <img src="https://img.shields.io/badge/SDG-12-10B981?style=flat-square" alt="SDG 12" />
  <img src="https://img.shields.io/badge/SDG-9-22D3EE?style=flat-square" alt="SDG 9" />
  <img src="https://img.shields.io/badge/SDG-13-10B981?style=flat-square" alt="SDG 13" />
  <img src="https://img.shields.io/badge/UNTP-Aligned-8B5CF6?style=flat-square" alt="UNTP Aligned" />
  <img src="https://img.shields.io/badge/Hackathon-Parul_University_2026-FF6B6B?style=flat-square" alt="Hackathon" />
  <img src="https://img.shields.io/badge/Zero_Cost-₹0-10B981?style=flat-square" alt="Zero Cost" />
</p>

---

> *"Every year, 62 million tonnes of electronic waste is dumped or burned — losing $62 billion in gold, copper, and lithium. We built the infrastructure to stop that."*

---

##  Table of Contents

- [The Problem](#-the-problem)
- [Why It Matters for India](#-why-it-matters-for-india)
- [Our Solution](#-our-solution)
- [How It Works](#-how-it-works)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [UN & Policy Alignment](#-un--policy-alignment)
- [Impact Projections](#-impact-projections)
- [Roadmap](#-roadmap)
- [Competitors & Differentiation](#-competitors--differentiation)
- [Why Avartana Wins](#-why-avartana-wins)
- [References](#-references)
- [Team](#-team)
- [License](#-license)

---

##  The Problem

### Global E-Waste Crisis

The world generated a record **62 million tonnes** of electronic waste in 2022 — enough to fill 1.55 million 40-tonne trucks placed bumper-to-bumper around the equator.

| Metric | Value |
|---|---|
| E-waste generated (2022) | **62 million tonnes** |
| Annual growth rate | **2.6M tonnes/year** |
| Projected by 2030 | **82 million tonnes** |
| Formally recycled | **Only 22.3%** |
| Lost annually in metals | **USD $62 billion** |

*Source: Global E-waste Monitor 2024, UNITAR & ITU*

### What Happens to the 77.7%?

| Destination | Consequence |
|---|---|
|  **Burned** by informal recyclers | Releases dioxins, furans, and heavy metals |
|  **Dumped** in landfills | Contaminates groundwater with mercury, lead, and cadmium |
|  **Illegally exported** to developing nations | Under the guise of "second-hand goods" |
|  **Hoarded** in drawers and closets | Never recycled at all |

### The Core Information Gap

```
Consumer  ──?──►  Recycler
(has old device)   (needs material data)

Producer  ──?──►  Regulator
(must prove EPR)   (needs verified records)

Device    ──?──►  Circular Economy
(has gold,         (needs material passport)
copper, lithium)
```

**No unified digital system exists** to tell a consumer what's inside their device, where to take it, and to verify that recycling actually happened.

**That is exactly what this project solves.**

---

## 🇮🇳 Why It Matters for India

India is the world's **third-largest generator of e-waste**:

| Metric | Value |
|---|---|
| Annual e-waste generation | **6.19 million tonnes** |
| Annual growth rate | **16.9% per year** |
| Global rank | **3rd largest generator** |
| Critical mineral imports | **100% dependent** (lithium, cobalt) |
| EPR recycling mandate | **70% by 2026–27** |

**India imports 100% of its critical minerals** — yet buries the same materials in 6 million tonnes of e-waste every year.

> *The solution to India's mineral import dependency is literally under our desks, in our drawers, and in our old phones.*

---

##  Our Solution

**Avartana** (अवर्तन — Sanskrit for *"Cycle"*) is a **Digital Product Passport (DPP) platform** for electronics — a web-based application that gives every electronic device a digital identity containing:

- ✅ Its complete material composition (which metals, at what percentages)
- ✅ Its recyclability score and estimated recovery value
- ✅ Certified recyclers near the user who can process it properly
- ✅ A tamper-evident verification ledger proving recycling happened

### The Three-Sided Bridge

```
              ┌──────────────────────────┐
              │         AVARTANA         │
              │  Digital Product Passport│
              └──────────┬───────────────┘
                         │
           ┌─────────────┼─────────────┐
           │             │             │
    ┌──────▼─────┐ ┌─────▼──────┐ ┌───▼────────────┐
    │  CONSUMER  │ │  RECYCLER  │ │    PRODUCER    │
    │            │ │            │ │                │
    │ Knows what │ │ Gets mat.  │ │ Proves EPR     │
    │ to recycle │ │ data in    │ │ compliance     │
    │ and where  │ │ advance    │ │ digitally      │
    └────────────┘ └────────────┘ └────────────────┘
```

---

##  How It Works

```
┌───────────┐    ┌───────────┐    ┌───────────┐    ┌───────────┐    ┌───────────┐
│  STEP 1   │    │  STEP 2   │    │  STEP 3   │    │  STEP 4   │    │  STEP 5   │
│           │    │           │    │           │    │           │    │           │
│  SCAN /   │───►│ MATERIAL  │───►│ FIND A    │───►│   LOG     │───►│  IMPACT   │
│  SEARCH   │    │ PASSPORT  │    │ RECYCLER  │    │    IT     │    │   DASH.   │
│           │    │           │    │           │    │           │    │           │
│ User types│    │ Shows Cu, │    │ Nearest   │    │ Recorded  │    │ kg saved, │
│ device or │    │ Au, Li %  │    │ CPCB-cert │    │ on ledger │    │ CO₂, INR  │
│ scans bar │    │ + score   │    │ on map    │    │           │    │ value     │
└───────────┘    └───────────┘    └───────────┘    └───────────┘    └───────────┘
```

### Example: iPhone 12 Passport

```json
{
  "product": "iPhone 12",
  "materials": [
    { "element": "Copper",    "percentage": 15.3, "recoverable": true },
    { "element": "Gold",      "percentage": 0.03, "recoverable": true },
    { "element": "Lithium",   "percentage": 2.0,  "recoverable": true },
    { "element": "Aluminium", "percentage": 24.8, "recoverable": true }
  ],
  "recyclability_score": 72,
  "estimated_recovery_value_inr": 420
}
```

---

##  Key Features

| Feature | Description |
|---|---|
|  **Product Search** | Search any device by name or scan barcode |
|  **Digital Passport** | Material breakdown, recyclability score, recovery value |
|  **Recycler Map** | CPCB-certified recyclers near you |
|  **Impact Dashboard** | Real-time: kg saved, CO₂ avoided, INR value |
|  **Verification Ledger** | Tamper-proof blockchain-inspired log |
|  **Mobile-First** | Works on India's 750M+ smartphones |

---

##  Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (ES6+) |
| Backend | Python Flask / Node.js |
| Database | Firebase / MongoDB Atlas (free tier) |
| Maps | Google Maps Embed API (free) |
| Hosting | Vercel / Netlify (free tier) |

> **Total Deployment Cost: ₹ 0.00**

---

##  Project Structure

```
avartana/
├── frontend/
│   ├── index.html              # Landing page
│   ├── passport.html           # Digital passport view
│   ├── map.html                # Recycler map
│   ├── dashboard.html          # Impact dashboard
│   ├── css/                    # Stylesheets
│   └── js/                     # JavaScript files
├── backend/
│   ├── app.py                  # Flask API server
│   ├── routes/                 # API endpoints
│   └── utils/                  # Helper functions
├── data/
│   ├── products.json           # 30+ device database
│   └── recyclers.json          # Recycler data
└── docs/
    ├── ProjectReport.pdf
    └── Presentation.pptx
```

---

##  Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/Aditi-963/AVARTANA.git
cd AVARTANA

# 2. Set up backend
cd backend
pip install -r requirements.txt
python app.py

# 3. Open frontend in browser
open frontend/index.html
```

---

##  UN & Policy Alignment

| Framework | Relevance |
|---|---|
| **UNTP (UNECE)** | Our verification ledger is UNTP-compliant |
| **UNITAR** | Primary data source for e-waste statistics |
| **UNEP Resolution 4/7** | Policy mandate for formal e-waste systems |
| **SDG 12, 9, 13** | Direct alignment with sustainable goals |

---

##  Impact Projections

### At 1% Adoption — 14M Indian Users Recycling 1 Device/Year

| Metric | Value |
|---|---|
| Devices recycled | **14 million** |
| Materials recovered | **~7,000 tonnes** |
| CO₂ avoided | **~35,000 tonnes** |
| Economic value | **~$7 million** |
| Informal workers protected | **50,000+** |

---

##  Roadmap

| Phase | Timeline | Deliverables |
|---|---|---|
| **Phase 1** | Current (Hackathon) | Web MVP, 30+ products, recycler map |
| **Phase 2** | 3–6 months | Mobile app, barcode scanning, PWA |
| **Phase 3** | 6–12 months | CPCB EPR integration, compliance certs |
| **Phase 4** | 12–18 months | AI value prediction, multi-language support |
| **Phase 5** | 18–36 months | Pan-India, UNITAR partnership, global DPP |

---

##  Competitors & Differentiation

### Global Competitors

| Company | Focus | Their Gap |
|---|---|---|
| Circularise (Netherlands) | Enterprise B2B DPP | No consumer interface, no India presence |
| Spherity (Germany) | Digital identity DPP | No recycling connection |
| Minespider (Germany) | Mineral sourcing | Upstream mining only |
| SuperCircle (USA) | Textile DPP | Not electronics-focused |
| SATO Corp (Japan) | Electronics DPP pilot | Pilot stage, not consumer-facing |

### Indian Competitors

| Company | Focus | Their Gap |
|---|---|---|
| Recykal (Hyderabad) | B2B EPR compliance | Corporate-facing, no consumer app |
| Attero / MetalMandi (Noida) | Scrap pricing platform | Price data only, no material passport |
| ASM Global | B2B waste tech | Not consumer-first |

### Full Comparison

| Parameter | AVARTANA | Circularise | Recykal | Attero | SATO |
|---|:---:|:---:|:---:|:---:|:---:|
| Consumer-Facing | ✅ | ❌ | ❌ | ❌ | ❌ |
| India Presence | ✅ | ❌ | ✅ | ✅ | ⚠️ |
| Free for Users | ✅ | ❌ | ❌ | ❌ | ❌ |
| Material Passport | ✅ | ✅ | ❌ | ❌ | ⚠️ |
| UNTP Aligned | ✅ | ❌ | ❌ | ❌ | ❌ |
| Last-Mile Connection | ✅ | ❌ | ❌ | ❌ | ❌ |

---

##  Why Avartana Wins

> *"Global players like Circularise build DPPs for enterprises. Indian players like Recykal build EPR compliance for brands. Avartana is the ONLY platform built for consumers — free, simple, and designed for 1.4 billion Indians."*

### The Three-Sided Gap — Who Solves What?

| Competitor | Consumer Side | Recycler Side | Producer Side |
|---|:---:|:---:|:---:|
| Recykal | ❌ | ⚠️ Limited | ✅ |
| Attero | ❌ | ⚠️ Price only | ❌ |
| Circularise | ❌ | ⚠️ Supply chain | ✅ |
| **AVARTANA** | ✅ | ✅ | ✅ |

### Our Competitive Edge

| Advantage | Why It Matters |
|---|---|
| **Consumer-First** | Built for 1.4B Indian consumers |
| **Brand-Agnostic** | Works for ANY device, ANY brand |
| **India-Built** | Designed for the Indian context |
| **UN-Aligned** | UNTP-compatible, globally scalable |
| **Zero Cost** | Free for end users |
| **Last-Mile** | Directly connects consumer to recycler |
| **Pure Electronics** | Specialized, not generic waste management |

---

##  References

1. [Global E-waste Monitor 2024](https://ewastemonitor.info/) — UNITAR & ITU
2. [E-Waste (Management) Rules, 2022](https://moef.gov.in/) — MoEFCC, India
3. [EU ESPR Regulation 2024/1781](https://eur-lex.europa.eu/) — European Commission
4. [UN Transparency Protocol (UNTP)](https://uncefact.github.io/spec-untp/) — UNECE
5. [SATO DPP PoC Report, 2023](https://www.sato-global.com/) — SATO Holdings
6. [Circularise](https://www.circularise.com/)
7. [Recykal](https://www.recykal.com/)
8. Attero MetalMandi — *The Economic Times*, Jan 2025

---

##  Team

**Team Avartana** — अवर्तन · *Cycle · Renewal · Return*

| Name |
|---|
| Aditi Rajput |
| Pranjal Gupta |

*Parul University Environment Hackathon 2026 · Circular Economy · SDG 12, 9, 13*

> *"Avartana is not just our team name. It is our thesis: that every material in every device deserves to return to the economy, not a landfill."*

---

##  License

MIT License — Copyright © 2026 Team Avartana

---

<p align="center">
  <strong>Built with purpose. Powered by data. Aligned with the planet.</strong>
  <br><br>
  <strong>Team Avartana · Parul University · 2026</strong>
  <br><br>
  <em> "Giving e-waste a second life, one device at a time."</em>
</p>
