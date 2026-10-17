# Mapillary Urban Segmentation Viewer

Interactive viewer for street-level imagery with AI-powered semantic segmentation.

## Features

- Fetches images from Mapillary API
- Runs Segformer segmentation (buildings, sky, vegetation, road, etc.)
- Interactive map with Leaflet
- Live charts with Plotly
- Toggle between original and segmentation view

## Live Demo

Coming soon: https://nasimnou.github.io/mapillary-urban-viewer/

## Tech Stack

- Python: Mapillary API, Segformer, PyTorch
- JavaScript: Leaflet, Plotly
- Data: Mapillary Street-Level Imagery

## Setup

1. Clone the repo:
   git clone https://github.com/nasimnou/mapillary-urban-viewer.git
   cd mapillary-urban-viewer

2. Install dependencies:
   pip install -r requirements.txt

3. Create .env file:
   MLY_ACCESS_TOKEN=your_token_here

4. Run Urban Viewer.ipynb in Jupyter

## Structure

- Urban Viewer.ipynb - Main pipeline
- index.html - Generated viewer
- segmentation/ - Segmentation overlays
