# Meta Ad Auditor

**Try it:** https://carlostorres-growth.github.io/meta-ad-auditor/
Click "Try with sample data" to see it work. No login needed.

A browser tool that pulls every active ad in a Meta ad account and flags the ones that waste spend.

## Why I built it

Running paid social for several e-commerce brands, I kept finding the same problems in live ads: single-product ads sending people to a collection page instead of the product page, ads still showing an offer that had ended, and ads with no destination at all. Checking this by hand in Ads Manager, account by account, was slow and easy to miss.

I built the first version for my team, and it's still in use. This is a cleaned-up public version with no client data.

## What it checks

- **Destination vs. creative.** An ad showing one product that sends people to a collection page gets flagged "switch to product page". An ad showing several products that sends people to a single product page gets flagged for review.
- **Outdated copy.** You list phrases that shouldn't run anymore (e.g. "Summer Sale"), and any active ad still using them is flagged with the phrase highlighted.
- **Missing or unexpected destinations.** Ads with no URL, or pointing to the homepage or another page type, get flagged for review.

Results are sorted by
