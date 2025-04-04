# Toroidal Simulator - Unified Physics (v17.3)

Live Demo Here - https://toroidal.midland.org.uk/

![image](https://github.com/user-attachments/assets/2b1612ea-19a9-4ef5-8c38-e769299c0a04)

---

## Description

This web-based app provides an interactive visualization of particle flow within one or more toroidal moments. The aim of the app is to allow the users to explore, building an intuitive understand of related geometry. Many mathematical and scientific principles are included, though not strictly named to make the app accessible for everyone. The app aims to be lightweight and run on many devices, so many features related to complex math and quantum physics are not fully calculated (yet!).

**PC devices only, mobile and touchscreen support to follow later.

It allows users to manipulate parameters related to:

* **Flow Dynamics:** Control intensity, twist (toroidal vs. poloidal flow), angular momentum effects, soliton phasing, and even visualize theoretical eigenmodes.
* **Geometry:** Define torus dimensions (major/minor radius), create nested shells, and arrange multiple toroids into sacred geometry patterns (Flower of Life, Platonic Solids, etc.) or standard arrangements.
* **Particle Systems:** Configure particle count (random or discrete grid placement), size, appearance (color, opacity, glow), and apply post-processing effects like motion trails and bloom.

It leverages **Three.js** for 3D rendering and provides a user-friendly control panel for real-time experimentation.

## Features

* **Flexible Flow Control:** Adjust intensity, twist, coupling, angular momentum (approximate or effect-based), constant drift, soliton phasing, and jitter.
* **Eigenmode Visualization:** Modulate flow based on user-defined poloidal (m) and toroidal (n) mode numbers and strength.
* **Diverse Geometric Arrangements:** Single torus, Vesica Piscis, Flower/Fruit of Life (2D), Tree of Life, Platonic Solids (Tetrahedron, Cube, Octahedron, etc.), Star Tetrahedron.
* **Nested Toroids:** Create simulations with multiple concentric shells with adjustable size ratios.
* **Particle Placement Options:**
    * Random placement within the volume.
    * Discrete N x M grid placement on the surface (with optional N/M slider linking).
* **Advanced Appearance Control:**
    * Particle count, size, opacity, energy intensity (glow).
    * Multiple color modes (Manual RGB, Velocity, Direction Change, Angles, Position, Eigenmode Phase, etc.).
    * Color variation for manual modes.
* **Post-Processing:** Apply motion trails (Afterimage) and bloom effects (UnrealBloom).
* **Configuration Management:** Save/Load/Delete multiple named configurations directly in the browser's Local Storage. Includes auto-saving of the current state.
* **Camera Controls:** Mouse drag to rotate, mouse wheel to zoom, preset view buttons (Orthographic & Isometric).
* **UI Conveniences:** Collapsible control sections, UI visibility toggle, hotkey support.

## Live Demo

Access the live application here: **[Link to Live Demo]**
*(Replace with your actual link)*

## Usage / Controls

1.  Open in your web browser.
2.  Use the mouse to interact:
    * **Click and Drag:** Rotate the camera view.
    * **Scroll Wheel:** Zoom in and out.
3.  Use the **Control Panel** (bottom-left, collapsible sections) to adjust parameters in real-time. See the tooltips for hints on each control.
4.  Use the main buttons at the bottom for global actions.

### Basic Controls Summary

* **Play/Pause Button (or Spacebar):** Start/stop the simulation time.
* **Hide/Show UI Button (or H):** Toggle the control panel visibility.
* **Restart Sim Button (or Shift+R):** Resets particles and camera based on *current* settings.
* **Reset All Button (or Shift+Delete):** **Warning:** Resets all settings to defaults *and* clears all saved configurations from browser storage.
* **View Buttons:** Snap camera to standard views.

### Control Panel Summary

* **Flow Dynamics:** Intensity, twist, coupling, angular momentum, winding, phasing, jitter, eigenmodes.
* **Geometry & Structure:** Arrangement type, radii, pulsing, nesting, particle placement (discrete/random).
* **Particles & Appearance:** Count, size, opacity, glow, color modes, post-processing (trails, bloom).
* **Configuration Slots:** Save/Load/Delete named settings presets.

### Saving/Loading Configurations

* Use the "Configuration Slots" section in the control panel.
* Type a name in "Save Name" and click "Save As" to store the current settings.
* Select a saved name from the dropdown and click "Load" to restore those settings.
* Click "Delete" to remove the selected configuration.
* Settings are saved in your browser's **Local Storage**. They persist between sessions but will be lost if you clear your browser data.
* The application also automatically saves your last state, which is loaded when you reopen it.

### Hotkeys

* **Space:** Play / Pause Simulation
* **H:** Show / Hide UI Panel
* **Shift + R:** Restart Simulation
* **Shift + Delete:** Reset All Settings (Requires confirmation)
* **T:** Snap View to Top
* **F:** Snap View to Front
* **L:** Snap View to Left
* **I:** Snap View to Isometric NE
* **Escape:** Close Hotkeys Panel

## Support

If you find this application useful or interesting, please consider supporting its development:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/6af1sbu)
**(Link: https://buymeacoffee.com/6af1sbu)**

## Development / Contributing

*(Placeholder: Add information here if you want others to contribute. E.g., how to set up a local development environment, coding standards, pull request process.)*

Currently, you can run the application locally by simply opening the `index.html` file in a web browser that supports WebGL and ES6 JavaScript.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (or choose another license).
*(You'll need to add a LICENSE.md file with the actual license text if you include this)*
