# p4a-oceania-cinema

> 🤝🔷 **A Luke × Claude build.** Created by Luke Nathan Hayes (`auraofintelligence`) and Claude — Fable 5, July 2026. Not a Codex build. This is the cinematic rebuild fork of [p4a-oceania-expansion-lab](https://github.com/auraofintelligence/p4a-oceania-expansion-lab); the original Codex-era repo stays untouched upstream.

Static multi-page idea lab for exploring how the Purple Party for Australia civic workbench could be translated across Oceania.

Current public status: open civic prototype. Party registration, campaigning, legal machinery, financial products, medical programmes and adopted policy would each need their own public record, review path and authority.

## Navigation System

Every page shares a compact header plus an Index button that opens a full-screen searchable index of all rooms. Navigation — index overlay, breadcrumbs and footer explore-columns — is generated from one data file: `assets/site-nav.js`. To surface a new page everywhere, add one entry to `SECTIONS` there. `tools/apply-chrome.mjs` is the re-runnable stamper for the shared header shell. The site self-hosts two variable fonts in `assets/fonts/` (Archivo and JetBrains Mono) so it stays offline-first with no CDN calls.

## Site Shape

- `index.html` - short public doorway
- `pages/gen-xyza.html` - youth and self-sovereign participant doorway
- `pages/progression.html` - Australia seed to Oceania thought pathway
- `pages/oceania-map.html` - sourced atlas, hover regions and translation questions
- `pages/pulse.html` - live election clocks, due windows and electoral-system differences, data-driven from `assets/oceania-pulse-data.js`
- `pages/shared-currents.html` - the region's shared pressures and existing regional bodies, held as translation questions
- `pages/c-hours.html` - Community-Hour / regenerative asset concept
- `pages/compute.html` - decentralised civic compute shelf
- `pages/surge.html` - Oceania 2028-2032 moonshot shelf
- `pages/compliance.html` - trust stack, receipts and public proof
- `pages/source-notes.html` - source archive and research lanes
- `pages/site-map.html` - full link map
- `content/project/` - plain markdown notes for future agents and humans

## Sources Used

- P4A public civic workbench: [site](https://auraofintelligence.github.io/p4a-xyz-cinema/) and [repo](https://github.com/auraofintelligence/p4a-xyz-cinema)
- C-Hour legislation and national security memo
- Decentralised Compute for Australian Communities
- Australia's Olympic Space Gambit
- GAJRA Earth-Space-AI Summit
- Local Government Funding Inquiry Submission
- Queensland Olympic Earn-to-Heal Pilot
- Queensland's Heart-First AI Surge Plan
- Brisbane Global Summit Research Plan
- Strategic wellness, food waste, health-tech co-operative, de-slop and peaceful space gambit source notes

The source packet uses US English in places and often speaks in strategic-memo voltage. This site translates the public copy into Australian English and routes serious claims through receipts, review paths and evidence gates.

## Preview

Open `index.html` in a browser.

## Status

Open civic prototype. Legal, electoral, financial, medical, procurement, infrastructure and political claims gain force through fresh source checking, local authority and human review.
