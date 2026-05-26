# Project 2: Intel Sustainability Timeline

An interactive webpage presenting Intel's sustainability journey from 1968 to 2024 in a horizontally scrollable timeline format.

## Overview

This project showcases key milestones in Intel's history — from its founding through its most recent environmental commitments — using a card-based timeline layout with smooth hover effects and responsive design.

## Features

- **Horizontal scrollable timeline** with scroll-snap for card-by-card navigation
- **Hover animations** — cards lift on hover and images scale subtly
- **Responsive layout** — adapts to both desktop and mobile screen sizes
- **Custom scrollbar styling** using Intel's brand blue (`#0071c5`)
- **Intel branding** — SVG logo in the header, favicon, and brand color palette throughout

## Project Structure

```
GCA-Intel-Timeline/
├── index.html        # Main page with timeline cards
├── style.css         # All styling, animations, and responsive rules
└── img/
    ├── intel-header-logo.svg         # Intel logo (header)
    ├── intel.png                     # Favicon
    ├── 1968-intel-founded.png
    ├── 1971-microprocessor.png
    ├── 1978-8086.png
    ├── 1985-386.png
    ├── 2006-emissions.png
    ├── 2020-rise.png
    ├── 2022-netzero.png
    ├── 2023-renewable.png
    └── 2024-summit.png
```

## Timeline Milestones

| Year | Milestone |
|------|-----------|
| 1968 | Intel founded by Robert Noyce and Gordon Moore |
| 1971 | World's first commercial microprocessor (Intel 4004) |
| 1978 | Launch of the 8086, establishing the x86 architecture |
| 1985 | 386 processor introduces 32-bit architecture |
| 2006 | Peak greenhouse gas emissions — the turning point |
| 2020 | RISE strategy and 2030 sustainability goals launched |
| 2022 | Net-zero GHG emissions commitment by 2040 announced |
| 2023 | 99% renewable electricity achieved worldwide |
| 2024 | First Intel Sustainability Summit held |

## Getting Started

1. Launch a Codespace from the GitHub repository
2. Open `index.html` in the browser preview
3. Commit and push your changes regularly to avoid losing progress

## Technologies Used

- HTML5
- CSS3 (Flexbox, transitions, scroll-snap, media queries)

## Learning Goals

- Working with SVG assets and controlling them via CSS
- Building horizontal scroll layouts with Flexbox
- Implementing CSS transitions and hover effects
- Writing responsive styles with media queries
