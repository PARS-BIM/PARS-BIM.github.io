---
title: Revit Plugin Help
---

# Revit Plugin — Help

> Version: 1.1.0 · Last updated: 2026-05-26

Welcome! This is the central help for the PARS-BIM plugins.

## Quick Start
General Access:
Open the PARS-BIM tab in your Revit ribbon to access all tools.

Common Tools (Available in all versions):

**View Templates:** Duplicate views based on predefined templates or import/export templates between projects.

**Sheets:** Re-number sheets, generate sheet lists from Excel files, and manage your sheet set organization.

**Family Placement:** Automatically map and place Revit families using AutoCAD blocks as a reference.

**Smart Filter:** Select elements based on existing V/G filters or categories. Create system-based filters instantly.

**Clash Review:** Integrate Navisworks clash reports directly into Revit or manage internal model collisions.

**Annotations:** Efficiently manage Marks, sync parameters, apply multiple tags, and clean up schematic linework with Break Point.

**License Manager:** View your current license status and activation details.

**About:** Access contact support, documentation, and our privacy policy.

Architecture Tools (Exclusive):

**Room Tools:** Automate room finishing, manage room parameters, and generate color-coded ceiling height legends.

**Auto Modeling:** Use CADtoBIM to convert 2D AutoCAD drawings into 3D Revit walls, doors, and windows automatically; includes Auto Join for cleaner model geometry.

**Magic Dimension:** Automatically generate dimensions for grids, wall openings, and windows based on your rules.

**Levels:** Create levels efficiently using both manual and rule-based generation methods.

MEP Tools (Exclusive):

**Routing & Modeling:** Generate parallel pipes/conduits, convert CAD lines to pipe systems, and convert rigid segments to flexible ducts/pipes.

**Crossing Engine:** Execute professional vertical routing and clash resolution using 2-point, 1-point, or fixed-distance crossing methods.

**MEP Alignment:** Utilize Match Elevations, Match Horizontally, and 3D Alignment for precise support and rack layouts.

**Connectors:** Streamline connectivity with Easy Connect (Single/Multiple), Align & Connect, and Branch Alignment tools.

**MEP Assistant:** Fix broken connections, restore undefined system types, rotate fittings, and manage MEP spacing with one-click utilities.
---

## Commands (Full Guides)

## Common Tools
- **View Templates**
  - [Duplicate views](commands/Duplicate-views.md)
  - [Export/import view templates](commands/Export-import-view-templates.md)
  
- **Sheets**
  - [Re-Number sheets](commands/Re-number-sheets.md)
  - [Create list from file](commands/Create-list-from-file.md)
  - [Sheets management](commands/sheets-management.md)
  
 - **Family Placement**
   - [Workplane based](commands/Family-placement-Workplane.md)
   - [Ceiling based - From RVT link](commands/Ceiling-based-RVT-link.md)
   - [Ceiling based - Host based](commands/Ceiling-based-host.md)

- **Smart Filter**
  - [Pick by Filter](commands/Pick-by-filter.md)
  - [Pick horizontal pipes](commands/Pick-horizontal-pipes.md)
  - [Create filter by Pipe systems](commands/Create-filter-by-pipe-systems.md)
  - [Create filter by Duct systems](commands/Create-filter-by-duct-systems.md)
  - [Select-Pipes-Ducts-By-Levels](commands/Selectpipesductsbylevel.md)
  - [Merge-saved-selections](commands/Merge-saved-selections.md)
  - [MEP elevation range](commands/MEP-level-range.md)
  - [Previous selections](commands/Previous-selections.md)

- **Clash Review**
  - [Clash Review-From Navisworks](commands/Clash-review.md)
  - [Clash Review-Inside Revit](commands/Inside-Revit.md)
  - [Show Error report items](commands/Error-report.md)

- **Annotations**
  - [Mark by sequence](commands/Mark-by-sequence.md)
  - [Sync parameters](commands/Sync-parameters.md)
  - [Multiple tags](commands/Multiple-tags.md)
  - [Break point](commands/Break-point.md)

## Architecture Tools

- **Room Tools**
  - [Room Finishing](commands/Room-Finishing.md)
  - [Room parameters](commands/Room-area.md)
  - [Ceiling heights](commands/Ceiling-heights.md)

- **Auto modelling**
  - [CADtoBIM](commands/CAD-to-BIM.md)
  - [Auto join](commands/Auto-join.md)

- **Magic Dimension**
  - [Grids dimension](commands/Magic-dimensions.md)
  - [Rough walls dimensions](commands/Magic-dimensions.md)
  - [Windows dimensions](commands/Magic-dimensions.md)  

- **Levels**
  - [Add Level](commands/Add-level.md)
  - [Rule based levels](commands/Rule-based-levels.md)
 
## MEP Tools

  - [Duct/Pipe to flexible](commands/Duct-pipe-to-flexible.md)
  - [Add to accessories](commands/Add-to-accessories.md)
  - [Change system type](commands/Change-system-type.md)
  - **Pipes/Conduits**
    - [Multiple pipes](commands/Multiple-pipes.md)
    - [Multiple conduits](commands/Multiple-conduits.md)
    - [Line to pipe](commands/Line-to-pipe.md)
  - **MEP Alignment**
    - [Match Elevations](commands/Match-elevation.md)
    - [Match horizontally](commands/Match-horizontally.md)
    - [MEP Spacing](commands/MEP-spacing.md)
  - **Crossing**
    - [Vertical cross - 2 point (Cross and keep elevation)](commands/vcross-2point.md)
    - [Vertical cross - 1 point (Change elevation)](commands/vcross-1point.md)
    - [Vertical cross - Fixed distance (Cross and keep elevation)](commands/vcross-fixed-distance.md)
    - [Vertical cross multiple elements - Fixed distance](commands/vcross-multiple.md)
  - **Connect MEP**
    - [Easy connect (Single)](commands/easy-connect-single.md)
    - [Easy connect (Multiple)](commands/easy-connect-multiple.md)
  - **MEP Assistant**
    - [Extend](commands/Extend.md)
    - [Elbow](commands/Elbow.md)
    - [Rotate element](commands/Rotate-element.md)
    - [Disconnect](commands/Disconnect.md)
    - [Branch alignment](commands/Branch-alignment.md)
    - [3D alignment](commands/3D-alignment.md)
    - [Align and connect](commands/Align-connect.md)

---

## Installation & Updates
- Install via Autodesk App Store as a `.bundle`.
- To update, replace with the latest version.


## Support
- Email: Hessam.na067@gmail.com
