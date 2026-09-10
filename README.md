# Tesla Model 3 Equity Tracker

iPhone-first PWA for:
- 2021 Tesla Model 3 Long Range AWD
- Acceleration Boost
- 52,168 miles at setup
- £50,000 loan
- 2.8% APR
- 84 months
- first payment March 2022

Seed valuation (10 Sep 2026):
- Market estimate: £19,250
- WBAC quote: £16,990

Calculated monthly payment: £656.17

## Publish it

The folder is a complete static website. Upload all files to any static host such as:
- GitHub Pages
- Cloudflare Pages
- Netlify

Then open the HTTPS URL in Safari on iPhone and use:
Share → Add to Home Screen

The app stores valuation edits in your browser/PWA local storage, and the loan balance recalculates automatically based on the current date.

## Important limitation

This version cannot automatically scrape live UK car-listing sites from the browser. The market estimate is seeded from web research, while future market/WBAC values can be updated inside the app. A backend or a valuation API would be needed for automatic live refreshes.
