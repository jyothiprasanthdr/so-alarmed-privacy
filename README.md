# So Alarmed Legal

The official Privacy Policy and Terms of Use for **So Alarmed**, a privacy-first alarm
app for iPhone, developed by **Nandha Kumar Ilangovan**.

## Live pages

Served by GitHub Pages:

- Privacy Policy: **https://jyothiprasanthdr.github.io/so-alarmed-privacy/**
- Terms of Use: **https://jyothiprasanthdr.github.io/so-alarmed-privacy/terms.html**

Use these as the **Privacy Policy URL** and **EULA / Terms URL** in App Store Connect.
The same two URLs are also linked inside the app, in Settings and on the paywall.

## Files

| File | Purpose |
|---|---|
| `index.html` | Hosted Privacy Policy (the canonical published page). |
| `terms.html` | Hosted Terms of Use. |
| `privacy-policy.md` | Markdown mirror of the Privacy Policy. |
| `terms.md` | Markdown mirror of the Terms of Use. |

> Keep each `.html` page and its `.md` mirror in sync when you make changes.

## Updating

1. Edit the `.html` page (and mirror the change in the matching `.md`).
2. Update the **"Last updated"** date in both files.
3. Commit and push to `main`. GitHub Pages redeploys automatically.

## Notes

- The Privacy Policy reflects the app's actual data practices as of June 28, 2026:
  optional Apple/Google sign-in via Firebase Auth, optional cloud backup of alarms and
  streak via Cloud Firestore, Apple StoreKit subscriptions, and on-device-only motion
  sensing for the Shake/Walk missions. No analytics, ads, crash reporting, or
  third-party tracking.
- The Terms of Use include an alarm-reliability safety disclaimer and Apple's required
  Licensed Application End User License Agreement minimum terms.
- Governing law in the Terms is set to **India**. Change Section 14 if the operating
  entity is based elsewhere.
- If you add or remove any data collection (for example the planned "calendar wake"
  feature), update the Privacy Policy and your App Store privacy disclosures before
  shipping.
