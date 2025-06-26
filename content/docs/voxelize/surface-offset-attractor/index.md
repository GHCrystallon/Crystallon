---
title: "Surface Offset Attractor (SOa)"
weight: 10
tags: [component, voxelize]
---

## Description

Offset a surface with attractor(s).

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Surface (S) - [surface] - Surface to offset
- Resolution U (Re(u)) - [number] - Number of surface divisions in the U direction
- Resolution V (Re(v)) - [number] - Number of surface divisions in the V direction
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Lower Limit (Li) - [number] - Smoothing of the surface closest to the attractor
- Influence (I) - [number] - Smoothed range of attractor influence (0-1)
- Magnitude (min) (Ma(min)) - [number] - Magnitude of the offset (minimum)
- Magnitude (max) (Ma(max)) - [number] - Magnitude of the offset (maximum)

## Outputs

- Surface (S) - [surface] - Offset surface
