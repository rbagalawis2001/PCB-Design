# KiCAD 
Basic outline of a KiCAD project

## Basic KiCAD info
- **Project** - Double click on this file to prompt KiCAD to open the project window
- **Schematic**  - Block diagram of component connections used for wiring later on the board file 
- **Board** - Layout of physical PCB design: Traces, pads, drill holes, board size+shape
- **Library** - Stores project data such as schematic symbols and component footprints

\* For personal projects, I save my libraries locally (inside of my KiCAD project folder) *
- [ ] Save globally - lib is saved internally to my KiCAD program giles
- [x] Save locally - lib goes to a folder and moves with the project

## Scalable KiCAD Project
To transfer KiCAD project files, follow this hierarchy:
<details><summary>KiCAD_Project0 (Folder)</summary>
  
  - KiCAD_Project0 (project file type)
  - KiCAD_Project0 (schematic file type)
  - KiCAD_Project0 (board file type)
  - Footprint_LibName.Pretty 
  - Symbol_LibName.kicad_sym
  - Output folder and files *if applicable*
</details>

> You may need to manually link the library files to the schematic editor and footprint editor

