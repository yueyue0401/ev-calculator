# EV Calculator

A lightweight browser-based EV charging planner for the Toyota CHR and other similar small EVs.

## What it does

- Estimates charging window duration and battery gain
- Calculates driving range from current battery percentage
- Computes the required battery percentage for a given trip distance
- Uses PG&E EV2-A-style residential pricing for cost estimates

## Notes

- The default CHR charging rate is set to **2% per hour** for slow charging
- The calculator assumes roughly **2 miles per 1% battery** as a baseline
- Results are displayed with mobile-friendly bullets and responsive styling

## Running locally

1. Open `index.html` in a browser
2. Adjust the values and click the buttons to see estimates

## Customization

- Update the default EV assumptions in `index.html`
- Change the rate season or pricing labels directly in the UI markup
- The app is intentionally minimal and works without a build step
