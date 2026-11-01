# Grid Builder for EffectCraft

> A modern, powerful ExtendScript (JSX) panel for EffectCraft that creates dynamic modular grids, spherical arrays, radial distributions, and responsive layer layouts with keyframable morphing and effector controls.

Inspired by the acclaimed Grid Builder tool for motion designers, this plugin brings advanced procedural layout generation directly into EffectCraft.

---

## 🎨 Key Features

- **4 Core Grid Modes:**
  - 📐 **Rectangular Grid:** Automatic multi-column/row distribution with custom gutter controls.
  - ⭕ **Radial Grid:** Circular and spiral layer placement around a central anchor.
  - 〰️ **Path Grid:** Even distribution of layers along vector paths or mask lines.
  - 🌐 **Spherical Grid:** 3D spherical point distribution with automatic target focusing.

- **Unified Controller Engine:**
  - Single Master Null control interface housing keyframable sliders for space, scale, and offset.
  - Full native property access—individual layers remain fully customizable.

- **4 Orientation Modes:**
  - **Forward:** Alignment locked to Master Null orientation.
  - **Orient to Center:** Layers dynamically point toward the grid's center point.
  - **Face Screen:** Layers lock facing the active viewport regardless of global camera rotation.
  - **Orient to Path:** Assets align to vector tangency along custom paths.

- **Morph Engine:**
  - Smooth keyframable morph slider allowing live transitions between different grid modes (e.g., Rectangular to Spherical).

- **Proximity & Effector System:**
  - Dynamic **Attract**, **Repel**, and **Look At** effectors affecting position, scale, rotation, and opacity.

- **1000x Modern Dark UI:**
  - Compact, dockable panel styled specifically for dark motion graphics environments.

---

## 📥 Installation

1. Download `GridBuilder.jsx` from the latest release.
2. Place the file inside your EffectCraft Scripts directory:
   - **Path:** `.../EffectCraft/Scripts/ScriptUI Panels/`
3. Launch EffectCraft.
4. Navigate to **Window > GridBuilder.jsx** to open the panel and dock it anywhere in your workspace.

---

## 🚀 Quick Start Guide

1. **Select Layers:** Choose the layers in your active composition that you want to form into a grid.
2. **Choose a Mode:** Select your layout preset (**Rectangular**, **Radial**, **Path**, or **Spherical**) in the panel.
3. **Build Grid:** Click `Build Grid`. Grid Builder will generate the master null controller and bind all layers.
4. **Customize & Animate:** Use the Master Controller Null properties or the panel sliders to adjust spacing, set up effectors, or keyframe the **Morph Slider**.

---

## 🛠️ Usage Notes & Tips

- **Undo Grouping:** All operations are wrapped in safe undo blocks (`app.beginUndoGroup`). Pressing `Ctrl+Z` / `Cmd+Z` safely reverts the entire grid setup.
- **Layer Sorting:** Reorder layers directly inside the panel's layer manager to change layout positioning without altering timeline stack orders.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
