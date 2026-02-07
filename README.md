#  Custom Shadow Board Project

> **Concept:** A fully bespoke organization system where every tool has a specifically designed home, modeled with precision tolerances for a perfect friction fit.


##  The Philosophy
Standard pegboards are versatile, but they often rattle and lack precision. I wanted a workspace that followed the **Industrial "Shadow Board" Principle**, but upgraded with modern manufacturing:

1.  **Visual Inventory:** Immediate visual feedback if a tool is missing.
2.  **Perfect Fit:** Tools snap into place with satisfying precision (0.2mm - 0.5mm tolerance).
3.  **Workflow Efficiency:** Essential items (like drill bits and soldering accessories) are detachable, bringing the tool to the work area, not just storing it.

##  Key Features

### 1. Hidden Power & Cable Management
To maintain a clean aesthetic without visible wires:
* **Embedded Outlet:** A power outlet is flush-mounted directly into the wooden panel.
* **Routed Channels:** I used a wood router (*tupia*) to carve channels on the back of the panel. All wiring runs inside these recessed paths, remaining completely invisible from the front.

### 2. Detachable "Docking" Modules
Some tools need to move with you. Instead of permanently fixing everything, I designed specific holders to be removable:
* **Drill Bit Cassette:** The entire bit holder unclips from the wall, allowing me to take the whole set to the project area.
* **Soldering Station:** The cleaning sponge and brass wool holder can be detached for cleaning and refilling without unscrewing the base.

### 3. Direct Fixation System
Unlike grid-based systems (French Cleat or Pegboard), this wall uses direct screw mounting for maximum rigidity.
* **Retrofitting:** If a tool is replaced, I simply measure the existing screw hole positions and model the new holder in Fusion 360 to match the old mounting points (or drill new ones for heavier tools).

### 4. Ambient Lighting
* **Backlight:** RGB Neon LED strips are mounted in the perimeter to provide ambient contrast, highlighting the tool silhouettes (Shadow Board effect).

### 5. Stackable Component Bins (Multi-Color)
To organize small and medium electronic parts (resistors, LEDs, Arduino, driver's, step up, etc), I designed a custom modular bin system:
* **Interlocking Design:** The boxes feature a bottom lip that fits perfectly into the top of another box, allowing for stable vertical stacking.
* **High-Contrast Labeling:** The text on the front is printed in a contrasting color (White on Black) to ensure readability from a distance.
* **Technique:** This multi-color effect was achieved on a standard **single-extruder printer** by printing the wall with the letters separated. You only need to write what ou want, add a pause in the right height and change the filament.

##  The Design Workflow (Fusion 360)

Since every toolset is unique, sharing my specific STLs might not fit your tools. However, you can replicate my process:

1.  **Image Capture (for 1/4 of the tools):** Take a photo of the tool flat on a table (from a top-down orthogonal view) next to a ruler.
2.  **Canvas Import:** Import the photo into Fusion 360 and calibrate it using the ruler as a reference.
3.  **Sketching:** Trace the silhouette of the tool, or, take all the important measures and make the model without the image.
4.  **Tolerance Offset:** I apply a **0.3mm to 0.5mm offset** to the internal walls. This ensures a smooth slide-in fit without scratching the tool.
5.  **Mounting Holes:** Extrude the screw holes (usually 3mm or 4mm countersunk) based on the intended position on the wood.

##  Template Files (`/templates`)
To help you get started, I have included generic template files in the `templates` folder of this repository.
* `ATENCAOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO`
* `template_drill_holder.f3d` (Fusion 360 Source File)
* `template_removable_dock.f3d` (The mechanism for detachable parts)

##  Hardware Used
* **Material:** PLA (Black for contrast).
* **Panel:** MDF with Router-milled cable paths.
* **Fixation:** Wood screws (Countersunk head).
* **Lighting:** 12V Neon LED Strip (RGB).

---
*Project created by Henrique Gutknecht Michel*
