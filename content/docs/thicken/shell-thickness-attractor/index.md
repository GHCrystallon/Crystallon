---
title: "Shell Thickness Attractor (STa)"
weight: 4
tags: [component, thicken]
---

## Description

Apply thickness values to shell vertices with attractor(s). The output will be one value for each vertex of the mesh (useful for Weaverbird’s ‘Mesh Thicken’ tool).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (shell) (L(s)) - [mesh] - Lattice to thicken
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Lattice shell thickness (minimum)
- Magnitude (max) (Ma(max)) - [number] - Lattice shell thickness (maximum)

## Outputs

- Values (Va) - [number] - List of beam thickness values corresponding to each shell vertex