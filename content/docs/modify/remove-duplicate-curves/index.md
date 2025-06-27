---
title: "Remove Duplicate Curves (RD)"
weight: 6
tags: [component, modify]
---

## Description

Remove curves that share the same midpoint. This is a simple and fast method of removing duplicates by searching for common midpoints rather than common endpoints. Since all lattice curves should connect end-to-end, none should have common midpoints unless they are duplicates.

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice curves to filter
- Tolerance (T) - [number] - Tolerance for merging curves (distance between midpoints ~0.1 - 0.001)

## Outputs

- Lattice (L) - [curves] - Filtered lattice curves