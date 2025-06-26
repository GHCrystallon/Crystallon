---
title: "Conformal Pipe Parameter (CPp)"
weight: 15
tags: [component, voxelize]
---

## Description

Create a pipe of varying length and size voxels along a curve on a surface.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to conform to (mesh or brep)
- Curve (C) - [curve] - Curve to voxelize
- Periodic (P) - [boolean] - True if curve is closed
- Division Parameter (tD) - [number] - Parameter for voxel divisions (0-1)
- Distance (D) - [number] - Distance from surface
- Radius Parameter (tR) - [number] - Parameter for radius (0-1)
- Radius Domain (dR) - [domain] - Domain for radius
- Thickness Parameter (tTh) - [number] - Parameter for thickness (0-1)
- Thickness Domain (dTh) - [domain] - Domain for thickness
- Rotation (Ro) - [number] - Rotation (in degrees)
- Sides (Si) - [number] - Number of sides of pipe

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
