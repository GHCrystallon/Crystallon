---
title: "Morph Between Meshes (MBM)"
weight: 11
tags: [component, voxelize]
---

## Description

Create voxels between the faces of meshes with matching topology.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Meshes (M) - [mesh] - Meshes to morph between
- Triangulated (Tri) - [boolean] - True if the mesh is triangulated. False if the mesh is quads.
- Parameter (t) - [number] - Range of numbers (0-1) for divisions

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Quad Mesh (M) - [mesh] - Quad mesh generated from the input mesh
