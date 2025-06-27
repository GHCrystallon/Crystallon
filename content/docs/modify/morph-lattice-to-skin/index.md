---
title: "Morph Lattice to Skin (MLS)"
weight: 9
tags: [component, modify]
---

## Description

Morph lattice to connect to skin. This will move the nodes of the lattice within a set distance from the skin to the nearest node of the skin.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice to morph to skin
- Geometry (G) - [geometry] - Geometry to morph to (usually the geometry (mesh or brep) that makes the skin)
- Distance (D) - [number] - Maximum distance from geometry
- Geometry (G) - [geometry] - Geometry to morph to (usually the nodes or vertices of the skin)
- Distance (D) - [number] - Maximum distance to morph

## Outputs

- Lattice (L) - [curves] - Morphed lattice