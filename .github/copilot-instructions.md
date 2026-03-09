# Copilot Instructions

This repository contains data files used for radar chart visualization.

## Repository Structure

- `example_radar.csv` — CSV data file with radar chart entries (name, ring, quadrant, isNew, description).
- `jsonTest.json` — JSON data file with technology radar entries (name, ring, quadrant, isNew, description).

## Data Format

### CSV (`example_radar.csv`)
Each row represents a technology entry with the following fields:
- `name`: Name of the technology
- `ring`: Adoption stage (e.g., Scale, Research, Innovate)
- `quadrant`: Category (e.g., Experience client, Employeur, Business, Villes)
- `isNew`: Whether the entry is new (TRUE/FALSE)
- `description`: Short description of the technology

### JSON (`jsonTest.json`)
Array of objects, each with:
- `name`: Name of the technology
- `ring`: Adoption stage (adopt, trial, assess, hold)
- `quadrant`: Category (tools, techniques, platforms, languages & frameworks)
- `isNew`: Whether the entry is new ("TRUE"/"FALSE")
- `description`: Short description of the technology

## Guidelines

- When adding new entries, follow the existing data format for each file.
- Keep descriptions concise.
- Use consistent values for `ring` and `quadrant` within each file.
