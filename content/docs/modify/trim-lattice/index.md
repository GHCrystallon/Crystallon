---
title: "Trim Lattice (TL)"
weight: 1
tags: [component, modify]
---

## Description

Trim lattice with a closed volume (mesh or brep). This will trim the lattice curves to within the boundary of a closed volume.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [brep / mesh] - Geometry to trim with (closed brep or mesh)
- Lattice (L) - [curves] - Lattice curves to trim

## Outputs

- Trimmed Lattice (L) - [curves] - Lattice curves that have been trimmed
- Untrimmed Lattice (L) - [curves] - Lattice curves that have not been trimmed (Typically removes curves with valence 1)