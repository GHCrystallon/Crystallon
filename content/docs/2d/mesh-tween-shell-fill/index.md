---
title: "Mesh Tween Shell Fill (MTF)"
weight: 10
tags: [component, 2d]
---

## Description

Tween between mesh shell unit cells on mesh faces

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh shell 1 (Ms1) - [geometry] - Lattice shell unit to map to mesh faces
- Mesh shell 2 (Ms2) - [geometry] - Lattice shell unit to map to mesh faces
- Mesh faces - (Mf) - [mesh] - Mesh face (exploded as single meshes)
- Value (Va) - [number] - Value from 0-1 corresponding to each mesh face
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice Hinge (shell) (Ls) - [mesh] - Joined mesh that make up the lattice hinge