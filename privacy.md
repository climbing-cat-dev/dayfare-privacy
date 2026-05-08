# Dayfare Privacy Policy

_Last updated: 2026-05-08_

Dayfare ("the app") is a travel spending tracker for iOS. This policy explains what data the app accesses and how it is used.

## Data the app collects

All expense, trip, location, photo, and audio data is stored only on your device and is never transmitted to any server. The single exception is anonymous product-analytics events, described below, which are only sent if you have opted in.

- **Location data** — used to record your travel route and auto-detect your local currency. Collected only while you are using the app or have explicitly enabled location tracking.
- **Photos and videos** — added by you when attaching media to expenses or trips. Stored in the app's local container.
- **Microphone audio** — captured only as part of video clips you record while attaching media to an expense.
- **Expense and trip data** — amounts, categories, notes, dates, and currencies that you enter manually.

If you have iCloud Backup enabled on your device, this data may be included in your encrypted device backup, managed by Apple. Dayfare does not control or access iCloud backups.

## Data the app does NOT collect

- No advertising or third-party tracking SDKs are included.
- No advertising identifiers are accessed.
- No personal information (name, email, account credentials) is requested or stored.
- No third-party tracking.

## Analytics (opt-in)

Dayfare uses [PostHog](https://posthog.com) for anonymous product analytics. It is off by default in the EU and on by default elsewhere, and you are asked during onboarding. You can toggle it any time in Settings → Privacy → Share Anonymous Analytics.

What is sent: a random per-install UUID (regenerated if you delete and reinstall the app), plus product-interaction events such as `expense_added`, `trip_created`, `onboarding_step_completed`, and basic context (app version, OS version, device locale country).

What is NEVER sent: expense amounts, notes, categories, currencies, photos, videos, audio, location coordinates, your name, email, or any account credentials. Dayfare does not have user accounts.

Where it goes: PostHog Cloud (US region, `us.i.posthog.com`). PostHog acts as a data processor under their [DPA](https://posthog.com/dpa).

Opting out: toggling the setting off immediately stops the SDK from sending further events. Previously sent events remain on PostHog's servers; to request deletion, email the contact below.

## Network access

The app makes outbound network requests to:

- `open.er-api.com` — public currency exchange rates (no personal data sent).
- `us.i.posthog.com` — anonymous analytics, only when opted in (per the section above).

## Data sharing

Dayfare does not sell or share your data. The only third party that ever receives any data is PostHog, and only when you have opted in to anonymous analytics (see above).

## Your control

You can delete all app data at any time by deleting Dayfare from your device. You can also export and re-import your data from Settings.

## Contact

Questions: cardpilled@gmail.com
