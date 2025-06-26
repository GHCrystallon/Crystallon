---
title: "Mesh Offset Value (MOv)"
weight: 7
tags: [component, voxelize]
---

## Description

Offset mesh faces into voxels with a point cloud and corresponding values.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh (M) - [mesh] - Mesh to offset
- Triangulated (Tri) - [boolean] - True if the mesh is triangulated. False if the mesh is quads.
- Points (S) - [point] - List of points (flattened)
- Values (Va) - [number] - List of values that correspond to points (flattened)
- Distance Influence (DI) - [boolean] - If true the distance between the points and voxels will affect the magnitude
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the offset (minimum)
- Magnitude (max) (Ma(max)) - [number] - Magnitude of the offset (maximum)
- Parameter (t) - [number] - Range of numbers (0-1) for divisions

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Quad Mesh (M) - [mesh] - Quad mesh generated from the input mesh
