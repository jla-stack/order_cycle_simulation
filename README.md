# Order Cycle Simulation — FinTech PoC Engine

> **Note:** This repository is an **End-to-End Proof of Concept (PoC)** generated entirely using Artificial Intelligence. It serves as an interactive sandbox to quickly translate institutional trading ideas into a visual, functional prototype.

---

## 📌 Project Overview

This project demonstrates a 9-state institutional Order Management System (OMS) lifecycle, mapping the journey from portfolio rebalancing to custody clearing and post-trade risk synchronization. 

It contains two primary deliverables:
1. **`End-to-End Order Cycle.pdf`**: The foundational business scenario and domain state mapping.
2. **`index.html`** (or `order_cycle_simulation.html`): A single-file, interactive web simulation featuring real-time state transitions, realistic institutional blotters, an auto-advance engine, and dual terminal logs (`int_messages` vs `ext_messages`).

---

## 🛠️ How This Project Was Built

This entire repository was developed through an iterative AI-driven design process:

1. **Order Cycle Specification:** Defined a comprehensive 9-state institutional order lifecycle covering Portfolio Modeling, Basket Netting, Pre-Trade Compliance, Operational Risk Gates, Algorithmic Execution, Allocation, Clearing, and Post-Trade Risk Sync.
2. **Initial Canvas Prototype:** Leveraged **Gemini 3.6 Flash** and its Canvas feature to generate a complete, working HTML/CSS/JS simulation from scratch in a single file.
3. **UX & Architecture Refinements:** Performed prompt engineering iterations to enhance the user experience, including:
   - High-density, professional trading blotter styling (inspired by enterprise systems like Bloomberg AIM and Charles River).
   - A fully automated **Auto-Advance Engine** with dynamic speed controls (3s / 5s / 10s).
   - Strict separation between internal business audit logs (`int_messages`) and external messaging protocol streams (`ext_messages` for FIX 4.2 / SWIFT / ISO 20022).
   - Automatic log resets on closed-loop simulation cycles.

---

## 🎯 Purpose & Scope (Proof of Concept)

This repository is **strictly a Proof of Concept (PoC)**. 

* **Ideation Tool:** Designed to quickly put complex FinTech workflows and UI/UX ideas "on paper" without heavy frontend setup or external dependencies.
* **Zero Dependencies:** The web application is pure HTML5, CSS3, and standard vanilla JavaScript. No external libraries, node modules, or build tools are required.
* **Rapid Demonstration:** Ideal for product managers, system architects, and trading desk engineers looking to pitch, test, or validate order lifecycle concepts with stakeholders.

---

## 🚀 How to Run the Simulation

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)