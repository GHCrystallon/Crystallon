---
title: "Tween Shell Fill (TSF)"
weight: 6
tags: [component, populate]
---

## Description

Fill voxels with morphed shell unit cells. Use one of the ‘Cell Morph’ tools to create values for each voxel then use two ‘tween’ type unit cells to morph between. Values range from 0 (unit cell 1) to 1 (unit cell 2). Unit cells must have the same topology (same list of curves or nodes).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit Cell 1 (U(s)1) - [mesh] - Single unit cell to populate voxels
- Unit Cell 2 (U(s)2) - [mesh] - Single unit cell to populate voxels
- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Values (Va) - [number] - List of values from 0-1 (flattened) corresponding to each voxel
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice (shell) (L(s)) - [mesh] - Joined mesh that makes up the lattice