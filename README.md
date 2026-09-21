# Custom LED Robot Logo Plate

A two-part modular LED logo plate designed to slap onto the side of custom robot builds (typically around $10 \times 10$ to $20 \times 20$ cube footprints). 

Aesthetics matter a lot to me for my builds, so the goal of this project was to take my custom logo and create a clean, backlit plate that matches the original design as $1:1$ as possible.

---

## 📐 Design & CAD Process

The design was created in **Onshape** using a two-part embedded structure:

1. **Logo Vectorization:** Acquired the original PNG of my logo and converted it into a DXF vector file (the format Onshape accepts) to use as the base for the CAD sketch.
2. **Two-Part Extrusion:** Extruded the sketch geometry into two separate parts that embed nicely into each other:
   * **Translucent Logo Inlay:** The interior logo piece meant for LEDs to shine through.
   * **Mounting Frame/Plate:** The outer housing frame that holds the inlay and mounts directly to the robot chassis.

### Onshape CAD Views

| 2D DXF Sketch Import | Assembled 2-Part Plate | Exploded CAD View |
| :---: | :---: | :---: |
| *Vector points imported onto sketch plane* | *Translucent inlay embedded into housing* | *Separated frame and logo insert* |

---

## 🛠️ Planned Materials & Hardware

* **Translucent Inlay:** Printed using translucent/clear plastic filament so the LED backlighting diffuses evenly through the logo.
* **Mounting Frame:** Basic ABS or whatever budget filament is cheapest so I can cover the cost myself.
* **Mounting Method:** Double-sided tape to keep mounting simple and lightweight on $10 \times 10$ to $20 \times 20$ robot frames.

---

## 🔬 Next Steps & Research

* [ ] **Infill & Print Config Research:** Testing different slicer configurations (infill density, infill patterns, wall count, layer heights) to see what lets the most light shine through the translucent plastic.
* [ ] **3D Printing:** Print test iterations of both parts to verify fit tolerances for the embedded joint.
* [ ] **LED Integration & Tape Mounting:** Test backlighting behind the translucent inlay and mount the final plate to a robot chassis.
