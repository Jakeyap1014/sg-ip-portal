# SG IP Portal Enhancement Task

## Overview
Enhance two existing HTML files (grants.html and org-chart.html) for "The Little Company" SG IP holding company portal, then create an index.html landing page that links both.

## Files to Enhance

### 1. grants.html — Add Real Links + More Grants

**Add application/source links to EVERY existing grant card.** Add a clickable link button/badge at the bottom of each grant card.

#### Existing Grants — Add These Links:

| Grant | Application Link | Source/Info Link |
|-------|-----------------|------------------|
| Startup SG Tech POC/POV | ROI form: https://go.gov.sg/helloesg | https://www.enterprisesg.gov.sg/grow-your-business/partner-with-singapore/innovation-and-startups/join-startup-sg |
| Enterprise Innovation Scheme (EIS) | Claim via annual IRAS tax return | https://www.iras.gov.sg/schemes/disbursement-schemes/enterprise-innovation-scheme-(eis) and https://www.gobusiness.gov.sg/enterprise-innovation-scheme/ |
| Enterprise Development Grant (EDG) | Business Grants Portal: https://www.businessgrantsportal.gov.sg | https://www.enterprisesg.gov.sg/financial-support/enterprise-development-grant |
| EDG Co-Innovation Programme (CIP) | Via Eureka Network + EnterpriseSG | https://www.enterprisesg.gov.sg/financial-support/enterprise-development-grant |
| IAF-ICP (A*STAR) | RIE2025 closed; RIE2030 info expected Q1-Q2 2026 | https://www.a-star.edu.sg/Research/funding-opportunities/iaf-icp |
| Startup SG Founder | Apply through Accredited Mentor Partner (AMP) | https://www.enterprisesg.gov.sg/grow-your-business/partner-with-singapore/innovation-and-startups/join-startup-sg |
| RISC — Research & Innovation Scheme for Companies | Apply directly to EDB | https://www.edb.gov.sg/en/incentives-and-programmes/incentives-and-facilitation-programmes.html |
| IP Development Incentive (IDI) | Apply directly to EDB | https://invest.edb.gov.sg/find-government-support/intellectual-property-development-incentive |
| Refundable Investment Credit (RIC) | Apply via EDB or EnterpriseSG | https://www.enterprisesg.gov.sg/financial-support/refundable-investment-credit and https://www.iras.gov.sg/schemes/disbursement-schemes/refundable-investment-credit-(ric) |

#### NEW Grants to Add (as new grant cards):

1. **Market Readiness Assistance (MRA)** — High Fit
   - Admin: Enterprise Singapore
   - Up to S$100,000 per company per new market, 50% support (enhanced to 70% from 1 Apr 2026 for qualifying activities)
   - Covers overseas IP registration, market research, business matching, market setup
   - Available until EDGE launches H2 2026
   - Apply: Business Grants Portal https://www.businessgrantsportal.gov.sg
   - Source: https://www.enterprisesg.gov.sg/financial-support/market-readiness-assistance-grant
   - Category: collab (internationalisation)

2. **EDGE Grant (NEW — launching H2 2026)** — Medium Fit / Upcoming
   - Admin: Enterprise Singapore
   - Consolidated grant replacing MRA + EDG + PSG for simpler applications
   - Up to S$100,000 per year for eligible activities
   - Single simplified application process
   - Covers: productivity, capability development, internationalisation
   - Note: Not yet open — launching H2 2026
   - Source: Budget 2026 announcement
   - Category: collab

3. **Double Tax Deduction for Internationalisation (DTDi)** — High Fit
   - Admin: Enterprise Singapore / IRAS
   - 200% tax deduction on qualifying overseas expansion expenses (market development, IP registration overseas, trade fairs)
   - Budget 2026: cap increased to S$400K with expanded qualifying activities
   - Claim via IRAS in annual tax return
   - Apply: Business Grants Portal for pre-approval or claim automatically
   - Source: https://www.enterprisesg.gov.sg/financial-support/double-tax-deduction-for-internationalisation
   - Category: tax

