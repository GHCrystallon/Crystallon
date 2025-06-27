---
title: "Morph Shell to Skin (MSS)"
weight: 10
tags: [component, modify]
---

## Description

Morph shell to connect to skin. This will move vertices of the mesh shell within a set distance from the skin to the closest point on the skin. Subdividing the mesh of the shell to add more vertices will have a smoother result but will take longer.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (shell) (L(s)) - [mesh] - Lattice shell to morph
- Geometry (G) - [geometry] - Geometry to morph to
- Distance (D) - [number] - Maximum distance from geometry

## Outputs

- Lattice (shell) (L(s)) - [mesh] - Morphed lattice shell