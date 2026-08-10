# CLFANAGT — Brand System

A complete visual identity for a senior European consulting practice. Editorial register, type-led, no photography. Intended for analytical and advisory deliverables in French, English, and Dutch.

## Files

### Foundations
- **00 Overview** — `00_overview.html` — system at a glance
- **Typography** — `type_specimen.html` — full hierarchy specimen
- **Wordmark** — `wordmark.html` — three logo treatments
- **Color directions** — `colors.html` — three palettes side by side
- **Language accents** — `lang_accents.html` — FR / EN / NL accent system

### Direction comparison
- **A · Ink & Amber** — `direction_A.html`
- **B · Continental Green** — `direction_B.html`
- **C · Naval Precision** — `direction_C.html`

### Templates (built in primary direction with toggle)
- **Invoice** — `template_invoice.html`
- **Report** — `template_report.html` (cover, divider, text+chart, table, pull quote, back)
- **One-pager** — `template_onepager.html`
- **Recommendation memo** — `template_recommendation.html`
- **Business card** — `template_card.html`
- **Swag** — `template_swag.html` (mug, bottle, t-shirt)

## Tokens
All shared variables live in `tokens.css`. Direction-specific palettes are scoped via `[data-direction="A|B|C"]`. Language accents are universal and scoped via `[data-lang="fr|en|nl"]`.
