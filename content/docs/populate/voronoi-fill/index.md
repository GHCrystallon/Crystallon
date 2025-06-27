---
title: "Voronoi Fill (VF)"
weight: 9
tags: [component, populate]
---

## Description

Fill a volume with randomized voronoi cells. Use attractors to vary the density.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Geometry (G) - [geometry] - Geometry to fill
- Number of points (N) - [number] - The initial number of random points to fill the volume
- Use Attractor (UA) - [boolean] - If true, points will be filtered by distance to attractor(s)
- Attractor (A) - [geometry] - Any geometry to use as attractor(s)
- Magnitude (Ma) - [number] - Magnitude of the random filtering
- Number of filtered points (N) - [number] - The number of points to filter
- Enable Voronoi (EV) - [boolean] - If true, voronoi cells will be generated (can be very slow)

## Outputs

- Voronoi Lattice (L) - [curves] - List of curves that make up the voronoi lattice
- Voronoi Lattice Skin (L) - [curves] - List of curves that make up the voronoi skin
- Preview Points (P) - [points] - Preview of points that will make up the voronoi lattice