# EasyMQTT page copy

This folder contains all the text copy from `index.html`, organized by page
section. Each file matches one visible section of the site, in top-to-bottom
order.

## For the writer

Please edit the copy directly in these files. Keep the existing structure
and element labels — they tell us *where* each piece of text lives on the
page. Replace only the copy itself.

Notes on formatting:

- A few phrases use a non-breaking hyphen (U+2011) instead of a regular
  hyphen — e.g. "one‑time", "iOS‑native", "pretty‑printing". These prevent
  awkward line breaks mid-phrase on mobile. Preserve them if they appear in
  the source copy, or flag any you'd like to adjust.
- Em dashes (—) are used for rhythm in subheads. Keep or swap to commas as
  you see fit.
- A few places use *italic serif* for display emphasis (noted where it
  appears). If you change wording, tell us which phrase should keep the
  serif treatment.
- Code-looking text (MQTT topics like `zigbee2mqtt/kitchen/light`) renders
  in a monospace font. Use backticks when you want that treatment.

## Out of scope for this pass

- **FAQ content** (the questions in the Support section) — these are loaded
  at runtime from a different repo and used by the iOS app too. Edit
  happens there: `lucakaufmann.github.io/easymqtt/en.json` → `faqSections`.
  The fallback copy hardcoded into the page is listed in
  `09-support.md` for reference only — improving the live FAQs means
  editing the source-of-truth JSON in the other repo.
- **Article bodies** — same story. Articles live as `.md` files in the
  support repo under `lucakaufmann.github.io/easymqtt/articles/`.

## File index

| # | File | Section |
|---|------|---------|
| 01 | [01-nav.md](01-nav.md) | Sticky navigation |
| 02 | [02-hero.md](02-hero.md) | Hero (top of page) |
| 03 | [03-stats.md](03-stats.md) | Stats strip |
| 04 | [04-features.md](04-features.md) | Features grid |
| 05 | [05-automation.md](05-automation.md) | Automation spotlight |
| 06 | [06-use-cases.md](06-use-cases.md) | Use cases |
| 07 | [07-platforms.md](07-platforms.md) | Platforms row |
| 08 | [08-plus.md](08-plus.md) | EasyMQTT Plus |
| 09 | [09-support.md](09-support.md) | Support (tabs, sidebar, fallback FAQs/articles) |
| 10 | [10-final-cta.md](10-final-cta.md) | Final CTA |
| 11 | [11-footer.md](11-footer.md) | Footer |
