# Mars Navigator

**Interplanetary Survival Guide: Martian Map**
NASA Space Apps Challenge 2026

**Live site:** https://pravyasharma.github.io/mars-navigator/

A layered Mars map that tells the first human crews where to walk, when to walk, and how to stay safe.

## Team

Winchester School, Jebel Ali, Dubai

- **Pravya Sharma** (team lead): field guide, temperature zones, navigation and the Marswalk route plan
- **Advika Bisaria**: solar power plan (equator belt and polar farm)
- **Kshama**: safety layer (radiation, natural shelters, dust storms, helmet alert)

## Pages

| Page | What it does |
|---|---|
| [Map](https://pravyasharma.github.io/mars-navigator/) (`index.html`) | NASA Mars Trek layers, six mission objectives, route planner on Curiosity's real path, turn-by-turn navigation, temperature zone clock |
| [3D Globe](https://pravyasharma.github.io/mars-navigator/globe.html) (`globe.html`) | Slide-sized globe with a fixed pin, what lies in each direction, suit meter, live Sun position and sunlight, Earth distance |
| [Field Guide](https://pravyasharma.github.io/mars-navigator/guide.html) (`guide.html`) | The team's field guide, safety layer, solar power plan, and all credits and sources |

Every page also has a **crew chat** and a **field camera**.

## Mission objectives

1. Land safely and set up base
2. Find water ice
3. Search for signs of ancient life
4. Power the base
5. Stay safe from radiation and dust
6. Daily Marswalk

## Data sources

**NASA**
- Mars Trek map tiles: Viking colour mosaic, MOLA height map, THEMIS day and night infrared, TES thermal inertia and dust, CTX and HiRISE close-ups (https://trek.nasa.gov/mars/)
- Curiosity and Perseverance rover waypoints (mars.nasa.gov)
- Curiosity RAD and REMS, Perseverance MEDA and MOXIE results
- Mars24 Sunclock method, NASA GISS (https://www.giss.nasa.gov/tools/mars24/)
- JPL approximate planet positions (https://ssd.jpl.nasa.gov/planets/approx_pos.html)
- Images from the NASA Planetary Photojournal, credited on the Field Guide page

**Partners and others**
- ESA / DLR / FU Berlin (Mars Express HRSC)
- USGS / IAU Gazetteer of Planetary Nomenclature (https://planetarynames.wr.usgs.gov/)
- SWIM ice mapping project, Planetary Science Institute with NASA JPL (https://swim.psi.edu/)

Full credits, with links, are on the [Field Guide page](https://pravyasharma.github.io/mars-navigator/guide.html#team).

## Honest notes

- The temperature layer is our own simple model fitted to two real weather stations (Curiosity and Perseverance). It is a teaching tool, not a forecast.
- Suit readings on the 3D globe are simulated demo values.
- The chat and camera run in demo mode. A public website has no satellite link, so messages, photos and videos stay in your browser and are shared between its open tabs.
- Prepared by the team with help from an SI assistant for coding and fact-checking. Every fact was checked by the team. The six team diagrams were drawn with an SI image tool from the team's own ideas and carry an "SI-assisted image" mark. No NASA image was changed or generated.

## Built with

Plain HTML, CSS and JavaScript, [Leaflet](https://leafletjs.com/) (BSD-2 licence) and [three.js](https://threejs.org/) (MIT licence). Hosted on GitHub Pages.

## Files

- `index.html`, `globe.html`, `guide.html`: the three pages
- `data.js`: place names and the built-in copy of NASA rover waypoints
- `crew.js`: crew chat and field camera
- `img/`: NASA images and team diagrams

NASA does not endorse this project.
