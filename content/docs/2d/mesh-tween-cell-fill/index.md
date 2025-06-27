---
title: "Mesh Tween Cell Fill (MTC)"
weight: 8
tags: [component, 2d]
---

## Description

Tween between lattice unit cells on mesh faces

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh cell 1 (Mc1) - [geometry] - Lattice cell unit to map to mesh faces
- Mesh cell 2 (Mc2) - [geometry] - Lattice cell unit to map to mesh faces
- Mesh faces - (Mf) - [mesh] - Mesh face (exploded as single meshes)
- Value (Va) - [number] - Value from 0-1 corresponding to each mesh face

## Outputs

- Lattice Hinge (L) - [curve] - Joined curves that make up the lattice hinge