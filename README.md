# Centrifugal Pump Vendor Data Checklist

A offline, No installation required, desktop application for process engineers to systematically review and verify centrifugal pump vendor data sheets and performance curves.

## Overview

This application provides a structured checklist of 27 critical verification steps that process engineers must complete when reviewing vendor-supplied pump documentation. It includes built-in calculators, automatic data linking between steps, and the ability to save progress and generate reports.

**Developed by:** [Homayoun Fallahi](https://ir.linkedin.com/in/homayoun-fallahi)  
**Based on guidelines by:** [Behnaz Motamed](https://nl.linkedin.com/in/behnaz-motamed)

## Installation & Usage

### Portable Executable

1. Download the latest release from the [Releases](../../releases) page
2. Extract the ZIP file to any location on your computer
3. Run `PumpChecklist.exe` (no installation required)
4. The application will start immediately

## App interface

<div align="center">
  <img src="/interface/1.png" alt="Light Mode" width="45%"/>
  <img src="/interface/2.png" alt="Miniapp Mode" width="45%"/>
</div>
<div align="center">
  <img src="/interface/3.png" alt="Light Mode" width="45%"/>
  <img src="/interface/4.png" alt="Miniapp Mode" width="45%"/>
</div>
<div align="center">
  <img src="/interface/5.png" alt="Light Mode" width="45%"/>
  <img src="/interface/6.png" alt="Miniapp Mode" width="45%"/>
</div>

## Features

### Core Functionality
- **27-Step Checklist**: Comprehensive verification process covering all critical pump parameters
- **Visual Guide**: Real datasheet examples for each checklist step (Each step includes a real example from an actual pump datasheet to guide you. However, **datasheet formats vary between vendors**).
- **Interactive Calculators**: Built-in calculators for:
  - Flow rate ratios
  - Differential pressure and head
  - NPSHA (Net Positive Suction Head Available)
  - Rated power
  - BEP (Best Efficiency Point) checks
  - Shut-off pressure
  - Suction specific speed
  - And more...

### Intelligent Data Linking
- Automatic value transfer between related steps
- Real-time validation and range checking
- Dynamic status indicators for preferred and allowable operating regions

### User Interface
- **Visual Guide**: Sample images for each checklist step
- **LaTeX Formula Rendering**: For mathematical notation display
- **Color-Coded Status**: Instant visual feedback (Green=OK, Red=Not OK, Gray=Untouched)
- **Progress Tracking**: Visual progress bar
- **Referenced Notes**: Contextual notes appear automatically when relevant

### Data Management
- **Save/Load Progress**: Save your work as JSON files and resume later
- **Export Options**: 
  - Copy summary to clipboard (Excel-compatible)
  - Print report to browser (To save as PDF)
- **Autosave Prompts**: Never lose your work with unsaved changes warnings

## How to Use

### Getting Started

1. **Launch the Application**: Run the `.exe` file
2. **Navigate Through Steps**: Use the checklist panel on the left or the Previous/Next buttons
3. **Review Each Step**: Read the description, formulas, and view the sample image
4. **Use Calculators**: Enter values in the calculator fields (results update automatically)
5. **Add Comments**: Document vendor notes or discrepancies in the comments section
6. **Mark Status**: Click ✓ OK or ✗ Not OK buttons to mark each step

### Key Workflows

#### Saving Your Progress
- **File > Save**: Save to current file
- **File > Save As...**: Save with a new name
- Files are saved in JSON format for easy sharing and backup

#### Viewing Results
- **View > View Summary Report**: Opens a complete summary table
- From the report, you can:
  - Copy data to clipboard for Excel
  - Print to browser for PDF export

#### Starting a New Checklist
- **File > New**: Start fresh (prompts to save current work)
- **File > Load Progress**: Open a previously saved checklist

### Calculator Features

- Many calculators **auto-fill** with data from previous steps
- Example: Step 5 (Differential Head) automatically loads pressure values from Step 3
- All pre-filled values can be edited if needed
- Calculations update in real-time as you type

### Status Indicators

| Color | Meaning |
|-------|---------|
| 🟢 Green | Step verified OK |
| 🔴 Red | Issues found (Not OK) |
| ⚪ Gray | Not yet reviewed |

## Checklist Items

The application includes the following checklist items:

1. Check the pump tag
2. Check the flow rate
3. Check the suction and discharge pressure
4. Check pumping liquid
5. Check the differential head
6. Check NPSHA vs. designer's data sheet
7. Check starting condition
8. Check whether the pump is utilized continuously or intermittently
9. Check the site data
10. Check the pump performance
11. Check the rated power
12. Check the minimum flow
13. Check the BEP
14. Check Preferred operating region
15. Check allowable operating region
16. Check the maximum head at rated impeller
17. Check the maximum power at rated impeller
18. Check NPSHR at rated capacity
19. Max/Actual suction specific speed
20. Check the utility conditions
21. Check the NOTE section
22. Check the pump suction and discharge lines
23. Check the pump nozzle connections
24. Check the pump casing auxiliary connections
25. Type of pump seal plan
26. Check heating and cooling
27. Check the sump arrangement

## Calculators

The application includes calculators for:

- Flow rate ratio calculation
- Differential pressure calculation
- Differential head calculation
- NPSHA calculation
- Rated power calculation
- BEP check (80% - 110%)
- Head ratio calculation
- Shut-off pressure calculation
- Suction specific speed calculation

## Acknowledgments

This application was developed to streamline the pump data sheet review process for process engineers, following industry-standard practices and API-610 guidelines.

---

**Note**: This tool is designed to assist process engineers in their review process. It does not replace professional engineering judgment or detailed analysis of vendor documentation.
