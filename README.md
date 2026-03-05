# ⬡ Smith Chart

An interactive Smith Chart plotter that runs entirely in the browser — no dependencies, no build step, no server required.

Originally written in C using Turbo C / BGI graphics. Rebuilt as a single HTML file using HTML5 Canvas.

**[Live Demo →](https://YOUR-USERNAME.github.io/smith-chart/)**

---

## Features

- Constant resistance circles (r-circles)
- Constant reactance arcs (x-arcs)
- Plots normalised impedance point **Z (A)**
- Plots conjugate **Z* (B)** and admittance **Y (C)**
- VSWR locus circle
- Computes reflection coefficient **|Γ|** and **∠Γ**
- Fully responsive — works on any screen size

## Usage

Enter three values in the side panel and click **Plot Point**:

| Field | Description |
|-------|-------------|
| **Z₀** | Characteristic impedance (Ω), typically 50 |
| **R** | Resistance component of load (Ω) |
| **X** | Reactance component of load (Ω), negative for capacitive |

Results shown: normalised impedance, normalised admittance, \|Γ\|, ∠Γ, and VSWR.

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your chart is live at `https://YOUR-USERNAME.github.io/smith-chart/`

## Local Use

No install needed. Just open `index.html` in any browser:

```bash
git clone https://github.com/YOUR-USERNAME/smith-chart.git
cd smith-chart
open index.html
```

## Origin

Based on `Smithchr.c` originally written by **Patrick C. Janvier & Suresh**,
Sri Manakula Vinayagar College of Engineering, ECE Dept.

## License

MIT
