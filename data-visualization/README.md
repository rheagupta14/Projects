# Colormapping U.S. Presidential Election Data

**Course:** CMSC 23900 — Data Visualization  
**Project Type:** Two-person course project  
**Stack:** JavaScript, D3.js, HTML, CSS  
**Status:** Private course repository (code available upon request)

## Overview

This project is an interactive web-based visualization for exploring
U.S. Presidential election results across time and geography.

The visualization integrates multiple coordinated views—including a
hex-based U.S. map, balance bars, and a scatterplot—to support exploration
of voting patterns, political leaning, and total vote magnitude across
election years.

The focus of the project is not only on visual encoding, but also on
data wrangling, scale design, and user interaction.

## Visualization Components

The interface consists of several linked elements:

- **Balance bars** showing Democratic vs. Republican popular votes and
  Electoral College votes for the selected year.
- **Hexagonal U.S. map**, with each state represented as a hex tile and
  colored according to the active colormap mode.
- **Scatterplot view** displaying states in a parameterized data space,
  overlaid on a dynamically generated colormap.
- **Timeline slider** for selecting election years.
- **Mode controls** for switching between different visual encodings.

Hovering over a state in either the map or the scatterplot highlights the
corresponding state in both views and displays a detailed tooltip with
state-level election data.

## Colormap and Interaction Modes

The visualization supports multiple modes for interpreting the data:

- **RVD (Republican vs. Democratic):**  
  States are positioned by Republican and Democratic vote totals, and
  colored discretely based on the winning party.

- **PUR (Purple scale):**  
  A continuous colormap interpolates between Democratic and Republican
  colors based on political leaning.

- **LVA (Lean vs. Amount):**  
  Political leaning is plotted against total voting amount, using luminance
  to encode vote magnitude and hue to encode party preference.

All visual elements update with smooth animated transitions when the year
or mode changes.

## Data Sources

Election data was compiled from publicly available Wikipedia election
results pages and processed into CSV format for visualization.
The dataset includes state-level Democratic and Republican popular vote
counts and Electoral College votes across multiple election years.

Third-party candidates and elections with non-binary party outcomes were
excluded to simplify comparison across years.

## Code Availability

This project was completed as part of a University of Chicago course.
In accordance with academic integrity guidelines, the source code is not
publicly available.

## Demo

[Download short interaction demo](demo.mov)
**Code available upon request.**
