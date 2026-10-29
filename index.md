---
title: Privacy Policy
lang: en
---

[Türkçe](tr.html)

# Privacy Policy — Pocket Business City

**Last updated:** 29 October 2026

## The short version

Pocket Business City has no accounts and no advertising, and the game itself is
played entirely on your device — it needs no connection to work, and your saved
company and cities never leave your phone.

It does send usage and crash information to Firebase, a Google service, so we
can see how many people play, how far they get, and what is broken. It also
fetches game-balance settings from Firebase, and — only if you turn reminders on
— can receive announcements. This page says exactly what that means.

There is no field anywhere in the game for your personal name, an email address,
a phone number, a contact, a location, a photo, or a payment method. The company
name you choose is an in-game label, not a request for your real name.

## What stays on your device

Written to your device's private application storage. Readable only by this app,
never uploaded anywhere, deleted when you uninstall the game.

| What                                                                                                               | Why                                       |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------- |
| Your saved company and city runs — company name, cities, cash, businesses, staff, loans, statistics and game clock | So the game can resume where you left off |
| Your preferences — chosen language, notification opt-in, sound and vibration opt-in                                | So the game behaves the way you set it up |

**Your company name never leaves the device unless you join the leaderboard.** It
is the one piece of text you write yourself, and it is deliberately excluded
from everything sent below — with the single exception of the leaderboard, which
you have to opt into, and which shows you the name before it publishes it.

## What is sent to Firebase

Firebase is operated by Google. Google acts as our data processor and may
process this information on servers outside your country. Google's own handling
of it is covered by the [Firebase privacy
documentation](https://firebase.google.com/support/privacy) and the [Google
privacy policy](https://policies.google.com/privacy).

### Usage analytics

Twenty named events, and nothing else. Every one is an action in the game,
and every value in them is an identifier the game chose — a business type, a
theme, a district — never anything you typed:

`city_created`, `city_restarted`, `business_built`, `business_sold`,
`upgrade_purchased`, `renovation_started`, `renovation_finished`, `level_up`,
`loan_taken`, `loan_repaid`, `task_resolved`, `disaster_struck`,
`theme_changed`, `live_event_applied`, `push_opened`, `leaderboard_joined`,
`leaderboard_left`, `leaderboard_viewed`, `tutorial_begin`, `tutorial_complete`.

Alongside them, six facts about how you are playing, so the numbers can be read
by group rather than one player at a time: your level, roughly how many
businesses you own, your chosen theme, your app language, whether you have a
loan outstanding, and which version of the balance settings you received.

Firebase also collects a standard set on its own, which we do not choose: an
app-instance identifier, your device model and operating system version, the app
version, your app language, and an approximate country derived from your IP
address. Google does not retain the IP address itself. This identifier is
specific to this app on this device; it is not your advertising ID, and the game
never reads your advertising ID (IDFA / AAID).

### Crash reports

When the game crashes, Firebase Crashlytics sends the stack trace, the state of
the device at the time, and a Crashlytics installation identifier, together with
the same six facts listed above so we can tell which situation produced it. No
save data and no company name is attached.

### Game-balance settings

The game asks Firebase Remote Config for settings — how strong an event is, how
often disasters happen — at launch and when it returns to the foreground. The
request carries the app-instance identifier and three values used to decide
which settings you should get: your app language, your level, and roughly how
many businesses you own.

**This is never required to play.** Every remote setting is a multiplier that
defaults to 1, the game reads whatever it already has on the device, and a
device that never reaches Firebase plays identically to one that does.

### Announcements

Only if you turn reminders on in Settings. Firebase Cloud Messaging then issues
a registration token for this installation and subscribes it to a topic for your
chosen language, so an announcement can be sent in a language you read without
anybody holding a list of who speaks what. Turning reminders off stops it.

### The leaderboard

Only if you join it, which is a separate step behind its own sheet. Nothing
below happens until you confirm it, and nothing at all is created before then —
no account, no entry, no request.

Joining creates an **anonymous account**: a random identifier for this
installation, with no email, no password and no profile attached. It does not
survive uninstalling the app, so reinstalling means starting again on the board.

What becomes public is exactly two things: **the name you choose** and **what
you earned this week**. The sheet fills the name in from your company's, because
you already chose it, and lets you change it before anything is published —
which is why the promise above is that your company name never leaves the device
_unless you join_. Nothing else about your city is sent: not your save, not your
businesses, not your balance.

You can leave at any time in Settings, which deletes your entry.

**Reporting and hiding.** Tap another player's name to hide it from your board
or to report it. Hiding stays on your device. A report sends the reported
name, its anonymous identifier and the week — the same things already shown on
the board — and nothing about you; it works without joining and creates no
account. We review reports and remove names that break the rules.

## Device permissions

| Permission                           | When it is asked for                                                | What it is used for                                                               |
| ------------------------------------ | ------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Notifications (`POST_NOTIFICATIONS`) | Only when you turn reminders on in Settings — never on first launch | Local reminders that your businesses need attention, and occasional announcements |
| Vibration (`VIBRATE`)                | Not prompted; Android grants it automatically                       | Short haptic feedback on button presses, which you can switch off in Settings     |

Declining or revoking the notification permission has no effect on the rest of
the game.

## What the game still does not do

- **No accounts or sign-in, unless you join the leaderboard** — and that one is
  anonymous, with nothing to register for and nothing to sign in to.
- **No advertising, and no ad identifiers.** The game does not read your
  advertising ID and does not share anything with advertisers or data brokers.
- **No purchases.** There are no in-app purchases and no payment processing.
- **No selling or sharing of data.** Nothing collected is sold, and nothing is
  shared with anyone other than Google as the processor described above.
- **No gameplay that depends on a connection.** The simulation, the economy and
  your save are entirely local. Aeroplane mode changes nothing about the game.

## Children

The game is suitable for all ages and is not directed at children under 13. It
collects no personal information from anyone, children included: nothing it
sends identifies a person, and there is no way to enter anything that could.

## Retention

Analytics data is held for the retention period set in our Firebase console and
deleted automatically after it; Google's available settings are 2 months and 14
months. Crash reports are held for 90 days.

## Your rights and your choices

Nothing collected identifies you, so there is no account to access, correct or
export. What you can do:

1. **Turn reminders off** in Settings, which stops announcements and removes the
   messaging token.
2. **Delete your save** in Settings → Delete save, which erases everything the
   game holds on your device.
3. **Uninstall the app**, which removes its storage and stops all collection.
4. **Write to us** at the address below with any question about this policy.

On an access or erasure request: what is collected carries no name, no account
and no contact detail, so in most cases there is nothing we can single out as
yours. Uninstalling stops all collection, and what has already been sent expires
on its own within the periods above. Write to us anyway if you want to ask — we
will tell you honestly what we can and cannot find.

If you are in the EU or UK: the lawful basis for the analytics and crash
reporting described above is legitimate interest — understanding how the game is
used and fixing what breaks — and none of it is used to build a profile of you
or to target advertising.

## Changes to this policy

Any future version of the game that collects something new will have this
document updated before it ships, and the change will be described in the app's
release notes.

## Contact

Questions about this policy: **ardasnturk@gmail.com**
