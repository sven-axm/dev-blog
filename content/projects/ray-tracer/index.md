---
title: "Path Tracer"
date: 2024-11-05
draft: false
description: "A physically-based path tracer implemented in C++ from scratch"
summary: "Monte Carlo path tracing implementation with support for various materials, light sources, and advanced rendering techniques."
tags: ["C++", "Graphics", "Ray Tracing", "Computer Graphics"]
---

![Path Tracer Icon](icon.png)

**🔗 [View on GitHub](https://github.com/sven-axm/path-tracer)**

An educational project that implements a Monte Carlo path tracer from first principles. This renderer produces photorealistic images by simulating light transport through physical scenes.

## Technical Details

- Monte Carlo integration for global illumination
- Support for various BRDF models (Lambertian, Phong, Cook-Torrance)
- Acceleration structures (BVH) for fast ray-scene intersection
- Multi-threaded rendering with progressive image updates
- Export to various image formats (PNG, EXR)

While not optimized for real-time rendering, this project provides deep insights into how modern renderers work. Each component is implemented from scratch, making it an excellent learning resource for understanding physically-based rendering.

