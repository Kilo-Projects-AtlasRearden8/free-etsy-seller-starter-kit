# STATUS

## What was built

Free Etsy Seller Starter Kit — fillable, printable, no account needed — for new
Etsy sellers, credited to Asdale Dynamics, LLC (MIT License).

Files:

- `README.md` — kit overview, who it's for, contents, how to use, Asdale Dynamics, LLC credit
- `LICENSE` — MIT License, copyright line exactly
  `Copyright (c) 2026 Asdale Dynamics, LLC`
- `shop-policies.md` + `shop-policies.html` — fill-in shop policies (processing,
  shipping, returns, custom orders, FAQ)
- `listing-worksheet.md` + `listing-worksheet.html` — pre-listing prep (title,
  photos, details, pricing, tags, description)
- `pricing-calculator.md` + `pricing-calculator.html` — materials, labor, Etsy
  fees, shipping, and profit with live browser calculation
- `packaging-slip.md` + `packaging-slip.html` — print-and-tuck order slip
- `income-log.md` + `income-log.html` — monthly sales/fees/net income tracker
- `STATUS.md` — this file

Every `.html` page has print styles (Ctrl/Cmd+P) that hide form borders and
controls for clean printouts, and runs entirely client-side — nothing is sent
anywhere.

## How to run

1. Open the folder and double-click any `.html` file. It opens in your web
   browser (Chrome, Firefox, Safari, or Edge).
2. Fill in the fields on screen, or print the page and write by hand.
3. To print: press **Ctrl+P** (Windows/Linux) or **Cmd+P** (Mac). Each page has
   print styles that hide form borders and controls so your printout looks clean.
4. Save a copy for your records. Nothing is sent anywhere — everything stays
   on your computer. No install, no account, no secrets, no network required.

## Verification results

- All 5 HTML files parse cleanly with Python's HTML parser (no errors).
- `pricing-calculator.html` embedded JavaScript passes `node --check` (valid
  syntax; runs in the browser DOM).
- Every HTML file, README.md, and LICENSE contains the exact line
  `Copyright (c) 2026 Asdale Dynamics, LLC`.
- README.md credits Asdale Dynamics, LLC (3 mentions) and links to
  dylanasdale.github.io.
- LICENSE contains the exact required copyright line.
- No `.github/workflows` files; no secrets, API keys, passwords, tokens, or
  email addresses anywhere in the repo.
- All 5 Markdown/HTML pairs are present.
- Committed as `8eee331` on `master`; working tree clean; no push, no remote.

## Known gaps

- Pricing calculator uses fixed US-fee estimates (6.5% transaction, ~3% +
  $0.25 payment processing, $0.20 listing); sellers outside the US, or using
  current Etsy fee schedules, should adjust the inputs manually.
- No data persistence: refreshing the page clears entries. Print or save as PDF
  to keep records.
- Markdown files are reference copies; the HTML pages are the fillable versions.
