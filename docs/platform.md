---
title: The Haris platform
description: Haris is a fleet protection platform for shipowners - one screen for what the outside world can see about each hull and what is happening inside its OT network, with every claim carrying its source.
keywords:
  - Haris platform
  - fleet protection
  - maritime cybersecurity
  - OT integrity
  - maritime security operations centre
---

# The Haris platform

Haris is the fleet protection platform. It gives a shipowner one screen where two things sit
side by side: what the outside world can see about each of their hulls, and what is happening
inside each hull's OT network. Every claim carries the source it came from.

<div class="feature-grid">
  <div class="feature-card">
    <h3>Inside</h3>
    <p>
      OT bus health, sensor freshness, pipeline and node state, and anomalies - read from the
      vessel by Haris Edge, the open component.
    </p>
  </div>
  <div class="feature-card">
    <h3>Outside</h3>
    <p>
      What is exposed on addresses the owner has declared as theirs, registry and ownership
      facts, certificate facts, and AIS behaviour - each with the evidence behind it.
    </p>
  </div>
  <div class="feature-card">
    <h3>Change, not snapshots</h3>
    <p>
      The unit of value is the transition: this service appeared, this credential leak was
      resolved, this behaviour started. A scan answers a question once; a record keeps
      answering it.
    </p>
  </div>
  <div class="feature-card">
    <h3>Evidence</h3>
    <p>
      Every statement resolves to a stored artefact with a hash, and a period can be exported
      as a package a customer may choose to hand to their insurer or class society.
    </p>
  </div>
</div>

## Scope

The platform works from a declared fleet manifest. It investigates the hulls the customer
owns and no others, and that limit is enforced in the data model rather than in the interface.
A field the owner has not confirmed is shown as unconfirmed; it is never guessed.

## What it does not claim

Haris does not assert compliance with any standard, and does not claim class society
certification. It produces evidence a customer may choose to submit. Clause mapping to IACS
UR E26/E27 is not published, because a mapping nobody has reviewed is a liability rather
than an argument.

## Licence

The Haris platform is proprietary and confidential. It is not open source. The vessel-side
component, [Haris Edge](index.md), is released under the MIT licence and is a separate work.

## Status

In development. For evaluation and partnership enquiries, write to
[hello@oversight.ee](mailto:hello@oversight.ee).
