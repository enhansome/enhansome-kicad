# Awesome Kicad with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 501,335 | 🐛 105 | 📅 2026-08-21

### Install from KiCad

Every project on this list that ships an installable add-on is published as a single KiCad repository. Add it under **Plugin and Content Manager → Manage → +**:

```
https://github.com/joanbono/awesome-kicad/releases/latest/download/repository.json
```

The repository is rebuilt automatically and only contains add-ons that install *inside* KiCad. Tools that run outside KiCad — CLI utilities, browser apps, FreeCAD workbenches, tutorials — are listed below but cannot be installed this way. See [`scripts/build_pcm_repository.py`](scripts/build_pcm_repository.py) for how it is generated.

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/joanbono/awesome-kicad/blob/main/CONTRIBUTING.md) ⭐ 602 | 🐛 0 | 🌐 Python | 📅 2026-08-25 first. Thanks to all [contributors](https://github.com/joanbono/awesome-kicad/graphs/contributors) ⭐ 602 | 🐛 0 | 🌐 Python | 📅 2026-08-25; you rock!

### Contents

#### API

* [`kicad-python`](https://gitlab.com/kicad/code/kicad-python): Official Python bindings for the KiCad IPC API.
* [`kicad-rs`](https://gitlab.com/kicad/code/kicad-rs): Official Rust bindings for the KiCad IPC API.

#### Plugins

##### Panelization

* [KiKit](https://github.com/yaqwsx/KiKit) ⭐ 2,015 | 🐛 98 | 🌐 Python | 📅 2026-08-05: Library and CLI tool to panelize boards, export manufacturing data and build board presentation pages.
* [ReplicateLayout](https://github.com/MitjaNemec/ReplicateLayout) ⭐ 131 | 🐛 28 | 🌐 Python | 📅 2026-08-23: Extension to replicate the PCB layout of one hierarchical sheet to other sheets based on hierarchical sheets in Eeschema.
* [panelize-plugin](https://github.com/msvisser/panelize-plugin) ⭐ 60 | 🐛 3 | 🌐 Python | 📅 2021-12-16: Automatic KiCad panelization plugin

##### Manufacturing BOM and Gerbers

* [Kicad JLCPCB Tools](https://github.com/Bouni/kicad-jlcpcb-tools) ⭐ 2,047 | 🐛 86 | 🌐 Python | 📅 2026-07-30: Plugin to generate all files necessary for JLCPCB board fabrication and assembly
* [KiCost](https://github.com/xesscorp/KiCost) ⭐ 625 | 🐛 32 | 🌐 Python | 📅 2026-07-08: Build cost spreadsheet for a KiCad project.
* [KiBoM](https://github.com/SchrodingersGat/KiBoM) ⚠️ Archived: Configurable BoM generation tool for KiCad EDA
* [JLCKicadTools](https://github.com/matthewlai/JLCKicadTools) ⭐ 355 | 🐛 6 | 🌐 Python | 📅 2025-05-01: Tool for using JLCPCB assembly service with KiCad
* [KiCad JLCPCB BOM Plugin](https://github.com/wokwi/kicad-jlcpcb-bom-plugin) ⭐ 204 | 🐛 5 | 🌐 Python | 📅 2023-04-16: Export a JLCPCB Compatible BOM directly from your KiCad schematic
* [kicad-gerberzipper](https://github.com/g200kg/kicad-gerberzipper) ⭐ 62 | 🐛 7 | 🌐 Python | 📅 2026-07-13: KiCad Plot and Zip
* [gerber\_to\_order](https://github.com/asukiaaa/gerber_to_order) ⭐ 61 | 🐛 9 | 🌐 Python | 📅 2026-06-15: A KiCad plugin to create zip compressed gerber files to order for Elecrow, FusionPCB, PCBWay or JLCPCB.
* [KiZip](https://github.com/gregdavill/KiZip) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2022-06-19: KiCad Plugin to package gerbers ready for ordering
* [kicad-bom-seeedstudio](https://github.com/imrehg/kicad-bom-seeedstudio) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2021-11-09: KiCad BOM plugin to follow Seeed Studio's Fusion PCBA template
* [Copper Thief Plugin](https://github.com/mrussell42/copper_thief) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2024-10-03: [Copper Thieving](https://electronics.stackexchange.com/questions/85633/what-is-copper-thieving-and-why-use-it) Plugin.
* [KiABOM](https://github.com/Mage-Control-Systems-Ltd/KiABOM) ⭐ 6 | 🐛 4 | 🌐 Python | 📅 2026-07-02: Simple BOM generation with online supplier data.
* [KiCad Better BOM](https://github.com/AlexanderNickolsky/KiCad-Better-BOM) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-17: Yet another pretty BOM generator for KiCad.
* [BOM2Md](https://github.com/AlexSartori/kicad-bom2md) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-02-28: Plugin for KiCAD to generate a Bill of Materials formatted as a Markdown table.
* [Salitronic Gerber Analyzer](https://salitronic.com/gerber_analyzer): Free in-browser tool to view and check the Gerbers KiCad exports (also reads ODB++ and IPC-2581), with DRC, layer diff, pick-and-place, and thermal, EMI and impedance analysis.

##### PCB Design

* [FreeRouting](https://github.com/freerouting/freerouting) ⭐ 1,918 | 🐛 38 | 🌐 Java | 📅 2026-08-28: Advanced PCB auto-router
* [SKiDL](https://github.com/devbisme/skidl) ⭐ 1,638 | 🐛 46 | 🌐 Python | 📅 2026-08-20: A module that extends Python with the ability to design electronic circuits.
* [PcbDraw](https://github.com/yaqwsx/PcbDraw) ⭐ 1,415 | 🐛 10 | 🌐 Python | 📅 2026-08-07: Convert your KiCAD boards into nice looking 2D drawings suitable for pinout diagrams
* [Svg2Shenzhen](https://github.com/badgeek/svg2shenzhen) ⭐ 872 | 🐛 50 | 🌐 C++ | 📅 2025-03-15: (Discontinued) Inkscape extension for exporting drawings into a KiCad PCB.
* [KiCad RF Tools](https://github.com/easyw/RF-tools-KiCAD) ⭐ 825 | 🐛 38 | 🌐 Python | 📅 2024-11-11: Footprints, wizards and round tracks, mask expander, via fencing
* [KiCad Templates](https://github.com/sethhillbrand/kicad_templates) ⭐ 761 | 🐛 6 | 🌐 HTML | 📅 2019-10-24: Provides a number of additional Board and production house templates for KiCad EDA.
* [KiBot](https://github.com/INTI-CMNB/KiBot) ⭐ 734 | 🐛 27 | 🌐 Python | 📅 2026-08-28: KiCad automation utility.
* [uConfig](https://github.com/Robotips/uConfig) ⭐ 586 | 🐛 29 | 🌐 C++ | 📅 2026-02-24: Datasheet pinout extractor from PDF and library Stylizer for Kicad.
* [KiBuzzard](https://github.com/gregdavill/KiBuzzard) ⭐ 468 | 🐛 25 | 🌐 Python | 📅 2026-04-09: Create labels in various fonts, and with inverted backgrounds
* [svg2mod](https://github.com/mtl/svg2mod) ⭐ 259 | 🐛 25 | 🌐 Python | 📅 2023-02-01: Convert Inkscape SVG drawings to KiCad footprint modules
* [Import-LIB-KiCad-Plugin](https://github.com/Steffen-W/Import-LIB-KiCad-Plugin) ⭐ 251 | 🐛 6 | 🌐 Python | 📅 2026-05-01: Import KiCad component libraries imported from Ultralibrarian and SnapEDA zipfiles.
* [Gingerbread](https://github.com/wntrblm/Gingerbread) ⭐ 206 | 🐛 17 | 🌐 C++ | 📅 2026-08-16: A tool for converting vector artwork to KiCAD PCB files that lives in your browser.
* [Stretch](https://github.com/JarrettR/Stretch) ⭐ 149 | 🐛 15 | 🌐 Python | 📅 2025-06-06: Allow your PCBs to stretch!
* [Circuitron](https://github.com/Shaurya-Sethi/circuitron) ⭐ 121 | 🐛 8 | 🌐 Python | 📅 2026-06-06: Agentic PCB Design Accelerator — Generate, plan, and layout circuits from natural language prompts.
* [Kobee Studio](https://github.com/mrcpuddington/kobeestudio) ⭐ 65 | 🐛 8 | 🌐 Python | 📅 2026-08-09: Modern PCB graphics toolkit for KiCad with customizable labels, icons, component overlays, QR codes, barcodes, and custom SVG assets.
* [Laser Stencil Plugin](https://github.com/ma-ha/kicad-laser-stencil-plugin) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2024-07-13: KiCAD Pcbnew plugin to generat laser cutter G-Code files for solder paste stencils
* [Img2Silk](https://github.com/NBalciunas/kicad-img2silk) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-07-07: Dither images into PCB graphics using Floyd–Steinberg, Atkinson, Bayer and other algorithms, in B\&W or multi-color using board layers as a palette.
* [NCCM](https://github.com/Mage-Control-Systems-Ltd/NCCM) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-05-26: Net Class Clearance Matrix (NCCM) to generate custom rules for clearances between net classes through a matrix GUI.
* [Stimulu KiCad Plugins](https://github.com/stimulu/stimulu-kicad-plugins) ⭐ 1 | 🐛 0 | 📅 2019-05-12: Collection of KiCad plugins to reproduce or use Stimulu board files.
* [Rectangulator](https://github.com/msolomentsev/rectangulator) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-30: A simple plug-in that automatically turns zones into perfect rectangles.
* [typeCAD](https://github.com/typecad/typecad): Programmatically create hardware designs with TypeScript. Create/reuse/import version-controlled packages between projects.

##### Presentations

* [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom) ⭐ 4,539 | 🐛 43 | 🌐 Python | 📅 2026-07-12: Generate convenient BOM listing with ability to visually correlate and easily search for components and their placements on the pcb

##### Reviewing

* [kicanvas](https://github.com/theacodes/kicanvas) ⭐ 1,127 | 🐛 55 | 🌐 TypeScript | 📅 2026-04-28: KiCanvas is an interactive, browser-based viewer for KiCAD schematics and boards
* [kicad-happy](https://github.com/aklofas/kicad-happy) ⭐ 1,044 | 🐛 5 | 🌐 Python | 📅 2026-08-20: AI-powered design review for KiCad — schematic analysis, PCB layout review, component sourcing, BOM management, and manufacturing prep via Claude Code skills.
* [kiri](https://github.com/leoheck/kiri) ⭐ 702 | 🐛 9 | 🌐 Shell | 📅 2026-06-22: A tool for reviewing Kicad's projects visually including schematics and layout using Kicad-Diff and Plotgitsch
* [KiCadStepUp](https://github.com/easyw/kicadStepUpMod/) ⭐ 683 | 🐛 40 | 🌐 Python | 📅 2026-08-14: KiCad StepUp is a FreeCAD Workbench to help in mechanical collaboration between KiCad EDA and FreeCAD.
* [KiCad-Diff](https://github.com/Gasman2014/KiCad-Diff) ⭐ 293 | 🐛 3 | 🌐 Python | 📅 2024-06-26: Plugin to perform image diffs between pcbnew layout revisions
* [gerber2ems](https://github.com/antmicro/gerber2ems) ⭐ 256 | 🐛 6 | 🌐 Python | 📅 2026-04-23: Takes PCB production files as input (Gerber, drill files, stackup information) and simulates trace SI performance using openEMS
* [plotkicadsch](https://github.com/jnavila/plotkicadsch) ⭐ 233 | 🐛 4 | 🌐 OCaml | 📅 2026-07-28: Export Kicad Sch files to structured picture files
* [gerber2blend](https://github.com/antmicro/gerber2blend) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2025-12-11: open-source utility to generate 3D models of Printed Circuit Boards (PCBs) in Blender (`.blend` format)
* [RFsim](https://github.com/NBalciunas/kicad-rfsim) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-08-20: KiCad 10 plugin for simulating S-parameters, E/H fields and far field of an RF structure directly in the PCB editor with the openEMS FDTD solver.
* [akcli](https://github.com/tipoLi5890/akcli) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-08-25: AI-native schematic design CLI for KiCad — author and edit `.kicad_sch` from JSON op-lists behind a net-diff safety gate, run ERC / design-review / BOM checks, simulate on ngspice, and source JLCPCB parts. Zero dependencies (pure-stdlib Python).
* [BoardRepo](https://github.com/flintt-dev/boardrepo-plugin) ⭐ 0 | 🐛 0 | 📅 2026-08-25: Hosted project library and read-only review tools for KiCad schematics, BOMs, source files, DRC/ERC results, and fabrication constraints through MCP.

##### Converters

* [Altium2Kicad](https://github.com/thesourcerer8/altium2kicad) ⚠️ Archived: Altium to KiCad converter for PCB and schematics
* [Eagle to KiCad](https://github.com/lachlanA/eagle-to-kicad) ⭐ 427 | 🐛 8 | 🌐 NASL | 📅 2022-01-03: Eagle SCH/LIB to KiCad SCH/LIB ULP conversion script

##### GUI

* [KiCad Color Schemes](https://github.com/pointhi/kicad-color-schemes) ⭐ 714 | 🐛 16 | 🌐 Python | 📅 2024-04-16

##### Other

* [kicad-wakatime](https://github.com/hackclub/kicad-wakatime) ⭐ 46 | 🐛 11 | 🌐 Rust | 📅 2026-05-28: WakaTime plugin for KiCAD 8.99

#### Symbols

* [Arduino Kicad Library](https://github.com/Alarm-Siren/arduino-kicad-library) ⭐ 444 | 🐛 13 | 📅 2025-06-07: KiCad Symbol & Footprint Library for Arduino Modules
* [Official KiCad Symbols](https://gitlab.com/kicad/libraries/kicad-symbols)

#### Footprints

* [Official KiCad Footprints](https://gitlab.com/kicad/libraries/kicad-footprints)
* [KiCad Footprint Generator](https://gitlab.com/kicad/libraries/kicad-footprint-generator): Generate custom KiCAD footprints using python

#### 3D Models

* [Official KiCad 3D Models](https://gitlab.com/kicad/libraries/kicad-packages3D)

#### Tutorials

* [Keyboard PCB guide](https://github.com/ruiqimao/keyboard-pcb-guide) ⭐ 4,943 | 🐛 22 | 📅 2024-07-02: Guide on how to design keyboard PCBs with KiCad
* [Hawk](https://github.com/MalphasWats/hawk) ⭐ 481 | 🐛 4 | 🌐 C | 📅 2020-11-06: Tutorial for making an ARM dev board in KiCAD

#### 3rd-Party Component Integration

* [Kandle](https://github.com/HarveyBates/kicad-component-handler) ⭐ 48 | 🐛 3 | 🌐 C++ | 📅 2024-04-29: CLI to automatically import 3rd-party components (symbols, footprints and 3D-models) into KiCad.

#### Verilog / VHDL Tools

* [KiCadVerilog](https://github.com/galacticstudios/KiCadVerilog) ⭐ 70 | 🐛 3 | 🌐 Python | 📅 2024-11-02: Generate Verilog code from a KiCad netlist.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
