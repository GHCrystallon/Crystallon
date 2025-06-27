---
title: "Mesh Flatten (MF)"
weight: 6
tags: [component, 2d]
---

## Description

Flatten a mesh surface and measure the strain per mesh face (requires Kangaroo2 https://www.food4rhino.com/app/kangaroo-physics). Disclaimer: This is a work in progress and has not been fully tested and validated.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Mesh (M) - [mesh] - Mesh to flatten
- Plane (Pl) - [plane] - Plane to flatten mesh to
- Threshold (Th) - [number] - Threshold for Kangaroo solver (~1e-7)
- Max iterations (I) - [number] - Maximum iterations for the Kangaroo solver

## Outputs

- Iterations (I) - [number] - Iterations of the kangaroo solver
- Flattened mesh (M) - [mesh] - The flattened mesh
- Mesh faces (Mf) - [mesh] - Faces of the flattened mesh (exploded into separate meshes)
- Ratio cP (cP) - [number] - Ratio of strain of mesh edges
- cP Lines (LcP) - [line] - Lines for preview
- Ratio cI (cI) - [number] - Ratio of strain on body centered lines
- cI Lines (LcI) - [line] - Lines for preview
- Ratio cF (cF) - [number] - Ratio of strain on face centered lines
- cF Lines (LcF) - [line] - Lines for preview
- Ratio average (Av) - [number] - Average ratio of strain per face