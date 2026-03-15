# Energy Blast Creator

A lightweight **HTML5 Canvas energy beam generator** inspired by classic anime battle attacks.

Design and preview cinematic energy blasts similar to **Kamehameha**, **Final Flash**, **Galick Gun**, and other beam-style techniques. The tool provides modular visual layers such as glow, beam core, particles, rings, and lightning so you can experiment with effects and build your own signature attacks.

Everything runs inside **one single HTML file** with **no dependencies**.

---

# Features

⚡ **Single-File App**
Runs entirely from one `index.html` file.

⚡ **Anime-Style Beam Effects**
Create energy attacks similar to:

* Kamehameha
* Final Flash
* Galick Gun
* Masenko
* Death Beam

⚡ **Full Visual Controls**

Adjust:

* Beam width
* Energy color (HSL)
* Glow intensity
* Charge level
* Beam length
* Wobble and pulse motion
* Particle count
* Shockwave rings
* Lightning arcs
* Noise streaks

⚡ **Reusable VFX Layers**

The blast is built from modular layers:

```
Source Flare
Aura Shell
Beam Core
Beam Glow
Particles
Shock Rings
Lightning Accents
```

This makes it easy to reuse pieces when building animation sequences.

⚡ **Preview Animation Modes**

You can preview three attack phases:

* Charge
* Fire
* Full Sequence

Looping mode allows continuous effect testing.

---

# Demo

Once hosted with GitHub Pages the app becomes a live interactive tool.

Example URL structure:

```
https://nytmaer.github.io/energy-blast-creator/
```

---

# Installation

No build tools required.

### Option 1 — Run locally

Download the file and open it:

```
index.html
```

Open in any browser.

---

### Option 2 — Host with GitHub Pages

1. Create a new repository
2. Upload `index.html`
3. Go to

```
Settings → Pages
```

4. Under **Build and Deployment**

```
Source: Deploy from branch
Branch: main
Folder: /root
```

5. Save

GitHub will publish your page automatically.

---

# Repository Structure

```
energy-blast-creator
│
├── index.html
└── README.md
```

The entire application lives inside the single HTML file.

---

# Why This Exists

Anime energy attacks are visually complex but conceptually simple:

A beam attack is usually composed of layered elements:

```
Energy Core
Glow Shell
Particle Spray
Shockwaves
Electrical Instability
```

This tool isolates those pieces so they can be tuned independently.

The result is a **sandbox for designing beam-style VFX**.

---

# Future Improvements

Possible extensions:

* Export beam animations as **PNG frame sequences**
* Add **timeline keyframe editor**
* Support **sprite sheet export**
* Allow **click-to-aim beam direction**
* Add **camera shake and screen bloom**
* Add **beam collision / impact explosions**

---

# Contributing

Pull requests are welcome.

Ideas that would help the project:

* new beam presets
* better particle motion
* export tools
* animation controls
* performance improvements

---

# License

MIT License

Use it freely for experiments, games, or visual effects work.

---

