---
title: "Surface Offset Value (SOv)"
weight: 8
tags: [component, voxelize]
---

## Description

Offset a surface with with a point cloud and corresponding values.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Surface (S) - [surface] - Surface to offset
- Resolution U (Re(u)) - [number] - Number of surface divisions in the U direction
- Resolution V (Re(v)) - [number] - Number of surface divisions in the V direction
- Points (S) - [point] - List of points (flattened)
- Values (Va) - [number] - List of values that correspond to points (flattened)
- Distance Influence (DI) - [boolean] - If true the distance between the points and voxels will affect the magnitude
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the offset (minimum)
- Magnitude (max) (Ma(max)) - [number] - Magnitude of the offset (maximum)

## Outputs

- Surface (S) - [surface] - Offset surface
