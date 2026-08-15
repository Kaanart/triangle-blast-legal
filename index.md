---
title: Triangle Blast — Privacy Policy
---

# Triangle Blast — Privacy Policy

*Last updated: 14 August 2026*

## Overview

Triangle Blast ("the App") is a single-player puzzle game developed and
published by **Euragnos B.V.**, a private limited company incorporated in
the Netherlands, which is the **data controller** for the limited processing
described below.

**Controller details**

> Euragnos B.V.
> Johan de Wittlaan 7
> 2517 JR Den Haag
> Netherlands
>
> Chamber of Commerce (KvK) number: **86313428**
> Email: kaanuysal@euragnos.com

No Data Protection Officer has been appointed. One is not required here:
GDPR Art. 37 mandates a DPO only for public authorities, for large-scale
regular and systematic monitoring, or for large-scale processing of special
categories of data, and none of those describe this App.

The App has **no user accounts, no login, and
no multiplayer or social features of any kind** — there is nothing to sign
up for, and nothing tying your activity to your identity. All game
progress (score, unlocked themes, mute/language settings) is stored only
on your own device.

The App is intended for a general audience and is not directed at
children under 13.

## Data We Collect

### Locally stored game data (never leaves your device)

The App saves your progress in a file on your device only: number of
games played, high score, best combo, which cosmetic themes you've
unlocked, your selected theme, your mute setting, and your selected
language. This file is never transmitted anywhere. Uninstalling the App
deletes it.

### Advertising (Google AdMob)

The App shows one optional short video ad when you choose to continue a
lost game ("Phoenix Reset" revive) — never any other ad format, and never
without you tapping to request it. Ads are served by Google's AdMob SDK.

Regardless of your consent choice below, Google's AdMob SDK automatically
collects your IP address, device and advertising identifiers, and app
diagnostic/interaction data for ad delivery, analytics, and fraud
prevention, per [Google's own disclosure requirements](https://developers.google.com/admob/android/privacy/play-data-disclosure).

Whether ads are additionally *personalized* to your interests depends on:
- **EEA/UK users:** a consent form shown via Google's User Messaging
  Platform (UMP) on first launch when required by your region.
- **iOS users:** the system App Tracking Transparency (ATT) permission
  prompt.

You can change your ad-personalization choice at any time from
**Settings → Privacy Options**. If you decline personalization, AdMob
automatically falls back to non-personalized ads — the revive feature
still works exactly the same either way.

See [Google's Privacy Policy](https://policies.google.com/privacy) and
[AdMob's data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure).

### Crash and error reports (Sentry)

The App uses Sentry to automatically report crashes and errors so we can
fix bugs. We've configured Sentry to minimize what it receives:

- Screenshots are **not** attached to crash reports.
- Performance/session tracing is **off** (0% sample rate).
- Sentry's default PII collection is explicitly **disabled**.

What Sentry does receive: the crash/error stack trace, two small tags
(which cosmetic theme you had active, and your games-played count), and
the baseline device/OS/app-version metadata the Sentry SDK includes by
default for grouping similar crashes together. None of this is linked to
your name, email, or any account, since the App has none.

See [Sentry's Privacy Policy](https://sentry.io/privacy/).

### Anonymous gameplay analytics (Supabase)

The App logs a small, fixed set of gameplay events to a private database
we operate on Supabase, so we can understand how the game is played:

| Event | What's recorded |
|---|---|
| Game started | Nothing beyond the event itself |
| Game ended | Final score, best combo, active theme |
| Revive used | Active theme |
| Theme unlocked | Which theme |
| Theme selected | Which theme |

Each event is tagged only with a random identifier that is **generated
fresh every time you open the App** — it is not saved, not tied to your
device, and cannot be used to link your activity across separate play
sessions, let alone to your identity. No device identifier, advertising
ID, or any other personal data is included in these events.

The database only accepts new entries — the key embedded in the App
cannot read, modify, or delete existing data, which prevents the app
itself (or anyone extracting that key) from browsing collected analytics.

### We do not collect

Your name, email address, physical address, phone number, photos,
contacts, precise location, or any account credentials — the App has no
account system of any kind to attach this data to even if we wanted to.

## Third Parties

| Service | Purpose | Data involved |
|---|---|---|
| Google AdMob / UMP | Rewarded video ads, consent management | IP address, device/advertising identifiers, diagnostic data (always); ad-personalization only per your consent choice |
| Sentry | Crash/error reporting | Crash stack traces, 2 gameplay tags, baseline device/OS metadata — no PII, no screenshots |
| Supabase | Anonymous gameplay analytics | Per-launch random session ID, gameplay event data (score/combo/theme) — no device or advertising identifiers |

## Legal Basis for Processing (EEA/UK)

Euragnos B.V. is established in the Netherlands, so the GDPR applies to
the processing described above wherever you play.

| What | Legal basis |
|---|---|
| Personalized ads (AdMob, where you have opted in via UMP or ATT) | Your **consent** (GDPR Art. 6(1)(a)), withdrawable at any time |
| Non-personalized ad delivery, and the ad fraud-prevention and diagnostic data AdMob collects regardless of consent | **Legitimate interests** (Art. 6(1)(f)) in funding and protecting a free game |
| Crash and error reports (Sentry) | **Legitimate interests** (Art. 6(1)(f)) in keeping the App stable and secure |
| Anonymous gameplay analytics (Supabase) | **Legitimate interests** (Art. 6(1)(f)) in understanding how the game is played. These events carry no device or advertising identifier and no persistent ID, so they are not expected to identify you |

Withdrawing consent to ad personalization does not affect the lawfulness
of processing carried out before you withdrew it, and never disables the
game or the revive feature.

## Your Rights Under EU/UK Data Protection Law

If the GDPR or UK GDPR applies to you, you have the right to request
access to your personal data, and to request its rectification, erasure,
or restriction; to object to processing carried out on the basis of
legitimate interests; to data portability; and to withdraw consent at any
time. Ad personalization consent is withdrawable in-app at any time via
**Settings → Privacy Options**.

**An important practical limit:** the App deliberately holds no
identifier that would let us find your data. Analytics events carry only
a random ID regenerated on every launch and never stored, and crash
reports are not linked to any account. Under GDPR Art. 11, where a
controller cannot identify a data subject, it is not required to acquire
additional information purely to enable rights requests — and we will not
start collecting identifying data just to make lookups possible. In
practice this means we usually cannot locate, export, or delete a
specific person's past events, because nothing distinguishes them. The
routes that *do* work are:

- **Advertising identifier:** reset or delete it in your device settings
  (iOS: Settings → Privacy & Security → Tracking; Android: Settings →
  Privacy → Ads), and exercise your rights directly with Google, who is
  the party holding it.
- **Local save data:** uninstall the App; it is deleted immediately and
  permanently.

You also have the right to lodge a complaint with a data protection
supervisory authority. Our lead supervisory authority is the Dutch
**Autoriteit Persoonsgegevens** (<https://autoriteitpersoonsgegevens.nl>).
You may also complain to the authority in your own country of residence.

## International Data Transfers

The two services we operate ourselves are both hosted in the EU:

- **Sentry** (crash reports) — EU region, Germany.
- **Supabase** (gameplay analytics) — EU region, Ireland (eu-west-1).

Data sent to those two therefore stays within the EEA and involves no
third-country transfer.

**Google (AdMob / UMP)** is different. Google operates globally and will
process advertising data, including your IP address and advertising
identifier, outside the EEA — including in the United States. Those
transfers rely on the transfer mechanisms Google makes available, such as
the EU Standard Contractual Clauses and, where applicable, the EU–US Data
Privacy Framework. See [Google's Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

Triangle Blast is intended for a general audience and is not directed at
children under 13. We do not knowingly collect personal information from
children. [If your final App Store/Play Store age rating or marketing
positioning changes this, this section and the AdMob configuration above
need re-review — a child-directed app has substantially different
obligations under COPPA and Google Play's Families Policy that this draft
does not attempt to cover.]

## Your Choices

- **Ad personalization:** change anytime via Settings → Privacy Options.
- **iOS tracking:** change anytime via iOS Settings → Privacy & Security →
  Tracking → Triangle Blast.
- **Local data:** uninstalling the App immediately and permanently deletes
  your locally stored save data.
- **Crash reports / analytics already sent:** because neither system
  links data to a persistent identifier we hold, we have no way to locate
  and delete a specific individual's past crash reports or analytics
  events on request — there is no identifier to search by. If this
  matters to you, you can decline ad personalization and analytics data
  will still be collected (the analytics event set is not gated by the
  ad-consent choice, since it collects no personal data), but no
  additional identity-linkable data will be present in either case.

## Data Retention

- **Crash and error reports (Sentry):** retained for **90 days**, then
  deleted automatically under Sentry's own retention policy.
- **Gameplay analytics (Supabase):** retained for **24 months** from the
  date of the event, then deleted.
- **Local save data:** kept on your device until you uninstall the App,
  which deletes it immediately and permanently. We never receive it.

## Security

Data sent to Sentry and Supabase travels over encrypted HTTPS connections.
The Supabase database enforces row-level security so that the key
embedded in the App can only add new analytics rows, never read or alter
existing ones.

## Contact

Questions about this policy: kaanuysal@euragnos.com

## Changes to This Policy

We may update this policy as the App changes. Material changes will be
reflected by updating the "Last updated" date above.
