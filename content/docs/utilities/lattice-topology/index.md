---
title: "Lattice Topology (LT)"
weight: 1
tags: [component, utilities]
---

## Description

Creates a clean graph from a lattice with unique nodes and their connections

| | |
| ---: | :--- |
|{{< figure src="comp.png" width="100%" >}} |{{< figure src="ex.png">}} |
{.no-border}

## Inputs

- Lattice (L) - [curves] - Lattice curves
- Tolerance (T) - [number] - Tolerance to merge points

## Outputs

- Nodes (P) - [point] - sorted unique points in the network
- Line-Point Connections (LP) - [number] - Index of points that make up each beam
- Point-Line Connections (PL) - [number] - For each point, lists the index of the lines connected to it