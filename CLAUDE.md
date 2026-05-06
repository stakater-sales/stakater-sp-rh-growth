# SCO Hyperscaler Engine — Project Rules

## Working Style

- Prefer surgical changes with limited side-effects. Touch only what the task requires; leave unrelated code, layouts, and copy alone. No opportunistic refactors or cleanups bundled in.

## Slide Design

### Accent Rule
Only accent (`.highlight`) the **core concept** each slide is introducing — the one thing the audience should remember from that slide.

- Accent the key noun or phrase, not filler words ("Wins", "anything", "Customers")
- Do not use `<strong>` for emphasis in slides — use `.highlight` or nothing
- One accent per slide title is the default; two is acceptable if both are core concepts
- Body text and subtitles should generally remain unaccented unless the concept is the slide's primary takeaway

### Presentation Style
- Minimal text per slide — short phrases, not sentences
- Use visual structure (cards, pills, flow diagrams) over bullet lists
- Alternate between `section-light` and default backgrounds
- Content should breathe — don't pack slides tight; favor whitespace and spacing
- Keep layouts balanced — if two columns, ensure equal visual weight
- Avoid abbreviations unless already introduced — write out product names

### Visual Language
- Brand color: `--primary` (#EA7845 for customer deck, #E00000 for Red Hat deck)
- Three-tier visual hierarchy: neutral (white/light border) → accented (primary border, tinted bg) → strong (gradient bg)
- Arrows and flow indicators for showing relationships between concepts

## Speaker Notes Style

### Voice
- Conversational and direct — written as spoken words, not essay prose
- Confident but not salesy — state facts, don't oversell
- Short declarative sentences — no filler, no hedging
- Use `>` blockquotes for what to actually say; plain text for stage directions

### Structure per slide
- Open with the key framing line
- Walk through the content naturally (don't narrate the slide verbatim)
- Land with a punchy relationship or takeaway
- Stage directions are brief and practical ("Pause. Let that land.", "Keep it short.", "Don't fake it.")

### Terminology
- Use "Cloud Orchestrator" in customer-facing notes, not "SCO"
- Use "SCO" only in internal/shorthand contexts
- Don't spoil later slides — each note should set up without revealing what comes next

## Design system

**Colours:**
- Primary Orange: `#FF5623` (CTAs, highlights, accents, icons)
- Secondary Orange: `#CC451C` (hover states)
- Primary Purple: `#1A0D32` (dark sections, headings)
- Secondary Purple: `#0A0614` (deepest dark sections)
- BG Main: `#F5F5F5`
- BG Alt: `#E8E8E8`
- BG Card: `#D1CFD6`
- Border: `#D9D9D9`
- Muted text: `#5a5668`

**Typography (Plus Jakarta Sans):**
- H1: 56px Bold (mobile: 32px)
- H2: 48px Bold (mobile: 28px)
- H3: 32px Bold
- H4: 24px SemiBold
- H5: 20px SemiBold
- H6: 18px SemiBold
- P1: 24px Regular
- P2: 18px Regular
- P3: 16px Regular
- P4: 14px Regular

**Layout:**
- Container max-width: 1200px
- Desktop margins: 120px left/right → `.container-site`
- Tablet margins: 40px
- Mobile margins: 16px
- Section padding: 144px top/bottom (mobile: 72px) → `.section-pad`
- Card gap: 32px between cards
- Gutter: 32px desktop, 24px tablet, 16px mobile

**Rules:**
- Orange ONLY for CTAs, highlights, icons, key accents — never large backgrounds
- Purple for dark section backgrounds
- BG Main/Alt for light section separation
- Single CTA across the site: `Book a Call`