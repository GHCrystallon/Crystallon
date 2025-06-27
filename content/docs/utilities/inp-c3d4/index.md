---
title: "INP C3D4 (C3D4)"
weight: 9
tags: [component, utilities]
---

## Description

Creates a C3D4 INP file from a tetrahedral mesh (requires Tetrino https://www.food4rhino.com/app/tetrino)

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Filename (F) - [text] - Name of file (also NSET, ELSET, etc)
- Indices (I) - [number] - Indices of tetrahedrons (”I” output of Tetgen)
- Points (P) - [point] - Points of tetrahedral mesh (”P” output of Tetgen)

## Outputs

- Output (O) - [text] - output text (copy and paste contents to a text editor and save with *.inp extension)