4. **Startup Tax Exemption (SUTE)** — High Fit (first 3 years)
   - Admin: IRAS
   - First 3 YAs: 75% exemption on first S$100K chargeable income + 50% exemption on next S$100K
   - Automatic — no application needed, claim in tax return
   - ⚠️ NOT available if company is purely investment holding — needs operational substance
   - Category: tax

5. **CIT Rebate YA 2026** — Medium Fit
   - Admin: IRAS
   - 40% corporate income tax rebate, capped at S$30K
   - Plus S$1,500 cash grant if ≥ 1 local employee
   - Automatic in tax assessment
   - Category: tax

6. **Writing-Down Allowances (WDA) for IP** — High Fit
   - Admin: IRAS
   - Claim allowances on capital spent to acquire IP rights (patents, trademarks, copyrights, trade secrets, designs)
   - Write down over 5, 10, or 15 years (straight-line)
   - Effectively lets you deduct cost of transferring IP into SG entity
   - Category: tax

#### Also Add These Resources (not grants, but important — add a "Resources" section at the bottom):

- **IPOS IP Clinics** — Free 45-min consultation on IP matters: https://www.ipos.gov.sg/eservices/ip-clinics/
- **GoBusiness IP Grow** — One-stop marketplace for IA/IP services: https://www.gobusiness.gov.sg/ip-grow/
- **IPOS IP2SG Portal** — File trademarks, patents, designs: https://www.ipos.gov.sg/
- **ACRA BizFile+** — Company incorporation: https://www.bizfile.gov.sg/
- **Business Grants Portal** — Apply for EDG, MRA, and other grants: https://www.businessgrantsportal.gov.sg

#### Update the hero stats:
- Change "7 Grant programmes identified" to match the new total count
- Update S$1.2M if the max has changed

### 2. org-chart.html — Verify & Enhance

The org chart shows:
- Parent: The Little Company (Parent HoldCo)
- Children: SG IP Co (NEW), SG Ops Co, AU Ops Co, US Ops Co, UK Ops Co, CA Ops Co, NZ Ops Co

**Verification notes:**
- This structure is correct for a multinational furniture/e-commerce group with SG IP HoldCo
- The parent "The Little Company" is the umbrella holding company
- SG IP Co is the new entity being set up
- All operating companies (AU, US, UK, CA, NZ) match Lifely's actual operations (they sell in all these markets)
- SG Ops Co is the existing Singapore operating entity

**Enhancements to make:**
1. Add IP flow arrows/indicators showing: IP flows FROM SG IP Co TO each Ops Co via licensing agreements
2. Add a "Key Relationships" section below the org chart showing:
   - SG IP Co → licenses IP to all Ops Cos
   - Ops Cos → pay royalties to SG IP Co
   - This creates deductible expenses in AU/US/UK/CA/NZ while income taxed at 5-10% in SG
3. Add an "Important Compliance" section:
   - Transfer pricing: royalty rates must be arm's-length (IRAS scrutinizes)
   - Economic substance: post-BEPS 2.0, need real people/activities in SG
   - AU CFC rules: Australia's Controlled Foreign Company rules may tax SG income back in AU
   - Pillar Two (from FY2027): 15% global minimum effective tax rate for groups with €750M+ revenue
4. Update the "March 2026" badge to "April 2026"

### 3. Create index.html — Landing Page

Create a clean landing page that links to both grants.html and org-chart.html. Same design language (sage/cream palette, DM Sans + DM Serif Display). Show:
- "The Little Company / IP" branding
- Brief intro paragraph
- Two cards linking to each document
- Confidential / Internal Use Only footer

## Design Rules
- Keep the EXACT same CSS variables, fonts, and design language as the originals
- Same warm sage/cream palette
- For link buttons on grant cards, use a subtle sage-colored pill button style
- All external links should open in new tab (target="_blank" rel="noopener")
- Keep the filter functionality working with new grants (assign correct data-cat)
- Mobile responsive (the originals already have some responsive design)

## Output
- Enhanced grants.html
- Enhanced org-chart.html
- New index.html
- All three files in /home/lifely-agent/.openclaw/workspace/projects/sg-ip-portal/
