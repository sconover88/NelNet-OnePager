# Nelnet AI-First Delivery Lifecycle — 1 Pager Project Context

## What This Is
A single-page HTML document (index.html) designed as a polished, visual one-pager for Nelnet (NDS IT Delivery). It responds to their RFI for Workstream 3 — an AI-First Delivery Lifecycle. The page is deployed to Vercel via GitHub and can be exported to PDF via browser print (⌘+P → Save as PDF, margins: None, background graphics: on).

## Client: Nelnet
Nelnet is a financial services company focused on student financial aid and loan services. They operate in regulated environments (Federal, consumer-financial) and use the Nelnet Agile Methodology (NAM) with a six-stage SDLC structure.

## Who We Are
Slalom — delivering an AI-First Delivery Lifecycle (AIDLC) platform that configures to Nelnet's existing SDLC rather than replacing it.

## What Nelnet Asked For in the 1 Pager
1. Our core approach to AI-first delivery lifecycle design
2. Sample artifacts or representative outputs
3. Recommended path forward — how we would approach implementation and adoption, and why
4. What we need from NDS IT Delivery to succeed

## Design Principles
- Feels like the front page of a newspaper: headlines, sections, scannable
- Professional and visually polished — not a wall of text
- Sized to fit on a single letter-size page when exported to PDF
- Uses SVG icons for the "What This Means for Nelnet" section

## Brand / Colors
- Primary: #0C62FB (bright blue)
- Accent 1: #002faf (dark navy — used for header, footer, table headers)
- Accent 2: #1be1f2 (cyan — used for tagline, chevron endpoint)
- Accent 3: #ff4d5f (coral/red)
- Accent 4: #c789ff (purple)
- Accent 5: #deff4d (lime green)
- Font: Avenir LT Pro (with fallbacks to Avenir Next, Avenir, system sans-serif)

## Key Metrics (from the RFI)
- **<1 Day** requirements cycle time (previously weeks)
- **60% reduction** in refactoring time (from legacy modernization client)
- **100%** requirements-to-test traceability

## Page Structure (current)
1. **Header** — "AI-First Delivery Lifecycle" + tagline "AI executes. People decide. Context compounds." in cyan
2. **Metrics Banner** — 3 stats in a row
3. **Two-column row** — "Our Core Approach" (left) | "What We Need from NDS IT Delivery" + "The Compounding Advantage" (right)
4. **Full-width** — "Representative Outputs" table
5. **Full-width** — "What This Means for Nelnet" (5 icon cards with SVGs)
6. **Full-width** — "Recommended Path Forward" (chevron arrows: Setup → Pilot → Scale)
7. **Footer** — currently hidden/commented out

## Reference Documents
- `one-pager.md` — AI-generated draft content (reference only, not copied verbatim)
- `rfi.md` — The full RFI response submitted to Nelnet (source of truth for claims and metrics)

## SVG Icons Used
- `time.svg` — Faster Time to Market
- `strong.svg` — Stronger Governance
- `compliance.svg` — Compliance Built In
- `compounds.svg` — Compounds Over Time
- `handshake.svg` — Nelnet Owns It

## Important Notes
- Client quotes were removed (may be added back with real quotes later)
- Footer is commented out in the HTML (may be restored later)
- The page must fit on 1 printed page — be careful adding content without removing something else
- All metrics must be traceable back to the RFI document — don't invent numbers
