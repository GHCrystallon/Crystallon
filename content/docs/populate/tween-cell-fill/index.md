---
title: "Tween Cell Fill (TCF)"
weight: 5
tags: [component, populate]
---

## Description

Fill voxels with morphed lattice unit cells. Use one of the ‘Cell Morph’ tools to create values for each voxel then use two ‘tween’ type unit cells to morph between. Values range from 0 (unit cell 1) to 1 (unit cell 2). Unit cells must have the same topology (same list of curves or nodes).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit Cell 1 (U) - [curves] - Single unit cell to populate voxels
- Unit Cell 2 (U) - [curves] - Single unit cell to populate voxels
- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Values (Va) - [number] - List of values from 0-1 (flattened) corresponding to each voxel

## Outputs

- Lattice (L) - [curves] - List of curves that make up the lattice