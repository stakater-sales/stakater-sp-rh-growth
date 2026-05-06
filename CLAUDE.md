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
