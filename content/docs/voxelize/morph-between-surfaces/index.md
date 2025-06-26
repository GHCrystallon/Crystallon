---
title: Morph Between Surfaces (MBS)
weight: 3
tags: [component, voxelize]
---

## Description

Conformal fill of voxels between two or more surfaces.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Surfaces (S) - [surface] - At least 2 surfaces to morph voxels between
- X Parameter (tX) - [number] - Range of numbers (0-1) for divisions
- Y Parameter (tY) - [number] - Range of numbers (0-1) for divisions
- Z Parameter (tZ) - [number] - Range of numbers (0-1) for divisions

## Outputs

- Voxels (V) - [twistedbox] - Voxels to be filled with unit cells