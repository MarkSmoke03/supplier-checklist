# Supplier Registration Readiness Checklist

A free, mobile-first checklist for small Zambian contractors and suppliers preparing for supplier registration with mining companies and other large buyers.

- 39 documents and requirements across 8 sections, each tagged **Commonly required** or **Check with the buyer**
- Readiness score, missing-items list and a plain next step for each gap
- Results formatted for WhatsApp
- One HTML file, no external requests, answers stay in the visitor's browser

This is a preparation guide, not an official requirements list. Every buyer sets its own requirements.

## Editing

Everything lives in `index.html`.

- **Contact details:** edit the `CONFIG` block at the top of the script (`whatsapp` takes digits only, international format, e.g. `260971234567`).
- **Visitor count (optional):** create a free GoatCounter site and put its code in `goatcounter`. Leave it empty for no counting.
- **Checklist items:** edit the `ITEMS` array. Each item has a section (`cat`), a tag (`common` or `buyer`), a title, a "What is this?" note (`why`) and a next step (`next`). Add `na:true` to allow "Not relevant".

## Hosting

Served with GitHub Pages from the `main` branch root.

Built by Mark Chushi.
