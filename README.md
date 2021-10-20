# pll_OSU180
On-Chip Clock Multiplier (PLL) on OSU180 Workshop

Under construction!

## Overview

> This course will be an in-depth introduction to On-Chip Clock Multiplier (PLL) design and layout using open-source EDA tools (ngspice & Magic) on OSU180nm. This course starts with fundamentals (from CMOS inverter & basic semiconductor physics) to Advanced IP design Process, issues & ways to deal with them (by live demo of entire IP from Design to Layout).
> 
> 1. Introduction – Basics of IP, ASIC Design flow, On-chip clock Multiplier, PLL,
> 2. Theory & Fundamental Concepts – CMOS implementation, transistor sizing, 2nd order control system, IC fab process, Euler path.
> 3. Pre-layout Implementation (lab session) – setting up system with linux, installation of tools, IP design, simulation & verification
> 4. Post-layout Implementation (lab session) – device to block level layout, extracting parasitic capacitors, simulation & verification.
> 5. Summary & Conclusion – Review Results, Future work, Acknowledgement.

## Introduction

## Theory & Fundamentals Concepts

## Pre-layout Implementation

![](images/Captura%20de%20tela%202021-10-19%20150909.png)

![](images/Captura%20de%20tela%202021-10-19%20151034.png)

![](images/Captura%20de%20tela%202021-10-19%20151125.png)

```ngspice inv.cir```

![](images/Captura%20de%20tela%202021-10-19%20151126.png)

![](images/Captura%20de%20tela%202021-10-19%20151304.png)

![](images/Captura%20de%20tela%202021-10-19%20151421.png)

![](images/Captura%20de%20tela%202021-10-19%20152016.png)

![](images/Captura%20de%20tela%202021-10-19%20151919.png)

![](images/Captura%20de%20tela%202021-10-19%20152250.png)

![](images/Captura%20de%20tela%202021-10-19%20152333.png)

![](images/Captura%20de%20tela%202021-10-19%20152516.png)

## Post-layout Implementation

```magic -T SC??? **source**```

```
extract
ext2spice cthresh 0
ext2spice
```

## Summary & Conclusion
