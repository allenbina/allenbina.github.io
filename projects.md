---
layout: default
title: Projects
permalink: /projects/
---

# Projects

A short list of things I build outside work. The headline ones are open source; some are personal infrastructure I happen to run; a couple are physical builds that sat on a workbench until they were done.

<article class="project featured">
  <h3>chatwire <span class="tag">flagship · beta · 2026</span></h3>
  <p>A self-hosted iMessage bridge for macOS. Telegram-first phone client (no dedicated app needed), plugin architecture, no relay servers, zero telemetry. <code>pipx install chatwire</code>.</p>
  <p>Built solo in collaboration with Claude on a $100/month subscription, 201 commits. It's the project I run myself, every day, on my own hardware.</p>
  <p class="links">
    <a href="https://allenbina.github.io/chatwire/">landing page</a>
    <a href="https://github.com/allenbina/chatwire">repo</a>
    <a href="https://github.com/allenbina/press">press kit</a>
    <a href="https://dsc.gg/chatwire">discord</a>
  </p>
</article>

<article class="project">
  <h3>dactyl manuform <span class="tag">hardware · 2025</span></h3>
  <p>Custom split mechanical keyboard. Hand-wired by me from raw switches and an RP2040 microcontroller, 3D-printed shell I printed on my own printer, KMK firmware. Daily driver.</p>
  <p>The build log lives in the repo. There were a lot of iterations.</p>
  <p class="links">
    <a href="https://github.com/allenbina/dactyl_manuform">repo &amp; build log</a>
  </p>
</article>

<article class="project">
  <h3>homelab <span class="tag">infrastructure · ongoing</span></h3>
  <p>k3s Kubernetes cluster across HP EliteDesk mini PCs and a Pi 5. GitOps via Argo CD. MergerFS NAS built from shucked drives. Cloudflare Zero Trust tunnels for external access. Home Assistant wired into more sensors and automations than I care to count.</p>
  <p>Notable services I run: Plex / Sonarr / Radarr stack, Vaultwarden, Immich for photos, Uptime Kuma (with a separate watchdog Kuma watching it), Authentik, ntfy, and a Kestra automation engine that handles infrastructure alerts.</p>
  <p class="links">
    <em style="color: var(--fg-faint); font-size: 0.85rem;">private repo for now — happy to walk through it on request</em>
  </p>
</article>

<article class="project">
  <h3>chatwire plugins <span class="tag">open source · 2026</span></h3>
  <p>Companion repos for chatwire — the Telegram bridge, the ntfy notifier, and the plugin SDK. Each is its own pip-installable package; chatwire's plugin system auto-discovers them and builds the settings UI from their config schemas.</p>
  <p class="links">
    <a href="https://github.com/allenbina/chatwire-telegram">chatwire-telegram</a>
    <a href="https://github.com/allenbina/chatwire-ntfy">chatwire-ntfy</a>
    <a href="https://github.com/allenbina/chatwire-plugins">chatwire-plugins</a>
    <a href="https://github.com/allenbina/homebrew-tap">homebrew-tap</a>
  </p>
</article>

---

More projects coming as I sort through old work and decide what's worth showing. If you're looking for something specific, [my GitHub](https://github.com/allenbina) has the full inventory.
