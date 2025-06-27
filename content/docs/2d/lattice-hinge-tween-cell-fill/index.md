---
title: "Lattice Hinge Tween Cell Fill (LHT)"
weight: 3
tags: [component, 2d]
---

## Description

Tween between lattice hinge panels with curve based unit cells

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Unit cell 1 (U(c)) - [curve] - Unit cell to populate lattice hinge panels
- Unit cell 2 (U(c)) - [curve] - Unit cell to populate lattice hinge panels
- Value (Va) - [number] - Value from 0-1 corresponding to each panel
- Panels (P) - [surface] - Panels to be populated with unit cells

## Outputs

- Lattice Hinge (L) - [curve] - List of curves that make up the lattice hinge