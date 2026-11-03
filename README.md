# Servo Sizing Workbench

Public GitHub Pages deployment of the F-series servo motor and drive sizing workbench.

## Public URL

https://lipslee.github.io/servo-sizing-workbench/

## Scope

- Uses the original v2 calculation convention for core screw-axis sizing.
- Retains the project-specific rated-torque / 3 static check and 0.7 drive-current reserve.
- Includes 17 SynTec single-axis drives and 16 multi-axis drive configurations from the V3.14.0 selection manual.
- Uses a multi-axis drive only when one unit can cover every calculated axis with distinct axis modules; if any axis cannot be covered, all axes use single-axis drives.
- Includes the AM90-30-F4 and AM90-30B-F4 catalog entries.
- Intended for preliminary selection; special process forces, preload, duty cycle, and thermal requirements still require separate verification.

The deployed `index.html` is a self-contained offline-capable page with embedded CSS, JavaScript, and catalog data.
