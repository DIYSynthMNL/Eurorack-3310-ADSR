# Eurorack-3310-ADSR

![AS3310 ADSR assembled](photos/front.jpg)

An ADSR envelope generator module based on the AS3310 chip (Electric Druid).

## Schematic

- Latest: **Rev 0.1.3** — [PDF](Schematic%20PDFs/Eurorack-AS3310-ADSR-Schematic-Rev0.1.3.pdf)
- All revisions: [Schematic PDFs/](Schematic%20PDFs/)

## Hardware

- KiCad project: [kicad/](kicad/)
- 3D-printed front panel STL: [3D printed front panel/](3D%20printed%20front%20panel/)
- Falstad simulations: [falstad/](falstad/)

## References

Local archived copies live in [`references/`](references/) so this repo stays useful if the upstream links die.

- **AS3310 datasheet** — [local copy](references/AS3310-alfatriode-2023-v7.pdf) · [upstream (alfatriode.lv)](https://alfatriode.lv/eng/sc/AS3310.pdf)
- **Electric Druid AS3310 product page** — [upstream](https://electricdruid.net/product/as3310-vcadsr/)
- **Design inspiration: Bumm Bumm Garage VCEG** — [upstream](https://www.bummbummgarage.com/modules/voltage-controlled-envelope-generator-vceg/) (page is JS/bot-protected; save manually if you want a local archive)

## Build status

What's ready for builders today, and what's still on the TODO list:

**Production assets** (what you need to actually fabricate and assemble a final unit)

- [x] Schematic — Rev 0.1.3 ([Eurorack-AS3310-ADSR-Schematic-Rev0.1.3.pdf](Schematic%20PDFs/Eurorack-AS3310-ADSR-Schematic-Rev0.1.3.pdf))
- [ ] PCB layout — in progress — single working layout in `kicad/`, not yet separated for fab
- [ ] Gerber files for fabrication — none yet
- [ ] BOM — none yet
- [ ] Final front panel (SVG/PDF for fab) — none yet
- [ ] License — none yet

**Prototype assets** (for breadboard / perfboard / 3D-printed-panel builds before final PCB)

- [x] 3D-printed prototype panel STL — [3310_ADSR.stl](3D%20printed%20front%20panel/3310_ADSR.stl)

**Documentation**

- [x] Photos of the assembled module — see [photos/](photos/)
- [ ] Demo video — none yet
- [ ] Build / assembly instructions — none yet

Want to help fill a gap (build photos, gerbers, an assembly guide)? Open an issue or PR.
