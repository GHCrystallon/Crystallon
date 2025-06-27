---
title: "Shell Thickness Value (STv)"
weight: 3
tags: [component, thicken]
---

## Description

Apply thickness values to shell vertices with a point cloud and corresponding values. The output will be one value for each vertex of the mesh (useful for Weaverbird’s ‘Mesh Thicken’ tool).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (shell) (L(s)) - [mesh] - Lattice to thicken
- Points (S) - [point] - List of points (flattened)
- Values (Va) - [number] - List of values that correspond to points (flattened)
- Distance Influence (DI) - [boolean] - If true the distance between the points
- and voxels will affect the magnitude
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - shell thickness (minimum)
- Magnitude (max) (Ma(max)) - [number] - shell thickness (maximum)

## Outputs

- Values (Va) - [number] - List of thickness values corresponding to each shell vertex