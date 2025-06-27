---
title: "Lattice Hinge Tween Shell Fill (LHTs)"
weight: 5
tags: [component]
---

## Description

Tween between lattice hinge panels with shell based unit cells

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit cell 1 (shell) (U(s)1) - [mesh] - Unit cell to populate lattice hinge panels
- Unit cell 2 (shell) (U(s)2) - [mesh] - Unit cell to populate lattice hinge panels
- Voxels (V) - [twisted box] - Voxels to be populated with unit cells
- Value (Va) - [number] - Value from 0-1 corresponding to each voxel
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice Hinge (shell) (L(s)) - [mesh] - Joined mesh that make up the lattice hinge