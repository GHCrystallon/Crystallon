---
title: "Conformal Skin (CSk)"
weight: 4
tags: [component, modify, v2.1, beta]
---

## Description

Create a conformal lattice skin at the boundary of the primitive geometry. Connect hanging elements based on unit cell connectivity.

<!-- | | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border} -->

## Inputs

- Voxels (Voxels) - [twisted box] - Boundary voxels containing lattice elements to connect
- Connectivity (Connectivity) - [mesh] - Mesh or brep defining how unit cell curves should be connected
- Geometry (Geometry) - [mesh] - Geometry to trim with (closed brep or mesh)

## Outputs

- Skin (Skin) - [generic data] - Curves that make the conformal lattice skin

