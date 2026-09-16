# CityTrace

**CityTrace** is a civic issue reporting and resolution verification platform that gives citizens transparent, evidence-based control over their complaints.

## The problem

Citizens can report issues like potholes, broken streetlights, garbage, water leakage, and damaged roads — but once a complaint is marked "Resolved," there's usually no real proof it was fixed, and the person who reported it rarely gets a say in confirming that.

This creates three problems:

1. **No reliable proof** — a "Resolved" label doesn't mean the issue is actually fixed.
2. **Evidence can be questionable** — old, wrong, or reused photos can be submitted as proof.
3. **Citizens lose control** — the person who reported the issue rarely gets a meaningful chance to confirm it was really resolved.

## How CityTrace fixes it

Instead of a complaint going straight from **Reported** to **Resolved**, CityTrace adds a verification layer in between:
Reported → Work Done → Proof Submitted → Verification → Resolved

- **Reported** — citizen files the issue with a photo, geotag, and timestamp
- **Work done** — department marks the fix complete (this alone can't close the case)
- **Proof submitted** — department uploads a before/after photo
- **Verification** — an automated engine checks time, location, and image difference
- **Resolved** — the citizen confirms the fix in person; only then does the case close

If the citizen disputes it, the case reopens and loops back to "work done."

## Features

- Case ticket for every complaint with a unique ID, geotag, and timestamp
- Before/after photo comparison for proof of work
- Automated verification checks (timestamp, location, image diff)
- Citizen confirm/dispute step before a case can close
- Department trust scores based on confirmed vs. disputed resolutions

## Tech

- HTML, CSS, JavaScript (single-page site)

## Team

- @comenater and collaborators

## Status

Prototype / concept build.
