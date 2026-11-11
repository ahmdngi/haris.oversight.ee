---
title: Haris Edge - open vessel telemetry component
description: "Haris Edge is the open, MIT-licensed vessel-side component of the Haris platform: NMEA 0183, NMEA 2000 and Signal K collection, onboard normalization, health monitoring, and encrypted transport to shore."
keywords:
  - Haris Edge
  - maritime telemetry
  - vessel data collection
  - Signal K
  - NMEA 2000
  - open source maritime
  - MIT licensed
---

# Haris Edge Docs

<div class="hero-shell">
  <div class="hero-kicker">Open component of the Haris platform</div>
  <h1>Haris Edge</h1>
  <p>
    Haris Edge is the vessel-side component: it collects maritime telemetry from
    NMEA 0183, NMEA 2000 and Signal K sources, normalizes it onboard, monitors
    its own health, and ships it to shore over an encrypted link. It is released
    under the MIT licence, so an operator can read exactly what touches their bus.
  </p>
</div>

---

## <span class="section-label">Editions</span> Two things, two licences

<div class="feature-grid">
  <div class="feature-card">
    <h3>Haris Edge - this site</h3>
    <p>
      The open component. Runs on the vessel, is openly licensed under MIT, and can be
      inspected, forked and deployed without asking anyone. It is what reads the sensors
      and what survives an intermittent link.
    </p>
  </div>
  <div class="feature-card">
    <h3>Haris - the platform</h3>
    <p>
      The commercial product built around it: the fleet-wide view, the outside-in picture,
      the change record and the evidence a customer can hand to an insurer or a class
      society. Proprietary.
    </p>
  </div>
</div>

Haris Edge is a component of the Haris platform, not a cut-down version of it. Both names
belong to the same estate: [the platform is described here](platform.md).

---

## <span class="section-label">Capabilities</span> What the edge does

<div class="feature-grid">
  <div class="feature-card">
    <h3>Collection</h3>
    <p>Collects vessel telemetry from NMEA 0183, NMEA 2000, and Signal K compatible sources in an edge-first operating model.</p>
  </div>
  <div class="feature-card">
    <h3>Processing</h3>
    <p>Parses, normalizes, and buffers data onboard so collection remains effective even when connectivity is unstable or intermittent.</p>
  </div>
  <div class="feature-card">
    <h3>Operations</h3>
    <p>Uses Watchtower automation to provision service state, storage, connectivity, telemetry freshness, and core-side observability.</p>
  </div>
  <div class="feature-card">
    <h3>Security</h3>
    <p>Applies encrypted transport, fail-closed assumptions, restricted services, and deployment controls as part of a layered security posture.</p>
  </div>
</div>

## <span class="section-label">Operational Model</span> Why edge-first matters

- Processes and normalizes data on the vessel instead of depending on continuous upstream availability.
- Buffers locally so the node remains functional during unstable or intermittent links.
- Forwards structured telemetry, logs, and health context into SOC and M-SOC workflows.
- Establishes a cleaner trust boundary before data reaches central infrastructure.
- Applies repeatable vessel-edge and M-SOC configuration through Watchtower playbooks.

## <span class="section-label">Licence</span> MIT, and what that means

Haris Edge is MIT licensed. You may use it, modify it, and redistribute it, including inside
a commercial product, provided the copyright notice and permission notice are kept. The
Haris platform is not open source and is not covered by that licence, and nothing on this
site should be read as extending the MIT grant to it.

<div class="cta-panel">
  <p><strong>Recommended reading path:</strong> review the architecture, Watchtower, deployment, and security pages in sequence before preparing a vessel installation or core-side integration.</p>
</div>
