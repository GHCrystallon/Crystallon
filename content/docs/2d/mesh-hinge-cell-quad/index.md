---
title: "Mesh Hinge Cell - Quad (MHq)"
weight: 12
tags: [component, 2d]
---

## Description

Map a quad based parametric cell with two domains to mesh faces. (This is an
example of how to use parameters from the “Mesh Flatten” component).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Parameter 1a (t1a) - [number] - Value 0-1
- Parameter 1b (t1b) - [number] - Value 0-1
- Parameter 1c (t1c) - [number] - Value 0-1
- Parameter 1d (t1d) - [number] - Value 0-1
- Parameter 2a (t2a) - [number] - Value 0-1
- Parameter 2b (t2b) - [number] - Value 0-1
- Parameter 2c (t2c) - [number] - Value 0-1
- Parameter 2d (t2d) - [number] - Value 0-1
- Mesh faces - (Mf) - [mesh] - Mesh face (exploded as single meshes)
- Tolerance (T) - [number] - Tolerance for merging faces and vertices (~0.1 - 0.001)

## Outputs

- Lattice Hinge (shell) (Ls) - [mesh] - Joined mesh that make up the lattice hinge