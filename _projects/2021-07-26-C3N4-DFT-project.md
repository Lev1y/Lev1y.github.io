---
layout: default
title: "First principle calculation of graphite-C3N4 monolayer, slab and tube using quantum espresso"
stack: "DFT, quantum espresso" 
pinned: false
order: 1
---

<h1 style="color: #cc0000">First principle calculation of graphite-C3N4 monolayer, slab and tube using quantum espresso</h1> 
<h2 style="color: #aaaaaa">Period: Jul 2021 - Present</h2>

## **Background** ##
The project required ZERO funding for licensing software and purchasing facility, except for the HPC clusters provided by NUS (thanks to NUS 😁 ). Though it is a big challenge. I believe this project is not only meaningful to the study of g-C3N4 but also instructive to those who have limited resources but keen on the DFT calculation.

## **Objective** ##
The ultimate objective of this project is obtaining a series of DOS (density of states), PDOS (projected density of states) and band structure of g-C3N4 in different shapes (monolayer, slab and tube). The calculated results should well explained the measured values from physical experiments.

## **Method** ##
The DFT calculation is performed by Quantum Espresso, an integrated and open-source suite for electronic-structure calculations and materials modeling at the nanoscale. Calculation scripts are processed in NUS HPC, which is able to provide enough hashrate. The cell structure of different C3N4 are modelled by Vesta, a 3D visualization program for molecules. To overcome the current shortage in QE that hybrid functional (HSE06) is not implemented in non-self-consistent field calculation, Wannier90 is used to calculate the maximally localized wannier functions, thus band structure. Other software and packages, such as PWgui, Xcrysden, Gnuplot, etc. are all downloadable and open-source. 

## **Selected results** (to be cont.) ##

[//]: # (cmcm的图<img src="/assets/images/2021-07-26-C3N4-DFT-project/cmcm.png" width="300"/>)

<img src="/assets/images/2021-07-26-C3N4-DFT-project/z2.png" width="300"/>

*Fig.1 g-C3N4 slab cell (28 atoms) with P63/mmc space group.*

<img src="/assets/images/2021-07-26-C3N4-DFT-project/DOS-total.jpg" width="600"/>

*Fig.2 Band gap of g-C3N4 slab cell (P63/mmc space group).*
