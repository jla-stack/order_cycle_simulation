# Order Cycle Simulation — FinTech PoC Engine

A 100% AI-generated interactive proof of concept for an institutional Order Management System (OMS) lifecycle.

No build tools, no frameworks, no dependencies. Just a single `.html` file that runs right in your browser.

---

## 🛠️ How This Was Built

1. **Mapped the Order Cycle:** Drafted an end-to-end institutional scenario (`End-to-End Order Cycle.pdf`).
2. **Asked Gemini:** Pushed the scenario into Gemini Flash 3.6 Canvas to generate a full interactive simulation in a single HTML file.
3. **Tweaked the UX:** Refined the prompts to polish the UI, clean up the blotters, fix the state loop, and separate internal logs from external FIX/SWIFT protocol streams.

---

## 💡 Why This Exists

Let’s be honest: **the devil is in the details**. This tool won't replace a Product Manager or a Business Analyst just yet, but it’s surprisingly useful for putting ideas on paper in 10 minutes instead of arguing over mockups for two weeks.

Think of it as a quick sandbox to demonstrate trade flows, test state logic, and pitch concepts to stakeholders without writing a single line of frontend code yourself.

---

## 🚀 How to Run It

1. Clone the repo.
2. Double-click `index.html` (or open it in any browser).
3. Flip the **AUTO-ADVANCE** switch and watch the order cycle run itself.