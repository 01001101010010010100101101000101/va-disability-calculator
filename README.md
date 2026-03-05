# va-disability-calculator
A lightweight, browser-based US VA Disability Claims Calculator

This repository contains a single `index.html` file that acts as the full
application. Open it in a modern browser to access the **Ultimate VA Disability
Calculator 2026**. The calculator is styled with Tailwind CSS, uses Font
Awesome icons, and performs all computations client-side with vanilla JavaScript.

## Features

- Add multiple service-connected conditions by rating and extremity (for
  bilateral factors).
- Automatically combine ratings using VA math and apply the 10% bilateral
  factor when appropriate.
- Track dependents (spouse, parents, children) and optionally Aid &
  Attendance for spouse.
- Live display of combined percentage, exact raw value, monthly compensation
  based on 2026 rates (with 2.8% COLA), and a graphical progress ring.
- Responsive layout with a sticky results panel for easy viewing on
  desktop and mobile.

## Usage

1. Clone or download the repository.
2. Open `index.html` in your web browser (no server required).
3. Use the controls to add conditions and dependents; results update
   automatically.
4. Click **Reset All** in the navigation bar to clear the calculator.

## Development

The application is a single HTML file; feel free to modify the inline CSS
or JavaScript to add features or update rates for future years.

> **Note:** This tool is for informational purposes only and is not an
> official VA product.

