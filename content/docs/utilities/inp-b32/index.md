---
title: "INP B32 (B32)"
weight: 4
tags: [component, utilities]
---

## Description

Create a B32 INP file from a lattice

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Filename (F) - [text] - Name of file (also NSET, ELSET, etc)
- Lattice Curves (L) - [curve] - Lattice curves
- Tolerance (T) - [number] - Tolerance to merge points
- Cross Section (Cs) - [text] - True if CIRC, false if RECT
- Width (W) - [number] - Width of cross section
- Height (H) - [number] - Height of cross section

## Outputs

- Output (O) - [text] - output text (copy and paste contents to a text editor and save with *.inp extension)