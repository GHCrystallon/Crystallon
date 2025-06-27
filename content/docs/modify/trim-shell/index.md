---
title: "Trim Shell (TS)"
weight: 2
tags: [component, modify]
---

## Description

Trim shell lattice with a closed volume (mesh or brep). This will trim a shell by removing the mesh vertices that are outside of the boundary of a closed mesh or brep. Subdividing the mesh of the shell to add more vertices before trimming will make a more accurate trim but will take longer.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (shell) (L(s)) - [mesh] - Lattice shell to trim
- Geometry (G) - [brep / mesh] - Geometry to trim with (closed brep or mesh)

## Outputs

- Lattice (shell) (L(s)) - [mesh] - Trimmed lattice shell