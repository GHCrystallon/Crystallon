---
title: "Cell Morph Attractor (CMa)"
weight: 8
tags: [component, populate]
---

## Description

Morph unit cells with attractor(s).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the morph (minimum)
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the morph (minimum)

## Outputs

- Values (Va) - [number] - List of values from 0-1 corresponding to each voxel