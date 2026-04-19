# ♾️ CloudZero: Sustainable Cloud & AI Analyzer

**CloudZero** is a premium, responsive SaaS dashboard designed to provide real-time financial and environmental insights into Cloud and AI infrastructure. Built for the modern web, it empowers developers to optimize for both cost and carbon footprint.

## 🚀 Live Demo
**[Launch CloudZero Dashboard](https://nikk18.github.io/CloudZero/)**

---

## ✨ Key Features
* **Real-Time Cloud Calculator**: Instant cost comparison across AWS, Azure, and GCP localized in Indian Rupees (₹).
* **Live Market Rates**: Automatically syncs the current USD-to-INR exchange rate via `open.er-api.com`.
* **AI Energy Impact Meter**: Real-time token counting and energy consumption estimation (Wh) for LLM prompts.
* **Carbon Footprint Tracking**: Visualizes CO₂ emissions based on computational intensity.
* **Fully Responsive UI**: Optimized for perfect viewing on mobile, tablet, and desktop devices.
* **Visual Analytics**: Interactive bar, pie, and line charts providing deep-dive cost breakdowns.

---

## 🛠️ Tech Stack
* **Frontend**: HTML5, CSS3 (Modern SaaS Dark Mode aesthetic).
* **Visualizations**: Chart.js.
* **API**: Exchange Rate API (Real-time financial data).
* **Logic**: Vanilla JavaScript (ES6+).

---

## 📐 Optimization Logic
* **Token Heuristic**: `1 Token ≈ 1.3 Words`.
* **Energy Model**: 
    * Large Models (GPT-4/Opus): `0.0003 Wh per token`.
    * Small Models (GPT-3.5/Haiku): `0.00005 Wh per token`.
* **Carbon Intensity**: `Energy (Wh) * 0.475` (Grams of CO₂).

---

## 📂 Repository Structure
* `index.html`: Core Cloud Cost Calculator.
* `tokens.html`: AI Energy & Token Impact Dashboard.
* `comparison.html`: Detailed E-commerce use-case comparison.

---

## 👥 Project Group
Developed by **Nikk18** and Team for the "Sustainable Energy in Cloud & AI Systems" academic project.
