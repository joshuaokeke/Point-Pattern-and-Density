# Spatial Statistics Lab 3
Welcome to the Spatial Statistics Lab 3 repository! This repository contains R code for simulating various point patterns, including homogeneous and inhomogeneous Poisson processes, regular pattern point processes, and clustering pattern point processes using the `spatstat` package.

## Table of Contents

- [Introduction](#introduction)
- [Part 1: Simulation of Homogeneous Poisson Process](#part-1-simulation-of-homogeneous-poisson-process)
- [Part 2: Simulation of Inhomogeneous Poisson Process](#part-2-simulation-of-inhomogeneous-poisson-process)
- [Part 3: Regular Pattern Point Processes](#part-3-regular-pattern-point-processes)
- [Part 4: Clustering Pattern Point Processes](#part-4-clustering-pattern-point-processes)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This lab focuses on simulating different types of spatial point patterns using R and the `spatstat` package. It explores the generation of homogeneous and inhomogeneous Poisson processes, regular pattern point processes, and clustering pattern point processes. Each part of the lab demonstrates various functions and techniques for simulating and visualizing spatial point patterns.

## Part 1: Simulation of Homogeneous Poisson Process

In this part, we simulate a homogeneous Poisson process and explore different realizations of the process under Complete Spatial Randomness (CSR). We examine the generation of point patterns using the `rpoispp` function and analyze the implications of changing the intensity parameter on the resulting patterns.

## Part 2: Simulation of Inhomogeneous Poisson Process

This part focuses on simulating inhomogeneous Poisson processes with varying intensity functions. We explore the generation of point patterns using custom intensity functions and visualize the spatial distribution of points. Additionally, we analyze how changing the intensity function affects the resulting point patterns.

## Part 3: Regular Pattern Point Processes

Here, we investigate regular pattern point processes using the `rSSI` function. We generate and visualize several realizations of regular patterns with different inhibition distances and number of events. By plotting each realization, we observe the spatial arrangement of points and explore the concept of regularity in point patterns.

## Part 4: Clustering Pattern Point Processes

In this part, we explore clustering pattern point processes using the `rThomas` function. We generate and visualize several realizations of clustering patterns with different parameters. By plotting each realization, we observe the clustering behavior of points and examine the impact of parameters on the clustering intensity.

## Getting Started

To get started with the analysis, clone this repository to your local machine and open the R script file (`Spatial_Statistics_Lab_3.Rmd`) in RStudio or any R environment of your choice. Run each code chunk sequentially to execute the simulations and visualize the results.

```bash
git clone https://github.com/your-username/spatial-statistics-lab-3.git
