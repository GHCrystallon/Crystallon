---
title: "LTCX Reader (LXI)"
weight: 3
tags: [component, utilities]
---

## Description

Reads a LTCX file and outputs beams and radii

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- File path (L) - [text] - File path of .ltcx file
- Enable beams (E) - [boolean] - Enable the generation of beam curves

## Outputs

- Nodes (P) - [point] - Nodes in the network
- Node radius (Rn) - [number] - a list of radii for each node
- Line-point connection (LP) - [number] - index of points that make up each beam
- Beam curves (B) - [curve] - If enabled, the beams as curves
- Beam Radius (Rb) - [number] - The radii of each beam (average of two nodes)