---
title: "Lattice Hinge (LH)"
weight: 1
tags: [component, 2d]
---

## Description

Create a ruled surface between two curves and unroll to apply kerf bending patterns. Disclaimer: This is a work in progress and not fully tested with real materials (requires Kangaroo https://www.food4rhino.com/app/kangaroo-physics).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Curve 1 (C1) - [curve] - Curve to loft between
- Curve 2 (C2) - [curve] - Curve to loft between
- U Divisions (U) - [number] - Divisions in the U direction
- V Divisions (V) - [number] - Divisions in the V direction
- Influence (I) - [number] - Influence from surface curvature (0-1)
- Voxel Height (H) - [number] - Height of voxels on surface

## Outputs

- Voxels (rolled) (Vr) - [twisted box] - Voxels of the rolled surface (for preview)
- Voxels (unrolled) (Vu) - [twisted box] - Voxels of the unrolled surface (for mapping)
- Panels (rolled) (Pr) - [surface] - Panels of the rolled surface (for preview)
- Panels (unrolled) (Pu) - [surface] - Panels of the unrolled surface (for mapping)
- Panel Values (V) - [number] - Values measuring curvature (0-1)
- Unrolled Surface (S) - [surface] - The unrolled surface