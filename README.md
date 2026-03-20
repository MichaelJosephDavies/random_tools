# random_tools

Static HTML tools for the Davies Snow Depth Sensor Network.

## Tools

### Shadow Sweep

Interactive station-placement viewer for checking whether the HC-SR04 beam is shadowed by the mast, tripod legs, solar panel, or electronics box.

What it does:

- simulates sun position at the site latitude for winter, equinox, and summer
- shows the sensor arm in different compass directions
- estimates when the measurement beam is blocked during the day
- compares shadow exposure across multiple arm directions

Use it when you want to decide which side of the mast to mount the sensor boom and whether nearby station hardware will cast beam interference.

### HC-SR04 Arm Length & Beam Clearance

Geometry calculator for determining how long the horizontal arm must be to keep the HC-SR04 beam clear of the mast and tripod legs all the way to the ground.

What it does:

- models the 15 degree beam half-angle from the sensor
- computes interference depth against the mast and the right tripod leg
- shows beam footprint at ground level
- reports the minimum arm length needed for full clearance

Use it when you need to choose or validate a boom length before building or modifying a station.

### Snow Station Planner

Top-view and side-view station layout planner for evaluating snow-depth clearance, beam footprint, and mast shading around the sensor.

What it does:

- converts mast height and snow depth into remaining sensor clearance
- computes beam radius at the snow surface
- visualizes mast and panel shadows for seasonal sun angles
- compares shaded and unshaded layouts around the sensor clean zone

Use it when you want to place the mast and panel relative to the sensor while keeping the beam clear and understanding when deliberate shading will or will not hit the sensor.

## GitHub Pages

Enable GitHub Pages from `main` / root in the repository settings.

After that, these clean URLs will work:

- `https://michaeljosephdavies.github.io/random_tools/`
- `https://michaeljosephdavies.github.io/random_tools/shadow-sweep/`
- `https://michaeljosephdavies.github.io/random_tools/hcsr04-arm-length-beam-clearance/`
- `https://michaeljosephdavies.github.io/random_tools/snow-station-planner/`

The source HTML files remain at the repo root:

- `shadow_sweep.html`
- `hcsr04_arm_length_beam_clearance.html`
- `snow_station_planner.html`
