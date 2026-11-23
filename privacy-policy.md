# ScrollSmack Privacy Policy

**Last updated:** 23 November 2026

## The short version

ScrollSmack collects nothing, transmits nothing, and has no servers. The app has
no network permission at all, so it is not technically capable of sending your
data anywhere.

## What the app stores

Everything ScrollSmack knows lives only on your device. The app's private storage
holds:

- **Which apps you chose to track** — the package names you ticked in the picker.
- **Your time limit** — the number of minutes you selected.
- **Whether it is on, off or paused** — including when a pause ends, when you
  turned it off (used to time reminders), and when you first turned it on.
- **Rating prompt counters** — how many roasts you have dismissed, and how many
  times and when the app last asked for a rating.

ScrollSmack also keeps a small **diagnostic log** in its own app folder on your
device's shared storage. It holds timestamps for events such as the timer starting
or stopping, a pause, a reminder, a phone restart or a limit being crossed, along
with the limit in minutes and whether the app's permissions are granted. It does
not contain the names of the apps you use, and it is never sent anywhere.

That is the entire list. Deleting the app deletes it.

Android's Auto Backup is switched **off** for ScrollSmack, and both cloud backup
and device-to-device transfer (Samsung Smart Switch and similar) are explicitly
excluded. Your list of tracked apps never leaves the phone even when you migrate
to a new one — the trade-off being that you re-pick your apps and limit after a
factory reset or a new device.

## What the app reads

- **Usage access (`PACKAGE_USAGE_STATS`)** — ScrollSmack asks Android which app
  is currently in the foreground, roughly once a second, so it can measure how
  long you have been continuously using an app you chose to track. This reading
  never leaves your device, which app is on screen is never written to a file,
  and nothing is associated with an identity — the app has no accounts.
- **Installed apps** — to show you a list to choose from, ScrollSmack asks
  Android for apps that have a launcher icon. This list is displayed to you and
  not recorded.

## Google Play ratings

After you have used ScrollSmack for a few days, it may ask Google Play to show its
standard rating prompt. Google Play displays that prompt and handles any rating or
review you choose to submit, under Google's own privacy policy. ScrollSmack cannot
see whether you rated it or what you wrote.

## What the app does not do

- No accounts, sign-in, or identifiers.
- No analytics, crash reporting, advertising, or tracking SDKs.
- No network requests of any kind.
- No cloud backup and no device-to-device transfer of app data.
- No selling or sharing of data with anyone, because no data is collected.

## Children

ScrollSmack is not directed at children and collects no data from anyone,
including children.

## Permissions summary

| Permission | Why |
|---|---|
| Usage access | Measure continuous use of the apps you selected |
| Display over other apps | Draw the full-screen interruption when you cross your limit |
| Foreground service | Keep the timer running while you use other apps |
| Notifications | Show the notification Android requires while the timer runs, and reminders after you turn ScrollSmack off |
| Ignore battery optimizations (optional) | Stop the system from killing the timer early |
| Run at startup | Restart the timer after a phone restart or app update if you left it on, and restore reminders |

## Changes

If this policy ever changes, the updated version will be posted at this same
address with a new "last updated" date.

## Contact

Questions about this policy: **scrollsmack.app@gmail.com**
