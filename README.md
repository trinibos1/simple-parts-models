# simple-parts-models
Common mechanical/electronics part models in simple `.stl` and `.f3d` formats.
If you have 3d model of a part, upload it because why not.

## Current Parts

| Name | STL Location | F3D Location | Date Updated (YYYY-MM-DD) | URL to Part | Notes | Made By |
| --- | --- | --- | --- | --- | --- | --- |
| Adafruit DRV8833 board | `boards/Adafruit drv8833.stl` | `boards/Adafruit drv8833.f3d` | `2026-05-01` | `https://www.adafruit.com/product/3297` | will be update soon. | `Trinibos1` |
| MG996R servo | `servo/mg996r.stl` | `servo/mg996r.f3d` | `2026-05-01` | `https://a.co/d/0bT9kwSo` | Mg996R servo. | `Trinibos1` |
| N20 motor | `motors/N20 motor.stl` | `motors/N20 motor.f3d` | `2026-05-01` | `https://a.co/d/07hGXFBm` | N20 motor great for small RC cars. | `Trinibos1` |

## coming soon
- ESP-WROOM-32

## Working Together (Part List Format + How to Add)

Use this combined workflow when adding or updating parts.

### Part List Format

| Name | STL Location | F3D Location | Date Updated (YYYY-MM-DD) | URL to Part (example: Amazon) | Notes | Made By |
| --- | --- | --- | --- | --- | --- | --- |
| `<part name>` | `path/to/file.stl` | `path/to/file.f3d` | `2026-05-01` | `https://www.amazon.com/...` | `<short note>` | `<name or handle>` |

### How to Add a New Part

1. Add both model files (`.stl` and `.f3d`) to a relevant folder.
2. Add a new row to **Current Parts**.
3. Fill in all columns:
   - name
   - STL and F3D file locations
   - last update date
   - source/purchase URL (Amazon or other)
   - short notes about the model
   - who made it
