---
title: "LTCX Writer (LXO)"
weight: 2
tags: [component, utilities]
---

## Description

Creates a LTCX file format from a beam based lattice

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Graph ID (ID) - [text] - id, unique (within the file) integer
- Name (Name) - [text] - File name
- Units (Units) - [text] - Units (in/mm/cm/m/ft)
- Type (Tye) - [text] - Cross section (rnd)
- Lattice Curves (L) - [curve] - Lattice curves
- Node Radius (N) - [number] - List of beam radii that will be averaged to each node
- Tolerance (T) - [number] - Tolerance to merge points

## Outputs

- Output (O) - [text] - output text (copy and paste contents to a text editor and save with *.ltcx extension)