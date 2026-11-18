# TRANSFORMERX — Transformer Engineering & Analysis Suite

A responsive, single-page educational website for transformer calculations.

## Features
- Single-phase transformer EMF equation calculator with selectable outputs and area units.
- Transformation ratio calculator.
- Open-circuit and short-circuit test calculations: shunt parameters, series parameters, approximate efficiency and voltage regulation.
- Conceptual equivalent-circuit diagrams referred to primary and secondary.
- Eight-period all-day efficiency schedule.
- Parallel transformer load-sharing calculator using complex percentage impedances.
- Responsive layout for mobile and desktop.

## Run locally
Open `index.html` in a modern browser. No installation, server, API key or external library is required.

## Publish with GitHub Pages
1. Create a public GitHub repository (for example, `transformerx`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Wait for deployment and open the published URL.

## Engineering assumptions and limitations
- EMF calculation uses the sinusoidal transformer equation E = 4.44 f Φm N.
- Transformation ratio uses the ideal transformer relationship V2/V1 = N2/N1.
- OC and SC readings must be measured on the same side. The SC wattmeter reading is treated as rated-current copper loss for efficiency estimates.
- Voltage regulation is an approximate equivalent-circuit estimate.
- All-day efficiency assumes constant core loss for 24 hours and copper loss proportional to the square of load current.
- Parallel load sharing assumes compatible voltage ratios, polarity, phase sequence and frequency. Unequal-ratio circulating currents are not modelled.
- This is an educational aid; verify results against course notes, laboratory readings and instructor guidance.
