<div align="center">

<br/>

```
 █████╗ ██╗   ██╗ █████╗ ██████╗ ████████╗ █████╗ ███╗   ██╗ █████╗
██╔══██╗██║   ██║██╔══██╗██╔══██╗╚══██╔══╝██╔══██╗████╗  ██║██╔══██╗
███████║██║   ██║███████║██████╔╝   ██║   ███████║██╔██╗ ██║███████║
██╔══██║╚██╗ ██╔╝██╔══██║██╔══██╗   ██║   ██╔══██║██║╚██╗██║██╔══██║
██║  ██║ ╚████╔╝ ██║  ██║██║  ██║   ██║   ██║  ██║██║ ╚████║██║  ██║
╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝
```

### *अवर्तन — Sanskrit for "Cycle"*

**Digital Product Passport for Electronics**

*Giving e-waste a second life, one device at a time.*

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![SDG 12](https://img.shields.io/badge/SDG-12%20Responsible%20Consumption-1B5E20)](https://sdgs.un.org/goals/goal12)
[![SDG 9](https://img.shields.io/badge/SDG-9%20Innovation-0D47A1)](https://sdgs.un.org/goals/goal9)
[![SDG 13](https://img.shields.io/badge/SDG-13%20Climate%20Action-2E7D32)](https://sdgs.un.org/goals/goal13)
[![UNTP](https://img.shields.io/badge/Aligned-UN%20Transparency%20Protocol-orange)](https://uncefact.github.io/spec-untp/)
[![Hackathon](https://img.shields.io/badge/Parul%20University-Environment%20Hackathon%202026-E65100)](https://paruluniversity.ac.in)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen)]()

<br/>

> **"Every year, 62 million tonnes of electronic waste is dumped or burned —**  
> **losing $62 billion in gold, copper, and lithium.**  
> **We built the infrastructure to stop that."**

<br/>

</div>

---

## 📋 Table of Contents

- [The Problem](#-the-problem)
- [Why It Matters for India](#-why-it-matters-for-india)
- [Our Solution](#-our-solution)
- [How It Works](#-how-it-works)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Material Database](#-material-database)
- [UN & Policy Alignment](#-un--policy-alignment)
- [Impact Projections](#-impact-projections)
- [Roadmap](#-roadmap)
- [Global Context](#-global-context)
- [References & Data Sources](#-references--data-sources)
- [Team](#-team)
- [License](#-license)

---

## 🌍 The Problem

<table>
<tr>
<td width="50%">

### Global E-Waste Crisis

The world generated a record **62 million tonnes** of electronic waste in 2022 — enough to fill **1.55 million 40-tonne trucks** placed bumper-to-bumper around the equator.

| Metric | Value |
|--------|-------|
| E-waste generated (2022) | **62 million tonnes** |
| Annual growth rate | **2.6M tonnes/year** |
| Projected by 2030 | **82 million tonnes** |
| Formally recycled | **Only 22.3%** |
| Lost annually in metals | **USD $62 billion** |
| Rare earth supply from recycling | **Less than 1%** |

*Source: Global E-waste Monitor 2024, UNITAR & ITU*

</td>
<td width="50%">

### What Happens to the 77.7%?

The vast majority of e-waste ends up:

- 🔥 **Burned** by informal recyclers — releasing dioxins, furans, and heavy metals
- 🏚️ **Dumped** in landfills — contaminating groundwater with mercury, lead, and cadmium
- 🚢 **Illegally exported** to developing nations under the guise of "second-hand goods"
- 🗄️ **Hoarded** in drawers and closets — never recycled at all

Workers at informal recycling sites — often children — suffer elevated rates of respiratory disease, neurological damage, and cancer. Communities near dumping sites face generational health crises.

</td>
</tr>
</table>

### The Core Information Gap

The reason recycling rates are so low isn't a lack of desire — it's a **lack of information infrastructure**:

```
Consumer          ──?──>   Recycler
(has old device)           (needs material data)

Producer          ──?──>   Regulator  
(must prove EPR)           (needs verified records)

Device            ──?──>   Circular Economy
(contains gold,            (needs material passport)
 copper, lithium)
```

**No unified digital system exists** to tell a consumer what's inside their device, where to take it, and to verify that recycling actually happened.

That is exactly what this project solves.

---

## 🇮🇳 Why It Matters for India

India is the world's **third-largest generator of e-waste** — and the stakes are particularly high:

```
┌─────────────────────────────────────────────────────────────────┐
│                    INDIA E-WASTE SNAPSHOT                       │
├───────────────────────────┬─────────────────────────────────────┤
│ Annual e-waste generation │ 6.19 million tonnes                 │
│ Annual growth rate        │ 16.9% per year                      │
│ Global rank               │ 3rd largest generator               │
│ Critical mineral imports  │ 100% dependent (lithium, cobalt)    │
│ EPR recycling mandate     │ 70% by 2026–27 (E-Waste Rules 2022) │
│ Market size (2024)        │ USD 4.40 billion                    │
│ Market size (2034 proj.)  │ USD 15.29 billion (13.9% CAGR)      │
└───────────────────────────┴─────────────────────────────────────┘
```

India imports 100% of its critical minerals — lithium for batteries, cobalt for electronics, rare earths for magnets — yet buries the same materials in 6 million tonnes of e-waste every year. **The solution to India's mineral import dependency is literally under our desks, in our drawers, and in our old phones.**

The E-Waste (Management) Rules, 2022 mandate that producers achieve **70–80% recycling targets by 2026–2027**. But without a digital passport system, compliance verification remains manual, fragmented, and easily gamed.

---

## 💡 Our Solution

**Avartana** is a **Digital Product Passport (DPP) platform** for electronics — a web-based application that gives every electronic device a digital identity containing:

- Its **complete material composition** (which metals, at what percentages)
- Its **recyclability score** and estimated recovery value  
- **Certified recyclers near the user** who can process it properly
- A **tamper-evident verification ledger** proving recycling happened

Think of it as a **passport for your phone** — just as a human passport contains your identity, travel history, and verified records, a device passport contains its material identity, lifecycle history, and verified recycling records.

### The Three-Sided Bridge

```
        ┌────────────────────────────────────────┐
        │              AVARTANA                  │
        │      Digital Product Passport          │
        └────────────────────────────────────────┘
               /          |           \
              /           |            \
     ┌────────────┐ ┌───────────┐ ┌──────────────┐
     │  CONSUMER  │ │ RECYCLER  │ │   PRODUCER   │
     │            │ │           │ │              │
     │ Knows what │ │ Gets mat. │ │ Proves EPR   │
     │ to recycle │ │ data in   │ │ compliance   │
     │ and where  │ │ advance   │ │ digitally    │
     └────────────┘ └───────────┘ └──────────────┘
```

---

## ⚙️ How It Works

The platform follows a simple 5-step flow:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   STEP 1          STEP 2          STEP 3          STEP 4     STEP 5    │
│                                                                         │
│  [SCAN /]  ──►  [MATERIAL]  ──►  [FIND A ]  ──►  [LOG  ] ──► [IMPACT] │
│  [SEARCH]       [PASSPORT]       [RECYCLER]       [IT   ]     [DASH. ] │
│                                                                         │
│  User types    System shows    Nearest CPCB-   Transaction   Dashboard │
│  device name   copper, gold,   certified       recorded on   updates:  │
│  or scans      lithium %,      recyclers on    immutable     kg saved, │
│  barcode       recyclability   interactive     ledger        CO₂, INR  │
│                score + value   map                                      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### Example: Scanning an iPhone 12

```json
{
  "product": "iPhone 12",
  "manufacturer": "Apple Inc.",
  "category": "Smartphone",
  "passport_id": "AVT-2026-IP12-001",
  "materials": [
    { "element": "Aluminium",  "percentage": 24.8, "recoverable": true,  "value_usd_per_kg": 2.10 },
    { "element": "Copper",     "percentage": 15.3, "recoverable": true,  "value_usd_per_kg": 9.20 },
    { "element": "Cobalt",     "percentage": 5.1,  "recoverable": true,  "value_usd_per_kg": 33.00 },
    { "element": "Lithium",    "percentage": 2.0,  "recoverable": true,  "value_usd_per_kg": 18.00 },
    { "element": "Gold",       "percentage": 0.03, "recoverable": true,  "value_usd_per_kg": 62000 },
    { "element": "Palladium",  "percentage": 0.01, "recoverable": true,  "value_usd_per_kg": 49000 },
    { "element": "Plastic",    "percentage": 32.0, "recoverable": false, "value_usd_per_kg": 0.10 },
    { "element": "Glass",      "percentage": 14.0, "recoverable": false, "value_usd_per_kg": 0.05 }
  ],
  "recyclability_score": 72,
  "estimated_recovery_value_inr": 420,
  "nearest_recyclers": ["GreenTech E-waste Pvt. Ltd.", "Attero Recycling - Delhi NCR"],
  "sdg_tags": ["SDG-12", "SDG-13"]
}
```

---

## ✨ Key Features

### 🔍 Product Search & Barcode Scanner
Search any device by name or scan its barcode. The system queries a curated material database sourced from UNITAR, Apple Material Reports, and iFixit teardowns.

### 📄 Digital Material Passport
Every device gets a passport card showing:
- Element-by-element material breakdown
- Recyclability score (0–100)
- Estimated recovery value in INR
- Hazardous substances flagged (RoHS compliance data)
- SDG impact tags

### 🗺️ Certified Recycler Map
Google Maps integration showing CPCB-certified e-waste recyclers near the user, filterable by device category and distance.

### 📊 Real-Time Impact Dashboard
Tracks cumulative impact across all users:
- **Materials recovered** (kg by element)
- **CO₂ emissions avoided** (kg, using UNITAR coefficients)
- **Economic value unlocked** (INR)
- **Devices diverted from landfill** (count)

### 🔐 Verification Ledger
Every confirmed recycling transaction is appended to an immutable log — blockchain-inspired architecture that can integrate with India's CPCB EPR portal and the UN Transparency Protocol (UNTP).

### 📱 Mobile-First Design
Responsive interface designed for India's 750M+ smartphone users. No app download required.

---

## 🛠️ Tech Stack

```
┌────────────────────────────────────────────────────────────┐
│                       FRONTEND                             │
│         HTML5 · CSS3 · Vanilla JavaScript (ES6+)           │
│                  Mobile-first · PWA-ready                  │
└────────────────────────────────────────────────────────────┘
                            │
┌────────────────────────────────────────────────────────────┐
│                        BACKEND                             │
│                   Python Flask / Node.js                   │
│              REST API · JSON responses · CORS              │
└────────────────────────────────────────────────────────────┘
                            │
┌───────────────┬───────────────────────┬────────────────────┐
│   DATABASE    │         MAPS          │    VERIFICATION    │
│               │                       │                    │
│  Firebase /   │  Google Maps Embed    │  Blockchain-       │
│  MongoDB      │  API (free tier)      │  inspired JSON     │
│  Atlas        │                       │  ledger            │
│  (free tier)  │                       │                    │
└───────────────┴───────────────────────┴────────────────────┘
                            │
┌────────────────────────────────────────────────────────────┐
│                       HOSTING                              │
│              Vercel / Netlify (free tier)                  │
│               Zero infrastructure cost                     │
└────────────────────────────────────────────────────────────┘

Total Deployment Cost: ₹ 0
```

### Dependencies

```json
{
  "runtime": "Node.js 18+  OR  Python 3.10+",
  "frontend_framework": "None (Vanilla JS) — React optional",
  "maps": "Google Maps Embed API (free, no key required for basic embed)",
  "database": "Firebase Realtime Database (Spark plan — free)",
  "barcode_scanning": "HTML5 Canvas API or ZXing-js (open source)",
  "hosting": "Vercel or Netlify (Hobby/Free tier)"
}
```

---

## 📁 Project Structure

```
avartana/
│
├── 📄 README.md                    ← You are here
├── 📄 LICENSE
├── 📄 .gitignore
│
├── 📂 frontend/
│   ├── index.html                  ← Landing page + search interface
│   ├── passport.html               ← Digital passport display page
│   ├── map.html                    ← Recycler locator map
│   ├── dashboard.html              ← Impact dashboard
│   ├── ledger.html                 ← Verification ledger viewer
│   │
│   ├── 📂 css/
│   │   ├── main.css                ← Core styles + CSS variables
│   │   ├── passport.css            ← Passport card design
│   │   └── dashboard.css           ← Charts and metrics
│   │
│   └── 📂 js/
│       ├── search.js               ← Product lookup logic
│       ├── passport.js             ← Passport rendering
│       ├── map.js                  ← Recycler map integration
│       ├── dashboard.js            ← Impact calculations
│       └── ledger.js               ← Transaction log logic
│
├── 📂 backend/
│   ├── app.py                      ← Flask API server
│   ├── requirements.txt
│   │
│   ├── 📂 routes/
│   │   ├── products.py             ← /api/products endpoints
│   │   ├── recyclers.py            ← /api/recyclers endpoints
│   │   └── ledger.py               ← /api/ledger endpoints
│   │
│   └── 📂 utils/
│       ├── impact_calculator.py    ← CO₂ + value calculations
│       └── validator.py            ← Input validation
│
├── 📂 data/
│   ├── products.json               ← Material database (20+ devices)
│   ├── recyclers.json              ← Certified recycler mock data
│   └── impact_coefficients.json   ← UNITAR impact factors
│
└── 📂 docs/
    ├── Avartana_ProjectReport.pdf  ← Hackathon project report
    ├── Avartana_Presentation.pptx  ← Pitch deck
    └── api_reference.md            ← API documentation
```

---

## 🚀 Getting Started

### Prerequisites

```bash
# Option A: Python backend
python --version   # 3.10+
pip --version

# Option B: Node.js backend  
node --version     # 18+
npm --version
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/avartana.git
cd avartana

# 2. Install backend dependencies
pip install -r backend/requirements.txt
# OR for Node.js:
npm install

# 3. Set up environment variables
cp .env.example .env
# Edit .env with your Firebase config (optional for local dev)

# 4. Start the backend server
cd backend
python app.py
# Server starts at http://localhost:5000

# 5. Open the frontend
# Simply open frontend/index.html in your browser
# OR serve it:
npx serve frontend/
```

### Quick Demo (No Setup Required)

To see the core functionality immediately:

```bash
# Just open index.html directly in your browser
# The product database (data/products.json) works without a server
# Maps embed without an API key
# Ledger runs on localStorage for local demo
open frontend/index.html
```

---

## 🗃️ Material Database

The material database covers **20+ device categories** with element-level composition data, sourced from:

- **UNITAR Global E-waste Monitor 2024**
- **Apple Material Reports** (published annually per device)
- **iFixit Teardown Database** (open-source)
- **Samsung Eco-Reports**
- **OpenLCA material datasets**

### Covered Device Categories

| Category | Example Products | Key Recoverable Materials |
|----------|-----------------|--------------------------|
| Smartphones | iPhone, Samsung Galaxy, OnePlus | Gold, Palladium, Cobalt, Copper |
| Laptops | Dell, HP, Lenovo, MacBook | Aluminium, Copper, Lithium, Gold |
| Tablets | iPad, Samsung Tab, Kindle | Lithium, Aluminium, Copper |
| Smart Speakers | Echo, HomePod, Google Nest | Copper, Neodymium, Plastic |
| Smartwatches | Apple Watch, Fitbit | Titanium, Gold, Lithium |
| Televisions | LED/OLED TVs | Indium, Copper, Rare Earths |
| Washing Machines | All brands | Copper (motor), Steel, Aluminium |
| Refrigerators | All brands | Copper, Steel, Refrigerant |
| Printers | Inkjet, Laser | Copper, Plastic, Rare Earths |
| Routers/Modems | All brands | Copper, PCB metals |
| Power Banks | All brands | Lithium, Copper, Cobalt |
| Earphones/Headphones | AirPods, Sony, JBL | Rare Earths (magnets), Copper |

### Database Schema

```json
{
  "product_id": "string — unique identifier",
  "product_name": "string",
  "manufacturer": "string",
  "category": "string",
  "year_range": "string — e.g. '2020-2023'",
  "weight_grams": "number",
  "materials": [
    {
      "element": "string",
      "percentage": "number",
      "mass_grams": "number",
      "recoverable": "boolean",
      "hazardous": "boolean",
      "value_usd_per_kg": "number",
      "recovery_method": "string"
    }
  ],
  "recyclability_score": "number (0-100)",
  "rohs_compliant": "boolean",
  "recycler_categories": ["array of strings"],
  "data_source": "string",
  "last_updated": "ISO date string"
}
```

---

## 🌐 UN & Policy Alignment

### United Nations Frameworks

| Framework | Relevance |
|-----------|-----------|
| **UN Transparency Protocol (UNTP)** | Our verification ledger is designed to be UNTP-compliant, enabling global DPP interoperability |
| **UNITAR Global E-waste Monitor** | Primary data source for all statistics and impact coefficients |
| **UNEP Resolution 4/7** | Policy mandate underpinning the need for formal e-waste systems |
| **Basel Convention (2019 Amendment)** | Restricts illegal e-waste export; our system supports formal channelling |

### Sustainable Development Goals

```
SDG 12 ── Responsible Consumption & Production
          Closes the material loop for electronics at consumer level

SDG 9  ── Industry, Innovation & Infrastructure  
          Builds digital infrastructure for a formalised circular economy

SDG 13 ── Climate Action
          Reduces toxic e-waste burning and GHG emissions

SDG 3  ── Good Health & Well-being
          Protects informal recyclers from toxic material exposure

SDG 8  ── Decent Work & Economic Growth
          Formalises informal recyclers with better data and tools
```

### India Regulatory Alignment

| Regulation | Requirement | How Avartana Helps |
|------------|-------------|-------------------|
| E-Waste (Management) Rules 2022 | 70% EPR recycling target by 2026–27 | Verified recycling ledger enables producer compliance proof |
| CPCB EPR Portal | Digital registration of all recyclers | Platform designed for CPCB API integration |
| Environmental Compensation | Penalties for non-compliance | Our certificates reduce non-compliance risk |

### EU Alignment (For Global Scalability)

The EU's **Ecodesign for Sustainable Products Regulation (ESPR) 2024/1781** — the world's first legally binding DPP mandate — entered into force July 2024. Avartana is architected to be **ESPR-compatible**, enabling cross-border passport interoperability for devices moving between India and EU markets.

---

## 📈 Impact Projections

### Conservative Scenario: 1% Adoption

*Assumes 1% of Indian smartphone users recycle 1 device per year via the platform:*

| Impact Metric | Annual Value |
|---------------|-------------|
| Devices formally recycled | **14 million** |
| Materials recovered | **~7,000 tonnes** (Cu, Au, Li, Co) |
| CO₂ emissions avoided | **~35,000 tonnes** |
| Economic value unlocked | **~USD 7 million** in recovered metals |
| Informal workers protected | **50,000+** shifted to safer channels |

### Impact Calculation Method

```python
# Impact calculation per device recycled
# Based on UNITAR coefficients

def calculate_impact(device_weight_kg, material_composition):
    materials_recovered_kg = sum(
        device_weight_kg * m["percentage"] / 100
        for m in material_composition if m["recoverable"]
    )
    
    # UNITAR coefficient: 5 kg CO₂ avoided per kg formally recycled
    co2_avoided_kg = materials_recovered_kg * 5.0
    
    economic_value_usd = sum(
        device_weight_kg * m["percentage"] / 100 * m["value_usd_per_kg"]
        for m in material_composition if m["recoverable"]
    )
    
    return {
        "materials_recovered_kg": materials_recovered_kg,
        "co2_avoided_kg": co2_avoided_kg,
        "economic_value_usd": economic_value_usd
    }
```

---

## 🗺️ Roadmap

```
PHASE 1 — MVP (Current)                     [Hackathon Prototype]
├── ✅ Product search & material passport
├── ✅ Material database: 20 device types
├── ✅ Recycler map (mock CPCB data)
├── ✅ Impact dashboard
└── ✅ Verification ledger (localStorage)

PHASE 2 — Mobile & Real Data               [3–6 months post-hackathon]
├── 📱 Native barcode scanning (ZXing / Google Vision API)
├── 🗄️ Live CPCB recycler database integration
├── 🌐 PWA for offline-first use in low-connectivity areas
└── 🔔 User recycling reminders and history

PHASE 3 — Compliance Infrastructure        [6–12 months]
├── 🏛️ CPCB EPR Portal API integration
├── 📜 Automated compliance certificate generation for producers
├── 🔗 UNTP-standard DPP export format
└── 🤝 Recycler onboarding and verification workflow

PHASE 4 — Intelligence Layer               [12–18 months]
├── 🤖 AI-powered material value prediction (live metal prices)
├── 📊 Predictive recycler matching by device category
├── 🌍 Multi-language support (Hindi, Tamil, Bengali, Telugu)
└── 🏭 B2B API for producers to embed passports in product QR codes

PHASE 5 — National & Global Scale          [18–36 months]
├── 🇮🇳 Partnership with UNITAR SCYCLE Programme
├── 🏛️ MoEFCC policy integration
├── 🌐 ESPR-compatible cross-border DPP interoperability
└── 📡 IoT integration for smart device self-reporting
```

---

## 🌐 Global Context

### Who's Already Doing This (And What's Different)

| Initiative | What They Do | What's Different About Avartana |
|-----------|-------------|--------------------------------|
| **Circularise** (Netherlands) | Enterprise B2B blockchain DPP for industrial supply chains | Enterprise-only; no consumer interface; no India presence |
| **SuperCircle** (USA) | Digital twin for textiles — $24M Series A | Textile-focused; not electronics |
| **SATO Corp** (Japan) | DPP pilot for electronics — proven 40%+ efficiency gain | Pilot stage; not consumer-facing |
| **Attero MetalMandi** | India's largest e-waste recycler — B2B scrap price platform | Price data only; no material passport |
| **Recykal** | Corporate EPR compliance platform | Corporate-facing; not consumer-first |
| **Apple Material Reports** | Brand-specific device composition data | Single-brand; not interoperable |

**Avartana's unique position:** Consumer-first · Brand-agnostic · India-built · UN-aligned · ₹0 cost to user

### The DPP Market Opportunity

```
Global Digital Product Passport Market:
├── 2024: ~USD 0.8 billion
├── 2033: USD 3.0 billion (projected)
└── CAGR: 35%

India E-Waste Management Market:
├── 2024: USD 4.40 billion
├── 2034: USD 15.29 billion (projected)
└── CAGR: 13.9%
```

---

## 📚 References & Data Sources

All statistics used in this project are sourced from verifiable published reports:

1. **Global E-waste Monitor 2024** — UNITAR & ITU. [globalewaste.org](https://globalewaste.org)
2. **E-Waste (Management) Rules, 2022** — Ministry of Environment, Forest & Climate Change (MoEFCC), Government of India.
3. **Ecodesign for Sustainable Products Regulation (EU) 2024/1781** — European Commission, July 2024.
4. **Global Waste Management Outlook 2024** — UNEP & ISWA.
5. **Global Transboundary E-waste Flows Monitor 2022** — UNITAR & UNU.
6. **SATO DPP Proof of Concept Report, 2023** — SATO Holdings Corporation.
7. **India E-Waste Market Report 2025–2034** — Market.us, 2025.
8. **Apple Material Composition Reports** — Apple Inc. (published annually per device model).
9. **iFixit Device Teardown Database** — iFixit.com (open source).
10. **UN Transparency Protocol (UNTP) Specification** — UNECE/UNCEFACT. [uncefact.github.io/spec-untp](https://uncefact.github.io/spec-untp/)

---

## 👥 Team

<div align="center">

### **Team Avartana**
*अवर्तन — Cycle · Renewal · Return*

**Parul University Environment Hackathon 2026**  
Theme: *"Designing Sustainable Futures in a Digital Age"*  
Domain: Circular Economy

---

*"Avartana is not just our team name.*  
*It is our thesis: that every material in every device*  
*deserves to return to the economy, not a landfill."*

</div>

---

## 📄 License

```
MIT License

Copyright (c) 2026 Team Avartana

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

**Built with purpose. Powered by data. Aligned with the planet.**

*Team Avartana · Parul University · 2026*

[![SDG 12](https://img.shields.io/badge/SDG-12-1B5E20)](https://sdgs.un.org/goals/goal12)
[![SDG 9](https://img.shields.io/badge/SDG-9-0D47A1)](https://sdgs.un.org/goals/goal9)
[![SDG 13](https://img.shields.io/badge/SDG-13-2E7D32)](https://sdgs.un.org/goals/goal13)

*"Giving e-waste a second life, one device at a time."*

</div>
