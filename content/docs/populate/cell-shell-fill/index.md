---
title: "Cell Shell Fill (CSF)"
weight: 4
tags: [component, populate]
---

## Description

Fill voxels with shell unit cells. Use the Unit Cell Selector and Cell Type to choose
from preset cells or create your own.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit Cell (shell) (U(s)) - [mesh] - Single unit cell to populate voxels
- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 -0.001)

## Outputs

- Lattice (shell) (L(s)) - [mesh] - Joined mesh that makes up the lattice