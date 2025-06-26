---
title: "Conformal Pipe Distance (CPd)"
weight: 14
tags: [component, voxelize]
---

## Description

Create a pipe of equal length voxels along a curve on a surface.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to conform to (mesh or brep)
- Curve (C) - [curve] - Curve to voxelize
- Periodic (P) - [boolean] - True if curve is closed
- Length (L) - [number] - Length of voxels
- Distance (D) - [number] - Distance from surface
- Radius (Ra) - [number] - Inner radius of pipe
- Thickness (Th) - [number] - Thickness of pipe
- Rotation (Ro) - [number] - Rotation (in degrees)
- Sides (Si) - [number] - Number of sides of pipe

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
