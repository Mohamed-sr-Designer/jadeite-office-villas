# Jadeite — Office Villas (جاديت — فلل مكتبية)

A premium, bilingual (Arabic / English) single-page landing site for **Jadeite Office Villas** — a development of standalone office villas in **Riyadh, Saudi Arabia**. Instead of a floor in a tower, each company gets its own villa within an integrated, gated community.

## Highlights
- **Single-page**, fully responsive (desktop / tablet / mobile)
- **Bilingual AR (RTL, default) / EN (LTR)** with an instant language toggle
- **Glassmorphism** luxury theme — brand green `#004438`, silver `#8C9091`, black
- Solid-green loading screen, scroll reveals, animated stat counters
- **Registration modal** (opens from the navbar + hero) with a dark overlay and smooth open/close
- In-page lead form at the bottom
- Floating **back-to-top** button that adapts to text direction (RTL → bottom-left, LTR → bottom-right)
- Optimized, lazy-loaded imagery; total page weight ≈ 1.5 MB

## Structure
```
jadeite/
├─ index.html        # the entire site (HTML + CSS + JS, self-contained)
├─ assets/           # logos (AR/EN, black + white) and optimized imagery
├─ server.js         # tiny zero-dependency static server for local preview
└─ README.md
```

## Run locally
Any static server works. With Node installed:
```bash
node server.js 8333
# then open http://localhost:8333
```

## Notes
- The contact form and registration modal currently show a success state on submit.
  To receive submissions, wire the form to a backend or service (e.g. Formspree) at the
  `TODO` marker in the `<script>` block of `index.html`.
- Project figures (number of villas, sizes, handover date, contact details) are placeholders
  to be confirmed with the client.

---
© 2026 Jadeite Office Villas — *The Future of Prosperity*
