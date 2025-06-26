---
title: "Conformal Rib Distance (CRd)"
weight: 12
tags: [component, voxelize]
---

## Description

Create a row of equal length voxels along a curve on a surface (mesh or brep).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to conform to (mesh or brep)
- Curve (C) - [curve] - Curve to voxelize
- Periodic (P) - [boolean] - True if curve is closed
- Length (L) - [number] - Length of voxels
- Height (H) - [number] - Height of voxels
- Width (W) - [number] - Width of voxels

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells