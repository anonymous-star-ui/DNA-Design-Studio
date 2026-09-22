# DNA-Design-Studio | Synthetic Bio-CAD Platform

A high-performance, browser-native 3D Bio-Molecular CAD platform built with **Three.js**, **TailwindCSS**, and **Google Firebase v12**. Designed for synthetic biologists, genetic engineers, and bio-architects to construct, simulate, and analyze synthetic double helix constructs in real-time.

---

## Key Features

- **3D Double Helix Viewport:** Three rendering representations (CAD Rung & Ribbon, CPK Ball & Stick, and Backbone Spacefill) powered by Three.js.
- **Expanded Genetic Alphabet:**
  - Standard Watson-Crick bases: `A`, `T`, `C`, `G`
  - Steve Benner lab Hachimoji synthetic pairs: `P`, `Z`
  - Floyd Romesberg lab hydrophobic unnatural base pairs: `X`, `Y`
  - Custom Base Architect tool to define user-engineered unnatural letters on the fly.
- **Real-Time Molecular Dynamics & Thermodynamics:** Dynamic melting temperature ($T_m$), free energy ($\Delta G$), GC-equivalent ratios, and interactive thermal breathing/denaturation simulations (10°C to 98°C).
- **In-Studio Scripting Console:** Built-in automation API sandbox to procedurally generate sequences, run polymerase incorporation tests, and inject targeted point mutations.
- **Cloud Identity & Sync:** Integrated Google Firebase v12 Authentication supporting Email/Password, profile management, and account verification.
- **Progressive Web App (PWA):** Zero-install, offline-capable progressive web application with responsive CAD view controls.

---

## File Structure

```text
├── dna_design_studio.html   # Main application source (CAD Viewport + UI + Firebase logic)
├── manifest.json            # PWA manifest metadata
├── sw.js                    # Service Worker for offline asset caching
├── icon.svg                 # Scalable high-res vector application icon
├── README.md                # Project documentation
└── LICENSE                  # MIT License
