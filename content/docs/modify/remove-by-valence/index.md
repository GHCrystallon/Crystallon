---
title: "Remove by Valence (RV)"
weight: 5
tags: [component, modify]
---

## Description

Remove curves by number of connections (this can be very slow, sorry). If only removing valence 1, the ‘Untrimmed Lattice’ output of Trim Lattice will have the same result.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice curves to filter
- Valence Number (N) - [number] - Minimum number of connections each curve has
- Flip (F) - [boolean] - If true, curves under valence number are removed. If false, curves over valence number are removed

## Outputs

- Lattice (L) - [curves] - Filtered lattice curves