# Awesome CNC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of CNC machines, firmware, software, learning resources and communities for hobbyists and professional machinists.

Routers, mills, lathes, plasma tables and lasers: the machines, the software that drives them, and the people who share what they know.

**Know something that belongs here? [Suggest it with a quick form](https://github.com/blackveilprecision/awesome-cnc/issues/new?template=add-resource.yml).** No Git required: a bot checks the link, runs an automated review, and opens the pull request for you.

## Contents

- [Desktop Machines](#desktop-machines)
- [Hobby & Small-Shop Routers](#hobby--small-shop-routers)
- [DIY & Open-Source Machines](#diy--open-source-machines)
- [Mills, Lathes & Plasma](#mills-lathes--plasma)
- [Firmware & Controllers](#firmware--controllers)
- [Machine Control Software](#machine-control-software)
- [CAD](#cad)
- [CAM](#cam)
- [Simulation & G-code Viewers](#simulation--g-code-viewers)
- [Feeds & Speeds](#feeds--speeds)
- [CNC Project Files](#cnc-project-files)
- [3D & CAD Model Libraries](#3d--cad-model-libraries)
- [Learning Resources](#learning-resources)
- [YouTube Channels](#youtube-channels)
- [Communities](#communities)

## Desktop Machines

- [Bantam Tools Desktop CNC](https://bantamtools.com/products/bantam-tools-desktop-cnc-milling-machine) - Enclosed, US-made desktop mill for machining aluminum prototypes and PCBs, with its own milling software.
- [Makera](https://www.makera.com/) - Desktop CNC machines with probing and quick or automatic tool changing: the Carvera, Carvera Air and Z1.
- [Nomad 3](https://carbide3d.com/nomad/) - Carbide 3D's fully enclosed desktop mill for metal, wood, wax and PCBs, with an 8x8x3 in cutting area.
- [Penta Machine](https://www.pentamachine.com/) - Maker of the Pocket NC desktop 5-axis mill and the compact 5-axis Solo.

## Hobby & Small-Shop Routers

- [AltMill](https://sienci.com/altmill/) - Sienci Labs linear-rail, ball-screw CNC router for production work in 2x4, 4x4 and 4x8 ft sizes.
- [Avid CNC](https://www.avidcnc.com/) - Modular CNC router and plasma table kits ranging from benchtop to 5x10 ft formats.
- [LongMill](https://sienci.com/product-category/longmill/) - Sienci Labs benchtop CNC router kit for hobbyists, supplied with the gSender control software.
- [Onefinity CNC](https://www.onefinitycnc.com/) - Ball-screw hobby CNC routers; the Elite series adds closed-loop steppers and a MASSO controller.
- [Shapeoko](https://carbide3d.com/shapeoko/) - Carbide 3D's line of hobby and small-shop CNC routers, including the ball-screw Shapeoko 5 Pro.
- [X-Carve Pro](https://www.inventables.com/pages/x-carve-pro-cnc-machine) - Inventables' steel-frame, ball-screw router for small shops.

## DIY & Open-Source Machines

- [LowRider CNC](https://docs.v1e.com/lowrider/) - Mostly 3D-printed V1 Engineering router that scales from benchtop size up to full 4x8 ft sheets.
- [Maslow CNC](https://www.maslowcnc.com/) - Open-source large-format router; Maslow 4 moves a sled with four belts to cut full sheets.
- [MPCNC Primo](https://docs.v1e.com/mpcnc/intro/) - Mostly Printed CNC from V1 Engineering, built from 3D-printed parts and steel tubing.
- [PrintNC](https://wiki.printnc.info/en/home) - Open-source steel-tube CNC router design that can cut aluminum and steel, documented in a community wiki.

## Mills, Lathes & Plasma

- [Langmuir Systems](https://www.langmuirsystems.com/) - Maker of the CrossFire CNC plasma tables and the MR-1 gantry mill for home and small fab shops.
- [Tormach](https://tormach.com/) - Compact CNC mills, lathes and routers for small shops, run by the LinuxCNC-based PathPilot control.

## Firmware & Controllers

- [Buildbotics](https://buildbotics.com/) - Open-source enclosed CNC controller with built-in stepper drivers, a web interface and a G-code planner.
- [Centroid Acorn](https://www.centroidcnc.com/centroid_diy/acorn_cnc_controller.html) - Ethernet DIY CNC control board paired with Centroid's CNC12 software in free and paid tiers.
- [FluidNC](https://github.com/bdring/FluidNC) - Open-source ESP32 motion control firmware, successor to Grbl_ESP32, configured by YAML with a built-in web UI.
- [Grbl](https://github.com/gnea/grbl) - Original open-source G-code motion control firmware for Arduino Uno-class boards; mature and feature-frozen.
- [grblHAL](https://github.com/grblHAL/core) - Open-source, hardware-abstracted 32-bit successor to Grbl with drivers for many MCUs and a plugin system.
- [LinuxCNC](https://linuxcnc.org/) - Open-source real-time Linux machine controller for mills, lathes, routers, plasma cutters, robot arms and more.
- [Mach4](https://www.machsupport.com/software/mach4/) - Commercial Windows CNC control software from Newfangled Solutions with a plugin architecture for motion devices.
- [Marlin](https://marlinfw.org/) - Widely used open-source 3D printer firmware with optional laser and spindle control for light CNC machines.
- [MASSO](https://www.masso.com.au/) - Standalone touchscreen CNC controllers for routers, mills, lathes, plasma and lasers that need no PC.
- [PlanetCNC](https://planet-cnc.com/) - TNG control software and Mk3-series motion controllers for mills, routers, lathes and plasma.
- [RepRapFirmware](https://github.com/Duet3D/RepRapFirmware) - Open-source firmware for Duet3D controller boards with a dedicated CNC mode.
- [Smoothieware](https://smoothieware.org/) - Open-source modular G-code interpreter and CNC firmware for the open-hardware Smoothieboard controllers.
- [UCCNC](https://cncdrive.com/UCCNC.html) - Control software for CNCdrive's UC-series USB and Ethernet motion controllers, licensed per controller.

## Machine Control Software

- [bCNC](https://github.com/vlachoudis/bCNC) - Open-source Python GRBL sender with autoleveling, a G-code editor and basic CAM functions.
- [Candle](https://github.com/Denvi/Candle) - Open-source Qt-based GRBL control application with a G-code visualizer and height-map support.
- [Carbide Motion](https://carbide3d.com/carbidemotion/) - Free machine control software for Carbide 3D's Shapeoko and Nomad machines.
- [Carvera Community Controller](https://github.com/Carvera-Community/Carvera_Controller) - Community-developed, open-source controller software for Makera Carvera machines.
- [CNCjs](https://cnc.js.org/) - Open-source web interface for Grbl, Marlin, Smoothieware and TinyG controllers, often run on a Raspberry Pi.
- [gSender](https://sienci.com/gsender/) - Sienci Labs' open-source sender for grbl and grblHAL machines with 3D preview and probing tools.
- [ioSender](https://github.com/terjeio/ioSender) - Open-source Windows G-code sender for Grbl and grblHAL that exposes grblHAL's extended features.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL) - Open-source Windows GRBL sender optimized for laser engraving and cutting, with image and vector import.
- [Probe Basic](https://github.com/kcjengr/probe_basic) - Open-source, touchscreen-oriented LinuxCNC user interface with built-in probing routines.
- [Universal Gcode Sender](https://github.com/winder/Universal-G-Code-Sender) - Open-source, cross-platform Java G-code sender for GRBL, Smoothieware, TinyG and g2core with a 3D visualizer.

## CAD

- [Autodesk Fusion](https://www.autodesk.com/products/fusion-360/overview) - Commercial cloud-based CAD/CAM/CAE platform; the free personal-use license includes limited CAM.
- [build123d](https://github.com/gumyr/build123d) - Open-source Python BREP CAD framework on OpenCascade that evolves CadQuery's ideas with context managers.
- [CadQuery](https://github.com/CadQuery/cadquery) - Open-source Python library for building parametric CAD models on the OpenCascade kernel.
- [FreeCAD](https://www.freecad.org/) - Open-source parametric 3D modeler with sketcher, part design, assembly and an integrated CAM workbench.
- [Inkscape](https://inkscape.org/) - Open-source SVG vector editor often used to prepare 2D artwork for routers, lasers and plasma.
- [LibreCAD](https://librecad.org/) - Open-source, cross-platform 2D CAD application that reads and writes DXF and DWG files.
- [Onshape](https://www.onshape.com/) - Commercial browser-based parametric CAD; the free plan is for non-commercial work in public documents.
- [OpenSCAD](https://openscad.org/) - Open-source, script-based solid modeler that builds 3D models from code using CSG operations.
- [QCAD](https://qcad.org/) - Open-source, cross-platform 2D CAD; paid Professional and QCAD/CAM editions add DWG support and G-code.
- [SolveSpace](https://solvespace.com/) - Open-source, lightweight constraint-based 2D/3D modeler that exports DXF, STEP and STL.

## CAM

- [Carbide Create](https://carbide3d.com/carbidecreate/) - Free design and 2.5D CAM software for routers with V-carving; the paid Pro version adds 3D tools.
- [dxf2gcode](https://sourceforge.net/projects/dxf2gcode/) - Open-source Python tool that converts 2D DXF, PDF and PS drawings into G-code with configurable postprocessors.
- [Easel](https://easel.com/) - Browser-based CAD/CAM and machine control from Inventables; the Pro tier is a paid upgrade.
- [Estlcam](https://www.estlcam.de/) - Commercial Windows CAM and machine control program for 2.5D, V-carving and STL machining with a one-time license.
- [Fabex](https://github.com/pppalain/blendercam) - Open-source Blender CAM extension, formerly BlenderCAM, for 3-axis and multi-axis toolpaths and simulation.
- [F-Engrave](https://www.scorchworks.com/Fengrave/fengrave.html) - Open-source text and image engraving and V-carving G-code generator with inlay support.
- [FreeCAD CAM Workbench](https://wiki.freecad.org/CAM_Workbench) - FreeCAD's built-in toolpath generator, named the Path workbench before FreeCAD 1.0.
- [Fusion CAM](https://www.autodesk.com/products/fusion-360/fusion-for-manufacturing) - CAM inside Autodesk Fusion covering 2.5D to 5-axis milling, turning and editable post-processors.
- [G-Code Ripper](https://www.scorchworks.com/Gcoderipper/gcoderipper.html) - Open-source G-code tool for scaling, rotary wrapping, auto-probing and splitting programs.
- [Kiri:Moto](https://grid.space/kiri/) - Open-source browser-based slicer and CAM that generates 2.5D milling, laser and 3D printing toolpaths locally.
- [LightBurn](https://lightburnsoftware.com/) - Commercial layout, editing and machine control software for laser cutters and engravers.
- [Makera CAM](https://www.makera.com/pages/software) - CAM for Makera Carvera machines, free for owners; its successor Makera Studio is in public beta.
- [Mastercam](https://www.mastercam.com/) - Commercial industrial CAD/CAM suite for mill, lathe, mill-turn, Swiss, wire EDM and router programming.
- [MeshCAM](https://www.grzsoftware.com/) - Commercial three-axis CAM that generates toolpaths directly from STL and DXF files with minimal setup.
- [OpenCAMLib](https://github.com/aewallin/opencamlib) - Open-source C++ library with Python bindings for drop-cutter and waterline toolpath algorithms.
- [SheetCAM](https://www.sheetcam.com/) - Commercial sheet-cutting CAM for plasma, waterjet, laser, oxy-fuel and routing with nesting and lead-in control.
- [svg2gcode](https://github.com/sameer/svg2gcode) - Open-source Rust tool and web app that converts SVG vector graphics into G-code for plotters, lasers and CNC.
- [Vectric](https://www.vectric.com/) - Commercial Windows router CAD/CAM: Cut2D for 2D, VCarve for 2.5D and V-carving, and Aspire for 3D reliefs.

## Simulation & G-code Viewers

- [CAMotics](https://camotics.org/) - Open-source three-axis G-code simulator that renders toolpaths and the resulting cut workpiece in 3D.
- [NC Viewer](https://ncviewer.com/) - Free browser-based G-code viewer and machine simulator that processes files locally.

## Feeds & Speeds

- [FSWizard](https://zero-divide.net/fswizard) - Free online and mobile feeds and speeds calculator from Zero-Divide, the developer of HSMAdvisor.
- [G-Wizard](https://www.cnccookbook.com/g-wizard-feeds-speeds-calculator-mill/) - Commercial feeds and speeds calculator from CNCCookbook for mills, routers and lathes, with a hobby Lite edition.
- [HSMAdvisor](https://hsmadvisor.com/) - Commercial Windows feeds and speeds calculator with a tool database and cutting force estimates.

## CNC Project Files

- [3axis.co](https://3axis.co/) - Free DXF, SVG, CDR and STL files for CNC routers, laser cutters and plasma tables.
- [Bantam Tools CNC Projects](https://support.bantamtools.com/hc/en-us/categories/8515336915603-CNC-Resources-and-Projects) - Free desktop-milling projects in aluminum, brass and PCB stock, with G-code and Fusion files under a CC BY-NC-SA license.
- [Clickspring](https://www.clickspringprojects.com/) - Commercial and free metric PDF drawings for the clock parts and shop-made tools built in the Clickspring machining videos.
- [CutRocket](https://cutrocket.com/) - Carbide 3D's free project-sharing site for Carbide Create, Vectric and Fusion projects, open to any machine.
- [Design & Make](https://www.designandmake.com/) - Commercial library of CNC-ready 2D and 3D relief clipart in V3M, STL and RLF formats for Vectric software.
- [Easel Project Gallery](https://site.inventables.com/projects/) - Community projects made in Easel that can be opened, customized and carved on your own machine.
- [FireShare](https://fireshare.langmuirsystems.com/) - Langmuir Systems' library of plasma, laser and MR-1 milling projects in DXF, STEP and Fusion formats; mostly free, some paid.
- [Hemingway Kits](https://www.hemingwaykits.com/) - Commercial model-engineering and workshop-tool projects, such as the Quorn tool and cutter grinder, sold as kits or drawings.
- [Home Model Engine Machinist Plans](https://www.homemodelenginemachinist.com/forums/plans.12/) - Forum board where members share model engine plans, many free, for steam, IC and Stirling engines, often with CAD files.
- [Little Machine Shop Projects](https://littlemachineshop.com/pages/machinists-projects) - Free beginner machining plans, such as an oscillating engine, a knurling tool and vise clamps.
- [Makerables](https://www.makerables.com/) - Makera's project-sharing platform with free CNC project files, filterable by machine.
- [Tormach Project Library](https://tormach.com/project-library) - Free machining projects with CAD and CAM files, G-code, materials lists and step-by-step directions, made for Tormach machines.
- [Vectric Free Projects](https://www.vectric.com/vectric-community/free-projects/) - Over 300 free CNC and laser projects with files, materials lists and step-by-step videos.

## 3D & CAD Model Libraries

- [3Dfindit](https://www.3dfindit.com/) - Free CADENAS search engine for manufacturer-certified CAD models with shape and sketch search; successor to PARTcommunity.
- [FreeCAD Parts Library](https://github.com/FreeCAD/FreeCAD-library) - Community-maintained, CC BY-licensed parametric FreeCAD parts with STEP exports, including fasteners, bearings and profiles.
- [GrabCAD Library](https://grabcad.com/library) - Millions of free CAD models shared by engineers, with STEP and native files for fixtures and machined parts.
- [MakerWorld](https://makerworld.com/) - Bambu Lab's model community, with many free printable jigs, fixtures, vise jaws and shop accessories.
- [McMaster-Carr](https://www.mcmaster.com/) - Industrial supply catalog whose product pages offer free 2D and 3D CAD downloads of fasteners, clamps, dowel pins and other hardware.
- [MISUMI inCAD Library](https://us.misumi-ec.com/us/incadlibrary/) - Free downloadable CAD assemblies of 200+ machine mechanisms such as clamps, indexing tables and positioning units.
- [Printables](https://www.printables.com/) - Prusa's model library, including many printable CNC jigs, fixtures, dust shoes and accessories.
- [Thangs](https://thangs.com/) - Geometric search engine that finds 3D models across many sharing sites.
- [Thingiverse](https://www.thingiverse.com/) - Large 3D model repository that also hosts CNC router designs, jigs and machine upgrades.
- [TraceParts](https://www.traceparts.com/en) - Free library of supplier catalog parts in STEP, native CAD and 2D formats, with plugins for major CAD tools.

## Learning Resources

- [Carbide 3D Getting Started with CNC](https://carbide3d.com/hub/courses/getting-started-cnc/) - Free introductory course on CNC terminology, tooling, software and workflow.
- [CNCCookbook Free CNC Training](https://www.cnccookbook.com/online-cnc-training-courses-guides-help/) - Self-paced guides on G-code, feeds and speeds, CAD/CAM and CNC fundamentals.
- [Haas Learning Resources](https://www.haascnc.com/myhaas/Haas_Learning_Resources.html) - Hub for Haas Tip of the Day videos and training on CNC setup and programming.
- [LinuxCNC G-code Reference](https://linuxcnc.org/docs/html/gcode/g-code.html) - Detailed reference for RS274/NGC G-codes as implemented in LinuxCNC.
- [Machinery's Handbook](https://books.industrialpress.com/machinery-handbook/) - Standard reference for mechanical engineering and machining, now in its 32nd edition.
- [RepRap G-code Wiki](https://reprap.org/wiki/G-code) - G-code and M-code reference across RepRap-family firmwares such as Marlin and RepRapFirmware.
- [Titans of CNC Academy](https://academy.titansofcnc.com/) - Free CAD, CAM and CNC machining courses built around projects, with downloadable prints, models and setup sheets for each part.

## YouTube Channels

- [Abom79](https://www.youtube.com/@Abom79) - Job-shop machining and repair work from a third-generation machinist.
- [Blondihacks](https://www.youtube.com/@Blondihacks) - Hobby machine-shop projects, lathe work and beginner-friendly machining lessons.
- [Carbide 3D](https://www.youtube.com/@Carbide3D) - Tutorials and live shows on Shapeoko and Nomad machines, Carbide Create and Carbide Motion.
- [Clough42](https://www.youtube.com/@Clough42) - Lathe, CNC and electronics projects, including the electronic leadscrew build series.
- [Cutting Edge Engineering](https://www.youtube.com/@CuttingEdgeEngineering) - Heavy machining, line boring and repair of mining and earthmoving components.
- [Haas Automation](https://www.youtube.com/@HaasAutomation) - Official Haas channel with Tip of the Day lessons on CNC setup and programming.
- [Inheritance Machining](https://www.youtube.com/@InheritanceMachining) - Restoring a family machine shop and documenting detailed machining projects.
- [NYC CNC](https://www.youtube.com/@NYCCNC) - John Saunders' channel on Fusion CAD/CAM, CNC machining and running a machine shop.
- [Sienci Labs](https://www.youtube.com/@SienciLabs) - LongMill and AltMill tutorials, gSender guides and hobby CNC project videos.
- [Stefan Gotteswinter](https://www.youtube.com/@StefanGotteswinter) - Precision manual and CNC machining, scraping and shop-made tooling.
- [This Old Tony](https://www.youtube.com/@ThisOldTony) - Home-shop machining projects and tool builds explained with dry humor.
- [Titans of CNC](https://www.youtube.com/@TITANSofCNC) - Titan Gilroy's channel on production CNC machining, multi-axis work and free training.
- [Winston Moy](https://www.youtube.com/@WinstonMakes) - Desktop CNC projects, Shapeoko builds and digital fabrication experiments.

## Communities

- [Carbide 3D Community](https://community.carbide3d.com/) - Forum for Shapeoko and Nomad owners and Carbide Create and Carbide Motion users.
- [CNCArena](https://en.cncarena.com/forum/) - IndustryArena's manufacturing forum and the successor to CNCzone.
- [The Hobby-Machinist](https://www.hobby-machinist.com/) - Forum for home-shop machinists with beginner sections and machine-specific boards.
- [Langmuir Systems Forum](https://forum.langmuirsystems.com/) - Owner forum for CrossFire plasma tables and the MR-1 mill.
- [LinuxCNC Forum](https://forum.linuxcnc.org/) - Official user forum for LinuxCNC configuration, HAL, GUIs and machine builds.
- [Maslow CNC Forums](https://forums.maslowcnc.com/) - Community forum for Maslow builds, calibration, firmware and projects.
- [Onefinity CNC Forum](https://forum.onefinitycnc.com/) - Owner forum for Onefinity machines, upgrades and MASSO controller questions.
- [Practical Machinist](https://www.practicalmachinist.com/forum/) - Large forum for professional machinists covering CNC, CAM, tooling and shop management.
- [r/CNC](https://www.reddit.com/r/CNC/) - Subreddit for CNC machining discussion across hobby and industrial machines.
- [r/hobbycnc](https://www.reddit.com/r/hobbycnc/) - Subreddit for hobby CNC routers, mills and lasers.
- [r/Machinists](https://www.reddit.com/r/Machinists/) - Subreddit for manual and CNC machinists, programmers and apprentices.
- [Sienci Community Forum](https://forum.sienci.com/) - Forum for LongMill, AltMill and gSender users.
- [V1 Engineering Forum](https://forum.v1e.com/) - Community forum for LowRider and MPCNC builds, troubleshooting and projects.

## Related Lists

- [Awesome 3D Printing](https://github.com/ad-si/awesome-3d-printing) - Printers, slicers, CAD and resources for 3D printing.
- [Awesome Electronics](https://github.com/kitspace/awesome-electronics) - Resources for electronic engineers and hobbyists.
- [Awesome Makera](https://github.com/blackveilprecision/awesome-makera) - Resources for Makera desktop CNC machines, including the Carvera, Carvera Air and Z1.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md), or use the suggestion form linked at the top and let the bot do the rest.
