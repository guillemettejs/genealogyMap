# 🗺️ Genealogy Timeline Map

This project visualizes the birth and death locations of thousands of individuals on an interactive world map with a dynamic timeline.

## 🎯 Purpose

To explore personal or community ancestry over time, observing migrations, lifespan patterns, and historical trends.

## 🛠️ Features

- Interactive timeline from 1600 to 2025
- Smooth animation of individuals moving from birth to death location
- Clickable dots showing birth/death details
- Search bar to find cities or regions
- Precision mode for slow scrubbing
- Color-coded age progression and fade-out effect after death
- Optimized to load tens of thousands of individuals

## 📂 Data Files

- `data_v4_min.json` — Minified core dataset
- `baked_positions_*.json` — Precomputed yearly positions split by time period for better performance

## 🚀 Live Demo

🌍 Visit the map here:  
**[https://yourusername.github.io/genealogy-map](https://yourusername.github.io/genealogy-map)**  
*(Replace with your real link once GitHub Pages is active)*

## 🧠 Tech Stack

- HTML + JavaScript
- [Leaflet.js](https://leafletjs.com/) for maps
- OpenStreetMap tiles
- Hosted on GitHub Pages

## 🧳 Getting Started (Local)

If you want to run it locally:

```bash
python -m http.server
