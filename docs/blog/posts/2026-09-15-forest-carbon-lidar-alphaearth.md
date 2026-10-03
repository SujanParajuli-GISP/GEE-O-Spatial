---
date: 2026-09-15
authors:
  - sujan
categories:
  - LiDAR
  - Google Earth Engine
tags:
  - forest carbon
  - deep learning
  - AlphaEarth
---

# Forest Carbon Estimation with AlphaEarth Foundations and Airborne LiDAR

Estimating forest carbon at scale means combining the *breadth* of satellite embeddings with
the *vertical detail* of LiDAR.

<!-- more -->

## The idea

Airborne LiDAR measures canopy structure directly, but coverage is patchy. Satellite
foundation-model embeddings such as AlphaEarth Foundations cover everything but see only the
surface. Training a model on both lets us extend LiDAR-quality estimates across the landscape.

## Where to go next

The workflow, with Python and deep-learning code, is in the repository
[GEE_MediumBlog_Logic_ForestCarbon_Estimation_with_LiDAR](https://github.com/SujanParajuli-GISP/GEE_MediumBlog_Logic_ForestCarbon_Estimation_with_LiDAR).

More hands-on material is in our [training resources](../../services/training-resources.md).

!!! note "Starter post"
    This is a starter post. Replace it with your own write-up, figures, and results.
