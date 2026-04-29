# Apple II Family Keyboard SVG Project

This project aims to create high-quality, hand-coded SVG representations of every keyboard variation produced for the Apple II, II+, and IIe computer family. 

Each SVG is meticulously crafted to reflect the physical geometry, layout, and legends of specific historical hardware, including regional variations and different production editions.

## Naming Convention

Files are named using the following hierarchy:
`[Model]-[Region]-[Edition].svg`

- **Model**: The computer or keyboard model (e.g., `apple2`, `apple2plus`, `apple2e`).
- **Region**: The geographical layout standard (e.g., `us`, `uk`, `fr`, `de`).
- **Edition**: The specific revision or design style (e.g., `original`, `platinum`, `enhanced`).

## Technical Standards

- **Pure SVG**: All files are static, standard SVG 1.1. No external frameworks or compilation required.
- **Reusable Symbols**: Keys are defined as `<symbol>` elements in the `<defs>` section for consistency.
- **3D Effect**: Keys utilize beveled paths and varied fill colors to simulate a 3D physical keycap.
- **Cross-Browser Compatibility**: Symbols use `overflow="visible"` to prevent clipping in strict renderers like Firefox.

## Project Matrix

| Model         | Region | Edition  | Filename                     | Status |
| :------------ | :----- | :------- | :--------------------------- | :----- |
| Apple II      | US     | Original | `apple2-us-original.svg`     | ✓      |
| Apple II Plus | US     | Original | `apple2plus-us-original.svg` |        |
| Apple II Plus | JP     | J-Plus   | `apple2plus-jp-jplus.svg`    |        |
| Apple IIe     | US     | Original | `apple2e-us-original.svg`    |        |
| Apple IIe     | US     | Enhanced | `apple2e-us-enhanced.svg`    |        |
| Apple IIe     | UK     | Original | `apple2e-uk-original.svg`    |        |
| Apple IIe     | UK     | Enhanced | `apple2e-uk-enhanced.svg`    |        |
| Apple IIe     | UK     | Platinum | `apple2e-uk-platinum.svg`    | ✓      |
| Apple IIe     | JP     | Original | `apple2e-jp-original.svg`    |        |
| Apple IIe     | JP     | Enhanced | `apple2e-jp-enhanced.svg`    |        |
| Apple IIe     | JP     | Platinum | `apple2e-jp-platinum.svg`    |        |
| Apple IIe     | FR     | Original | `apple2e-fr-original.svg`    |        |
| Apple IIe     | FR     | Enhanced | `apple2e-fr-enhanced.svg`    |        |
| Apple IIe     | DE     | Original | `apple2e-de-original.svg`    |        |
| Apple IIe     | DE     | Enhanced | `apple2e-de-enhanced.svg`    |        |
| Apple IIe     | IT     | Original | `apple2e-it-original.svg`    |        |
| Apple IIe     | IT     | Enhanced | `apple2e-it-enhanced.svg`    |        |
| Apple IIe     | ES     | Original | `apple2e-es-original.svg`    |        |
| Apple IIe     | ES     | Enhanced | `apple2e-es-enhanced.svg`    |        |
| Apple IIe     | SE     | Original | `apple2e-se-original.svg`    |        |
| Apple IIe     | SE     | Enhanced | `apple2e-se-enhanced.svg`    |        |
| Apple IIe     | US     | Platinum | `apple2e-us-platinum.svg`    |        |

---
*Note: This list is limited to the Apple II, II+, and IIe desktop models.*
