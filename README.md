# ⚙️ 3D Printable Gear Train & Compatibility Studio

An interactive, browser-based kinematic engine and CAD tool for designing, simulating, and validating 3D-printable gear trains. 

Built to solve the classic hardware problem of printed gears binding or skipping, this tool generates true involute gear meshes and runs live mechanical diagnostics (like transverse contact ratio and collision detection) before you ever export an STL.

Developed with the assistance of **Google's Argon model** to accelerate complex kinematic mathematics and Three.js rendering.

## ✨ Features

* **True Involute Generation:** Automatically locks the module ($m$) and pressure angle ($\alpha$) across the entire gear train so every tooth meshes perfectly.
* **Live Engineering Diagnostics:** Calculates the transverse contact ratio in real-time. Warns you instantly if the ratio drops below 1.0 (indicating teeth will skip).
* **Printability & FDM Checks:** Automatically flags tooth undercut risks, thin walls near the shaft bore, or tip thicknesses that standard 0.4mm FDM nozzles cannot resolve.
* **Phase-Locked Animation:** Simulates the exact rotation and meshing of linear trains, idlers, or branched gear clusters.
* **Direct STL Export:** Export individual gears, the entire train, or download a specialized **Test-Fit Baseplate Jig**—a flat plate with vertical test pins at the exact center-to-center coordinates to verify printer tolerances.

## 🚀 Live Demo

[**Try the Gear Studio Live**]([https://kadlagop61.github.io/](https://kadlagop61.github.io/Gear_Generator/) *(Replace with your GitHub Pages link)*

## 🛠️ Usage

This application is a 100% client-side web app. No installation, server, or Python environments are required.
