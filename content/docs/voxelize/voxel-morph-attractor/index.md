---
title: "Voxel Morph Attractor (VMa)"
weight: 5
tags: [component, voxelize]
---

## Description

Morph voxels with attractor(s).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (Ma) - [number] - Magnitude of the morph

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells