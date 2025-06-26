---
title: Voxelize Distance (Vd)
weight: 1
tags: [component, voxelize]
---

## Description

Fill a volume with equal sized voxels. 

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs
 
- Geometry (G) - [geometry] - Geometry to voxelize 
- Plane (Pl) - [plane] - Base plane for voxels 
- Voxel Size X (X) - [number] - Size of voxels in X direction 
- Voxel Size Y (Y) - [number] - Size of voxels in Y direction 
- Voxel Size Z (Z) - [number] - Size of voxels in Z direction 
- Fill Completely (FC) - [boolean] - If true, Voxels will fill entire volume. If false, only Voxels with their centroid within the volume will be kept. 

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells

