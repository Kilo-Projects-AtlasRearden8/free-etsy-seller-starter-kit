# STATUS

## What was built

Free Etsy Seller Starter Kit — fillable, printable, no account needed — for new
Etsy sellers, credited to Asdale Dynamics, LLC (MIT License).

Files:

- `README.md` — kit overview, contents, how to use, Asdale Dynamics, LLC credit
- `LICENSE` — MIT License, copyright line exactly
  `Copyright (c) 2026 Asdale Dynamics, LLC`
- `shop-policies.md` + `shop-policies.html` — fill-in shop policies (processing,
  shipping, returns, custom orders, FAQ)
- `listing-worksheet.md` + `listing-worksheet.html` — pre-listing prep (title,
  photos, details, pricing, tags, description)
- `pricing-calculator.md` + `pricing-calculator.html` — materials, labor, Etsy
  fees, shipping, profit with live browser calculation
- `packaging-slip.md` + `packaging-slip.html` — print-and-tuck order slip
- `income-log.md` + `income-log.html` — monthly sales/fees/net income tracker
- `STATUS.md` — this file

Every `.html` page has print styles (Ctrl/Cmd+P) that hide form borders and
controls for clean printouts, and runs entirely client-side — nothing is sent
anywhere.

## How to run

1. Open the folder in File Explorer / Finder.
2. Open any `.html` file in a web browser (Chrome, Firefox, Safari, Edge).
3. Fill in fields on screen, or print by hand (Ctrl+P / Cmd+P).
4. No install, no account, no secrets, no network required.

## Verification results

- All 5 HTML files parse cleanly with Python's HTML parser (no errors).
- `pricing-calculator.html` embedded JavaScript passes `node --check`.
- Every HTML file, README.md, and LICENSE contains
  `Copyright (c) 2026 Asdale Dynamics, LLC`.
- README.md credits Asdale Dynamics, LLC (3 mentions).
- No `.github/workflows` files, no secrets, no API keys, no personal data.

## Known gaps

- Pricing calculator uses fixed US-fee estimates (6.5% transaction, ~3% +
  $0.25 processing, $0.20 listing); sellers outside the US should adjust
  manually.
- No data persistence: refresh clears entries; print or save as PDF to keep
  records.
- Markdown files are reference copies; the HTML pages are the fillable versions.
