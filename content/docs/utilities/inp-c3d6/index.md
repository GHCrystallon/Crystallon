---
title: "INP C3D6 (C3D6)"
weight: 7
tags: [component, utilities]
---

## Description

Creates a C3D6 INP file from a triangulated mesh.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Filename (F) - [text] - Name of file (also NSET, ELSET, etc)
- Lattice shell (L(s)) - [mesh] - Lattice shell (as joined mesh)
- Thickness (T) - [number] - Thickness of cross section (offset)

## Outputs

- Output (O) - [text] - output text (copy and paste contents to a text editor and save with *.inp extension)