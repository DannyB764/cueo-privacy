# Cueo Privacy Policy

_Last updated: 2026-05-15_

Cueo is a personal notes app built around a simple promise: **your notes never leave your devices unless you choose to share them.** This document explains how Cueo handles data and what permissions it requests.

## TL;DR
- We don't collect any personal data.
- We don't use third-party analytics, ad SDKs, or trackers.
- Notes sync via your own iCloud account (Apple's end-to-end encryption applies).
- All AI features run on-device using Apple Intelligence.
- Integrations (Google Calendar, Apple Reminders) read your own data with your own credentials.

## What Cueo stores
Cueo stores your notes, blocks, folders, tags, attachments, and app preferences. By default this data lives in two places:

1. **Locally on your device**, inside Cueo's app sandbox.
2. **In your personal iCloud private database** (CloudKit), if you're signed in to iCloud on your device. The sync is encrypted in transit and at rest. We do not have access to your iCloud private database — only you and the devices signed in to your Apple ID do.

We do not transmit your notes to any server we control. There is no Cueo backend.

## Permissions Cueo may request
You're prompted only when you opt into a feature that requires the permission:

- **Microphone** — to record voice notes. Audio is transcribed locally; recordings are stored only inside Cueo's local database.
- **Speech Recognition** — to convert your voice notes to text. When supported, transcription runs entirely on-device.
- **Calendar (Apple + Google)** — to display your events alongside your daily notes. Cueo reads events from calendars you select; no calendar data is sent to any server we control. Google OAuth tokens are stored in your device keychain.
- **Reminders** — to two-way sync your todo blocks with Apple Reminders so Siri and Reminders.app stay in sync. Reminders are read and written using EventKit.
- **Notifications** — to remind you when a note's due date arrives. Notifications are scheduled locally; nothing leaves your device.
- **Photos** — only when you tap "Insert image" in an editor and use the system photo picker.

Any of these can be granted or revoked at any time in your device's Settings app.

## Apple Intelligence and AI features
Cueo's AI features (Tidy & Format, Rewrite Cleaner, summaries) use Apple's on-device Apple Intelligence framework. Your text is processed locally; nothing is sent to OpenAI, Anthropic, Google, or any other cloud provider.

If your device doesn't support Apple Intelligence, the AI features are simply unavailable — Cueo never falls back to a cloud model without explicit user action.

## What Cueo does NOT collect
- No advertising identifier (IDFA).
- No analytics events.
- No crash-reporting service. Crash and hang data is captured locally via Apple's MetricKit framework and shown to you in Settings → Diagnostics. Nothing is transmitted automatically.
- No location data.
- No contact information.
- No usage telemetry.

## Children's privacy
Cueo doesn't knowingly collect data from anyone, including children under 13.

## Changes to this policy
If we change anything material, this page will be updated and the "Last updated" date above will change. There is no email list — checking this page is the canonical record.

## Contact
For privacy questions or to report a concern, email: appinfo@redclay.com

---

Cueo is an independent app. It is not affiliated with Apple, Google, or any third party referenced in this policy.
