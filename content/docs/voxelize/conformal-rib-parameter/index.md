---
title: "Conformal Rib Parameter (CRp)"
weight: 13
tags: [component, voxelize]
---

## Description

Create a row of varying length voxels along a curve on a surface (mesh or brep).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to conform to (mesh or brep)
- Curve (C) - [curve] - Curve to voxelize
- Periodic (P) - [boolean] - True if curve is closed
- Division Parameter (tD) - [number] - Parameter for voxel divisions (0-1)
- Height Parameter (tH) - [number] - Parameter for voxel height (0-1)
- Height Domain (dH) - [domain] - Domain for voxel height
- Width Parameter (tW) - [number] - Parameter for voxel width (0-1)
- Width Domain (dH) - [domain] - Domain for voxel width

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
