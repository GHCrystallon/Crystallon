---
title: "Mesh Shell Fill (MSF)"
weight: 9
tags: [component, 2d]
---

## Description

Map shell lattice unit cells to mesh faces

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh shell (Ms) - [geometry] - Lattice shell unit to map to mesh faces
- Mesh faces - (Mf) - [mesh] - Mesh face (exploded as single meshes)
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice Hinge (shell) (Ls) - [mesh] - Joined mesh that make up the lattice hinge