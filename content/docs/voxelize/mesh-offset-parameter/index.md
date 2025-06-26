---
title: "Mesh Offset Parameter (MOp)"
weight: 6
tags: [component, voxelize]
---

## Description

Offset a mesh uniformly into voxels. Quad based meshes will make a voxel per mesh face. If the mesh is triangulated, it subdivides the mesh so that each triangle becomes (3) 4-sided polygons, then offsets each point normal to the mesh surface to create a voxel on the surface.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh (M) - [mesh] - Mesh to offset
- Triangulated (Tri) - [boolean] - True if the mesh is triangulated. False if the mesh is quads.
- Distance (D) - [number] - Distance to offset mesh
- Parameter (t) - [number] - Range of numbers (0-1) for divisions

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Quad Mesh (M) - [mesh] - Quad mesh generated from the input mesh
