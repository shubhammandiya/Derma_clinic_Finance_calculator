# Clinic Financial Engine

A visual, interactive financial pipeline calculator designed to model the feasibility, cash flow, and break-even points for a modern Dermatology & Aesthetics Clinic. 

Built as a lightweight, zero-dependency, single-file web application that runs directly in the browser on both desktop and mobile.

## Features
* **Visual Data Pipeline:** Follow the money from daily footfall (inflow) down to monthly survival costs (OPEX) and loan repayments.
* **CAPEX to Loan Engine:** Automatically calculates excess upfront setup costs (Interiors, Furniture, Lasers) into a clinic loan, generating a monthly EMI that feeds into the survival engine.
* **Monthly vs. Daily Scaling:** Separates daily base volume (OPD/Medical) from slower-scaling monthly volume (Aesthetics/Lasers).
* **Instant Payback Tracker:** Calculates exact "Months to Recover" for out-of-pocket down payments based on the net monthly surplus.
* **Break-Even Radar:** Computes the exact daily OPD footfall needed to keep the lights on and pay the doctors.

## How to Use
Since this is a static HTML file, no build tools are required.
1. Clone the repository.
2. Open `index.html` in any modern web browser (Chrome, Safari, Edge).
3. Adjust the sliders to simulate different business environments and pricing strategies.

## Live Demo
*(Note: Once you push this to GitHub, go to **Settings > Pages**, deploy from the `main` branch, and paste your live `https://<username>.github.io/<repo-name>` link here!)*