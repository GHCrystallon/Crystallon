---
title: "Lattice Hinge Shell Fill (LHS)"
weight: 4
tags: [component, 2d]
---

## Description

Populate lattice hinge panels with a shell based unit cell

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit cell (shell) (U(s)) - [mesh] - Unit cell to populate lattice hinge panels
- Voxels (V) - [twisted box] - Voxels to be populated with unit cells
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice Hinge (shell) (L(s)) - [mesh] - Joined mesh that make up the lattice hinge