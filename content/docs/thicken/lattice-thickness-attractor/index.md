---
title: "Lattice Thickness Attractor (LTa)"
weight: 2
tags: [component, thicken]
---

## Description

Apply thickness values to lattice curves with attractor(s). The output will be one value for each curve.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice to thicken
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Lattice beam thickness (minimum)
- Magnitude (max) (Ma(max)) - [number] - Lattice beam thickness (maximum)

## Outputs

- Values (Va) - [number] - List of beam thickness values corresponding to each lattice curve