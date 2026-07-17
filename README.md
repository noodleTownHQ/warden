<p align="center">
  <img src="assets/warden-icon.png" width="140" alt="Warden">
</p>

<h1 align="center">Warden</h1>

<p align="center"><strong>Know what runs in the background on your Mac — and get told when it stops.</strong></p>

Warden is a local-first macOS app that shows you every background job on your
machine, tells you what each one is and whether it's alive, and sends a
notification the moment one **fails or goes quiet** — a local dead-man's-switch,
with no cloud account.

## Download

**[⬇︎ Download Warden.dmg](../../releases/latest)**

1. Open the `.dmg` and drag **Warden** to Applications.
2. Launch it. On first run it asks to enable its background helper — approve it in
   **System Settings → General → Login Items & Extensions**.

Signed with an Apple Developer ID and notarized by Apple, so it opens with a
normal double-click. **Requires macOS 26 or later.**

## What it does

- **See everything** — every launchd background job, sorted into your own scripts
  vs. apps, with a plain-English name for each (no more mystery `python3` rows).
- **Tidy it up** — adopt your jobs into Warden so System Settings shows a single
  "Warden" entry instead of a pile of unidentified helpers. Reversible.
- **Never miss a silent failure** — per-job health checks and a staleness alarm
  notify you when a job fails, overruns, or quietly stops doing its work.
- **Stay in control** — pause, resume, or run any job on demand.

## Privacy

Runs entirely on your Mac, at your normal user permissions. Nothing is uploaded;
there's no account, server, or telemetry.

---

© 2026 Nural Choudhury. All rights reserved.
