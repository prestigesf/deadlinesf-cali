# Live page snapshot, 2026-10-19 (add-only)

deadlinesfcali.netlify.app is not built from this repo. Its current page came from a manual API deploy (6a6e72a2087fae9d45f2c0b8, "cali-pricing-sync", 2026-08-01).

- `index.live-2026-10-19.html` is the live page exactly as served on 2026-10-19 (reference only).
- `index.html` is that page with words and links changed only, no visual changes:
  - CA Exposure Scan $795 -> $749 (price, Pay button, JSON-LD 750.00 -> 749.00)
  - free-patch buttons -> https://claimfreepatch.netlify.app/
  - footer mailto nicholle@deadlinesf.com -> plain text info@deadlinesf.net

The checkout key stays `ca_scan_795`. The live Stripe price still charges $795 until a $749 price exists.

2026-10-24 update (words and clock only, no visual changes):
- SB 942 card: "Deadline · August 2, 2026" -> in effect since Aug 2, 2026; SB 1000 is no longer "moving in the Assembly" (signed Sept 30, 2026, in effect immediately, 1M-user carve-out deleted).
- The countdown hit zero on Aug 2, 2026. After that date it now shows time since SB 942 took effect instead of 00:00:00:00.
