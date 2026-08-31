# Order Cycle Simulation — FinTech PoC Engine

The devil is in the details. 

This repository is **not** a working Order Management System—it is a basic UI mockup generated purely by AI in 10 minutes. While it looks slick at a glance, real trading infrastructure requires deep domain logic that AI cannot build for you.

---

## 🛠️ How This Was Built

1. **Mapped the Concept:** Drafted an initial scenario (`End-to-End Order Cycle.pdf`).
2. **AI-Generated Baseline:** Had Gemini Flash 3.6 Canvas generate a basic 9-state institutional order cycle in a single HTML file.
3. **Pure CSS Layout & Simulation Flow:** Utilized surprisingly powerful CSS Grid and Flexbox flows to drive the responsive workspace, state views, and multi-panel alignment. Combined with lightweight JS, this creates a convincing simulation of live activity without writing complex frontend frameworks by hand.

---

## 💡 What This Visual Prototype Shows

* **CSS-Driven Layout Engine:** A single-page structure using native CSS layout flows to keep the high-density blotter, pinned action box, and terminal footers perfectly aligned across viewports.
* **9-State Lifecycle:** A surface-level walkthrough from portfolio rebalancing to custody settlement.
* **Pro Blotter:** High-density, multi-symbol grid mimicking real terminal UI density (Bloomberg AIM / Charles River style).
* **Auto-Advance Loop:** Simulated straight-through processing (STP) with dynamic speed controls.
* **Separated Protocol Streams:** Basic separation of internal business audit logs (`int_messages`) from dummy FIX 4.2 and SWIFT gateway messages (`ext_messages`).

---

## 🎯 The Reality Check

Will AI replace a Product Manager or Business Analyst today? Absolutely not. 

The moment you dig into real FIX engine state machines, partial fill calculations, or complex regulatory edge cases, the AI facade falls apart. 

However, as a visual sandbox to put a few ideas on paper and test user flows before wasting weeks arguing over slide decks? It is surprisingly useful.

---

## 🚀 How to Run It

1. Clone or download this repo.
2. Double-click `index.html` (or open it in any modern browser).
3. Flip the **AUTO-ADVANCE** toggle to watch the simulated order cycle run.