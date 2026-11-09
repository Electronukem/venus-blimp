# Venus Cloud Blimp

A browser simulation of a helium blimp floating in the clouds of Venus, holding the altitude where the outside air is 70°F (about 55.9 km up, at roughly 0.5 bar).

Open `venus-blimp.html` in any modern browser. There is no build step and nothing to install.

## What it simulates

- **Atmosphere:** an approximate Venus International Reference Atmosphere (VIRA) temperature profile, with pressure integrated hydrostatically from 92.1 bar at the surface. Day/night thermal tides, gravity waves and convective updrafts (strongest near 52 km) perturb it.
- **Blimp:** a sealed 5,000 m³ helium envelope with 2,650 kg dry mass. Vertical motion includes buoyancy, added mass and drag.
- **Altitude control:** a compressor packs outside CO₂ into a ballast tank to descend and vents it to climb. The autopilot steers by the outside thermometer.
- **Winds:** the blimp drifts with Venus's super-rotation (about 60 m/s westward at this altitude), circling the planet in about 6.4 Earth days. The Sun rises in the west.

## Controls

Time speed (1× to 4 hours per second), target temperature (40–105°F), autopilot or manual ballast, convection on/off, a downdraft trigger, and °F/°C.

The blimp is drawn about 10× its real size. This is a simulation for intuition, not mission design.

## License

[MIT](LICENSE)
