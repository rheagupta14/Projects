# GeoElections Web Visualization

**Type:** Interactive Web Visualization  
**Tools:** JavaScript, HTML/CSS, MapLibre GL JS, PMTiles  
**Affiliation:** University of Chicago — Summer Institute of Social Research Methods (SISRM), June–September 2025  
**Faculty Mentor:** Prof. Fabricio Vasselai

## Overview

This project is an interactive web-based dashboard for visualizing large-scale,
high-resolution, georeferenced election results. It was developed as part of the
University of Chicago’s Summer Institute of Social Research Methods (SISRM) in
collaboration with Prof. Fabricio Vasselai.

The visualization supports both winner-based and multi-party blended views,
allowing users to explore electoral outcomes across space, time, and party systems.

## Features

- Interactive map-based visualization of election results using vector tiles
- Toggleable visualization modes (winner buckets vs. multi-party blends)
- Custom party color selection and gradient controls
- Export of map views as static images for reporting and presentation
- Responsive UI for exploratory data analysis

## Data & Sources

The project uses large-scale geospatial election datasets compiled for the
**geoElections** project, a global election results initiative led by Prof. Vasselai.
Data include results from over 1,000 elections across nearly all countries, processed
into vector tile formats for efficient client-side rendering.

## Technical Notes

- Built entirely client-side using JavaScript and MapLibre GL JS
- PMTiles used for efficient delivery of large vector tile datasets
- Optimized to handle high-resolution geospatial data without server-side rendering

## Project Structure

- `final/` – Consolidated, viewable version of the website

## How to Run Locally

Open `final/index.html` using a local development server.

**VS Code Live Server**

- Right-click `final/index.html` → _Open with Live Server_

**Python**

```bash
python -m http.server
```
