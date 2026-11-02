# LJC Residential Test-Fit

A browser tool for quick multifamily yield studies. Import a property line (DWG or DXF), set zoning and program, and it tests hundreds of podium, wrap, garden and tower layouts. It then shows the compliant scheme with the most rentable square feet, with unit mix, metrics and a 3D massing.

**Use it:** open the GitHub Pages link for this repository. Nothing to install.

## Features
- DWG / DXF property line import (feet, inches, meters or millimeters).
- Zoning: setbacks by lot-line role, height, stories, FAR, coverage, density, open space, parking ratios or a fixed parking total.
- Program: unit types and mix, unit depth, corridor, floor-to-floor heights, lobby / amenity / retail, cores, parking stall and aisle sizes.
- Layouts: courtyard, U and site-following bars, wraps around a garage, garden bars with surface parking, and straight, twin, L, T and cross towers.
- Rules: daylight per room, minimum courtyard width, 5' corridor door per unit, stair travel and dead-end distances, elevator and two stairs per corridor.
- 3D view with plan mode, section box, click-to-inspect, a gallery of tested layouts, and favorites.
- Exports: PDF report, Excel workbook, 2D plan (DXF, opens in AutoCAD), 3D massing (Collada .dae for SketchUp Pro).

## Saving
Schemes are saved **in your own browser** on the computer you use. They are not shared or uploaded anywhere.
- **Export schemes** downloads all your saved schemes as a `.json` file, to back them up or send to a colleague.
- **Import** opens a `.json` file someone shared. Its schemes are added to your Scheme list.

Clearing your browser's site data removes saved schemes, so export anything you want to keep.

## Notes
Concept-level test-fit only. Verify zoning values against the adopted code. Layouts are schematic and are not a code review.

The page loads three.js, jsPDF, SheetJS and web fonts from public CDNs, so it needs an internet connection.
