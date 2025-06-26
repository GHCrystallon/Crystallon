---
title: Voxel Morph Value (VMv)
weight: 4
tags: [component, voxelize]
---

## Description

Morph voxels with a point cloud and corrosponding values.

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
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the morph (minimum)
- Magnitude (max) (Ma(max)) - [number] - Magnitude of the morph (maximum)

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells