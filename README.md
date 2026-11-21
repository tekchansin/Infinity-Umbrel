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

Open Infinity Core. The page asks for a six-digit code, once per browser:

1. Press **Show a code**.
2. Right-click the Infinity Core icon › **Settings** › **View logs**. The code is the line *Pairing code for your
   browser*.
3. Type it on the page. It works once, for 5 minutes.

## Your music

The music in **Files › Downloads** is your library. Put your albums there (any folders inside work).

## Good to know

**Where it plays.** An Umbrel has no sound of its own. Open the device list and pick where the music goes: a DAP or a
phone over Infinity Link, an AirPlay, Google Cast or UPnP speaker, or Infinity Core for Mac or Windows on a computer.

**Away from home.** In Infinity Core: Settings › Mobile App › **Link Anywhere** on, and sign in to Tailscale. On your
phone, in Infinity Core for Mobile, switch on Link Anywhere with the **same** Tailscale account. Umbrel's own Tailscale
app is not the same: the phone can open the library through it, but Infinity Core cannot send music back to the phone.

**Which Umbrel.** Umbrel Home and Umbrel on an Intel or AMD computer. Raspberry Pi follows in a later version.

This repository holds the app's description only; Infinity Core's own code is not open source — see
[LICENSE](LICENSE).
