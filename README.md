# ☀️ Philippine Solar PV System Calculator

An interactive, front-end web dashboard designed to estimate solar PV system sizing, financial returns (ROI), and environmental impact, specifically calibrated for the Philippine energy market.

## 📊 Features

* **Dynamic System Sizing:** Calculates recommended System Capacity (kWp) based on targeted bill reduction and current Meralco/coop electricity rates.
* **Real-time Financials:** Instantly computes Estimated Total Cost, Monthly/Annual Savings, and the Simple Payback Period (ROI) using live input variables.
* **Environmental Impact:** Translates clean energy generation into tangible metrics (Annual CO₂ Avoided in kg and Equivalent Trees Planted).
* **Spatial Estimation:** Provides a rough estimate of the unshaded roof space required (in square meters) for the system.
* **Export Ready:** Features a print-optimized CSS layout to easily generate clean, professional PDF quotes.

## 🛠️ Tech Stack

Built entirely with standard web technologies for maximum portability and zero-dependency deployment:
* **HTML5**
* **CSS3** (with CSS Variables and CSS Grid for responsive layout)
* **Vanilla JavaScript** (ES6+)

## 🇵🇭 Philippine-Specific Calibration

The underlying math engine uses established Philippine solar industry benchmarks to ensure realistic estimations rather than generic global averages:
* **Solar Irradiance:** Calculated using an average of 130 Peak Sun Hours (PSH) per month (~4.33 PSH/day).
* **System Efficiency:** Defaulted to a conservative 80% to account for local heat degradation, inverter losses, and wiring.
* **Grid Emission Factor:** Uses ~0.65 kg CO₂ per kWh to calculate environmental impact, reflecting the current baseload profile of the Philippine power grid.

## 🚀 How to Use

Since this is a static client-side application, no build process or local server is required. 

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.
3. Adjust the sliders and inputs to see real-time calculations.

