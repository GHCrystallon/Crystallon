---
title: "Cell Morph Value (CMv)"
weight: 7
tags: [component, populate]
---

## Description

Morph unit cells with a point cloud and corresponding values.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Points (S) - [point] - List of points (flattened)
- Values (Va) - [number] - List of values that correspond to points (flattened)
- Distance Influence (DI) - [boolean] - If true the distance between the points and voxels will affect the magnitude
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)

## Outputs

- Values (Va) - [number] - List of values from 0-1 corresponding to each voxel