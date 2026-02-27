# 3D Radiation Pattern of an Omni-Directional Antenna

## 📌 Project Description
This project models and visualizes the 3D radiation pattern of an ideal omni-directional antenna using MATLAB.

The antenna radiates equally in all azimuth directions (φ) and has elevation dependence (θ).

---

## 📐 Mathematical Model

The electric field pattern is modeled as:

E(θ) = sin(θ)

Power Pattern:

P(θ) = |E(θ)|² = sin²(θ)

---

## 🔄 Coordinate Conversion

Spherical to Cartesian transformation:

x = r sin(θ) cos(φ)  
y = r sin(θ) sin(φ)  
z = r cos(θ)

---

## 📊 Results

The radiation pattern forms a toroidal (doughnut-shaped) structure.

Maximum radiation occurs at:

θ = 90° (horizontal plane)

Minimum radiation occurs at:

θ = 0° and 180° (along Z-axis)

---

## 🛠 Software Used
- MATLAB R2020 or newer

---

## 📁 Repository Structure
