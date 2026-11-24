# Sheet Metal DXF Export – Autodesk Inventor

**Version:** 1.0  
**Author:** Kuba Myślicki  
**Environment:** Autodesk Inventor 2026  
**Language:** English

## Description

Sheet Metal DXF Export is a VBA macro for Autodesk Inventor that automates the export of sheet metal flat patterns from an active assembly to DXF files.

The tool reduces repetitive manual work and speeds up manufacturing documentation preparation.

## Features

The macro automatically searches assemblies and subassemblies for sheet metal parts, creates missing flat patterns and exports unique parts to DXF files. It offers output folder selection, existing file handling, bend line visibility settings, and export progress monitoring with cancellation.

## Requirements

- Autodesk Inventor 2026.
- VBA macro support enabled in Inventor.

## Installation

1. Download `Sheet-Metal-DXF-Export-EN.ivb` from [Releases](../../releases).
2. Open Autodesk Inventor and press `Alt + F11`.
3. Select **File → Load Project** and choose the downloaded `.ivb` file.
4. Close the VBA Editor.
5. In Inventor, open **Tools → Macros**.
6. Select `SheetMetalDXFExport_EN` and click **Run**.

## How to use

Open an assembly (`.iam`), configure the export options and click **Export**. The DXF files will be saved in the selected output folder.

## Contact

Need other tools to automate your work in Autodesk Inventor?

**Kuba Myślicki**  
kuba.myslicki@gmail.com
