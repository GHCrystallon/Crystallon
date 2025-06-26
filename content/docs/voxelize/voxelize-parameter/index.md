---
title: Voxelize Parameter (Vp)
weight: 2
tags: [component, voxelize]
---

## Description

Fill a volume with varying sized voxels.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to voxelize
- Plane (Pl) - [plane] - Base plane for voxels
- X Parameter (tX) - [number] - Range of numbers (0-1) for divisions
- Y Parameter (tY) - [number] - Range of numbers (0-1) for divisions
- Z Parameter (tZ) - [number] - Range of numbers (0-1) for divisions
- Fill Completely (FC) - [boolean] - If true, Voxels will fill entire volume. If false, only Voxels with their centroid within the volume will be kept.

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells