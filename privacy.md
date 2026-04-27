---
title: "Privacy Policy"
---

# Presidenter — Privacy Policy

**Last updated: April 2026**

Presidenter does not collect, store, or transmit any personal information about you to anyone, ever.

The app stores your gameplay state — decisions, achievements, nation profile, settings — locally on your device using Apple's standard `UserDefaults` storage. No analytics, no tracking, no third-party SDKs, no telemetry.

---

## iCloud sync (optional, automatic)

If you are signed in to iCloud on your device, the following data may sync via Apple's iCloud Key-Value Storage to your other Apple devices:

- Your career-best day count
- Your earned achievement set
- Your nation profile (country name + leader name + visual theme)
- Your seen-chains history (used to vary content across reigns)

This sync is end-to-end encrypted by Apple and is not visible to the developer. You can disable it system-wide via:

**Settings → [Your Name] → iCloud → Apps Using iCloud → Presidenter**

---

## Weekly Safety Backup (optional, Settings toggle)

If you enable Weekly Safety Backup (Settings → iCloud → Weekly Safety Backup), the app writes a single backup JSON file once per week to your iCloud Drive Documents folder.

This file contains the same gameplay state stored locally on your device and is **not** visible to the developer. You can browse it in the Files app under **iCloud Drive → Presidenter**.

You can disable this feature any time via the Settings sheet.

---

## Chronicle export (optional, manual)

You can export your reign chronicle as a markdown file at any time via the chronicle screen's **Export** button. This file is created locally and shared via the iOS share sheet to a destination of your choice (Files, Mail, Messages, etc.).

The developer never receives this file.

---

## AI Card Generation (optional, opt-in only)

If you opt into the AI Card Generation feature (My Cards → AI Generation) and provide your **own** API key for OpenAI, Anthropic, or Google Gemini, the app sends the prompt you compose to that vendor's HTTPS endpoint to generate a card.

- Your API key is stored in the iOS Keychain on your device only.
- Your key is never transmitted to the developer or any other third party.
- The data collected by the AI vendor when you make a generation request is governed by **that vendor's own privacy policy**.
- You can revoke the key at any time via My Cards → AI Generation → Reset Key.
- The feature is locked behind you providing your own key. Without a key, no AI requests ever fire.

For reference, here are the privacy policies of the three supported AI vendors:

- [OpenAI](https://openai.com/policies/privacy-policy)
- [Anthropic](https://www.anthropic.com/legal/privacy)
- [Google Gemini](https://policies.google.com/privacy)

---

## Game Center (optional, sign-in required)

If you are signed in to Game Center on your device, the app submits your career-best day count to Apple's leaderboard. Apple owns this data; the developer does not.

---

## What we never do

- The app contacts no servers controlled by the developer.
- No analytics service is integrated.
- No advertising network is integrated.
- No social-media SDK is integrated.
- No data is sold to anyone, ever.
- No third-party SDKs of any kind ship with the app.

---

## Children

Presidenter is rated 9+. The game contains no graphic violence, no profanity, no sexual content. References to war, drought, scandal, and crisis appear as gameplay text only.

We do not knowingly collect any data from children, because we do not collect any data at all.

---

## Changes to this policy

If this policy changes meaningfully, the "Last updated" date at the top of this page will change. Players are encouraged to re-read it on app updates.

---

## Contact

Questions about this policy: **[gokhanca@icloud.com](mailto:gokhanca@icloud.com)**

_Developed by Gokhan Arslan._
