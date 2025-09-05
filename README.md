# msc-thesis-appendices

# MSc Cartography Thesis Online Appendices

This repository contains supporting materials for my thesis:
**“Visualising 4D topographic change objects extracted from LiDAR time series”** (2025).

## Contents
- `code/` – Jupyter notebooks and scripts (4D-OBC processing and visualisation).
- `static maps/` – High-resolution figures used in the thesis.
- `animated maps/` – MP4/GIF animations referenced in Chapter 3.
- `interactive maps/` – Interactive map (HTML). A live version is hosted via GitHub Pages (link below).
- `survey/` – Questionnaire and anonymised responses.
- `data/` – csv file containing dataset timestamps.

## Live interactive map
https://maryam-source.github.io/thesis-interactive-maps/interactive_map_duration.html

https://maryam-source.github.io/thesis-interactive-maps/interactive_map_magnitude.html

https://maryam-source.github.io/thesis-interactive-maps/interactive_map_combination.html

https://maryam-source.github.io/thesis-interactive-maps/interactive_map_timestamps.html

## Reproduce environment
```bash
conda env create -f code/environment.yml
conda activate obc-env
# or: pip install -r code/requirements.txt

