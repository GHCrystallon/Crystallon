---
title: "Lattice Thickness Value (LTv)"
weight: 1
tags: [component, thicken]
---

## Description

Apply thickness values to lattice curves with a point cloud and
corresponding values. The output will be one value for each curve.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice to thicken
- Points (S) - [point] - List of points (flattened)
- Values (Va) - [number] - List of values that correspond to points (flattened)
- Distance Influence (DI) - [boolean] - If true the distance between the points
- and voxels will affect the magnitude
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Lattice beam thickness (minimum)
- Magnitude (max) (Ma(max)) - [number] - Lattice beam thickness
- (maximum)

## Outputs

- Values (Va) - [number] - List of beam thickness values corresponding to each lattice curve