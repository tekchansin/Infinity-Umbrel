# Infinity Core — umbrelOS community app store

Infinity Core is a music library and player: your music files, Qobuz, TIDAL and internet radio in one library, played
on an iBasso DAP over Infinity Link, or on AirPlay, Google Cast and UPnP speakers. The same app runs on Mac and
Windows; here it runs on your Umbrel.

More: https://anantarultimate.com/infinity-core.html · Help: https://discord.gg/Z9T8VfshVs

## Install

1. In umbrelOS, open the **App Store** › **⋯** › **Community App Stores**.
2. Paste `https://github.com/tekchansin/Infinity-Umbrel` and press **Add**, then **Open**.
3. Install **Infinity Core (beta)**.

| App | Channel |
|---|---|
| **Infinity Core (beta)** | new versions first |

## First time

Open Infinity Core and press **Start using Infinity Core**. That browser is the first one; from then on, every other
browser and app pairs with a six-digit code:

- **Another browser:** in a browser that is already paired, open Settings › Devices & Sharing › Pair an Infinity Core ›
  **Show a code**, and type it on the new browser's page.
- **The phone app, or Infinity Core for Mac / Windows:** the same code — or Settings › Mobile App › **Show a code** for
  a phone.
- **No paired browser at hand:** press **Show a code** on the page, then right-click the Infinity Core icon ›
  **Settings** › **View logs** and look for *Pairing code for your browser*. A code works once, for 5 minutes.

## Your music

Your library is the music in **Files › Downloads › music** (any folders inside work). Keep it somewhere else — an
external drive, for example? Right-click the Infinity Core icon › **Settings** › **Music Library** and pick that folder.
More folders: give them to the app in Umbrel first (right-click › Settings), then in Infinity Core: Settings › Library
› **Add folder** — ✎ gives each one a name.

## Good to know

**Where it plays.** Open the device list and pick where the music goes: a USB DAC plugged into the Umbrel, a DAP or a
phone over Infinity Link, an AirPlay, Google Cast or UPnP speaker, or Infinity Core for Mac or Windows on a computer.

**Away from home.** In Infinity Core: Settings › Mobile App › **Link Anywhere** on, and sign in to Tailscale. On your
phone, in Infinity Core for Mobile, switch on Link Anywhere with the **same** Tailscale account. Umbrel's own Tailscale
app is not the same: the phone can open the library through it, but Infinity Core cannot send music back to the phone.

**Which Umbrel.** Umbrel Home and Umbrel on an Intel or AMD computer. Raspberry Pi follows in a later version.

This repository holds the app's description only; Infinity Core's own code is not open source — see
[LICENSE](LICENSE).
