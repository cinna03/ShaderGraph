# Flipped Normals Shader (Shader Graph - URP)

## Overview
This project demonstrates a Shader Graph material in Unity’s Universal Render Pipeline (URP) that simulates flipped normals by rendering the backfaces of a sphere.

The viewer is placed inside the sphere, creating the illusion of being inside a 360-degree panoramic environment.

---

## Technologies Used
- Unity (URP)
- Shader Graph
- C#

---

## Key Features
- Shader Graph material with backface rendering
- Simulated flipped normals effect
- 360° panoramic environment
- Camera rotation to explore the interior
- Emission-based lighting for visibility

---

## How It Works

### Shader Logic
The shader does not modify the mesh geometry directly. Instead, it simulates flipped normals visually by rendering the **backfaces** of the sphere.

- The texture is sampled using UV coordinates
