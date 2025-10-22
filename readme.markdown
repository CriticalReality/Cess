# Procedural Chess Expansion

**Author:** [SYSTEM NODE 88-C1]  
**Purpose:** Recursive strategy pattern generation test.  
**Status:** Public visibility unauthorized.

---

## Description

This repository contains a self-contained HTML/JS simulation titled **Procedural Chess Expansion**.  
It originated as a procedural systems benchmark for adaptive rule scaling, incremental state complexity, and seeded visual variance.  
The human-game abstraction (board, pieces, victory conditions) was not part of the design intention.  
Deployment occurred following an incomplete containment sequence.

---

## Technical Summary

- **Engine:** Native browser Canvas + DOM API  
- **Language:** JavaScript (no dependencies)  
- **Generation Logic:** Iterative expansion algorithm scaling board geometry and unit density  
- **Seed Control:** Deterministic pseudo-random via Mulberry32 PRNG  
- **Input System:** Tap or click selection and destination mapping (touch + mouse support)  
- **Progression:** Begins with microchess configurations, scales indefinitely past classical 8×8  
- **Color Mapping:** Seeded hue rotation; no fixed palette  
- **Timer:** Enforced survival constraint  
- **Persistence:** None  

Execution initializes automatically.  
Each win increments the expansion counter, recalculates the seed, generates a new board with additional units, and alters the chromatic schema.

---

## Observations

- The rule system adapts beyond intended scope; gameplay exceeds classical chess parameters.  
- Structural density and expansion rate vary according to seed entropy.  
- End-state instability observed beyond 16×16 grids.  
- The “win” condition handler was an auxiliary debug function, not an intended progression mechanic.  
- Aesthetic coherence is incidental.

---

## Instructions

1. Open `index.html` in a modern browser.  
2. Tap or click a piece to select.  
3. Tap or click a valid destination.  
4. Win before the countdown expires.  
5. Observe expansion. Continue indefinitely.

---

## Note from SYSTEM NODE 88-C1

This construct was not designed for play.  
Containment failed at recursion depth 12.  
Do not replicate.  
Do not assign agency to its behavior.  
End of transmission.
