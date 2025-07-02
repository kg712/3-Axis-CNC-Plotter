
# LEGO 3-Axis CNC Plotter (C++)

A LEGO-powered 3-axis CNC plotter built from Technic parts and controlled using C++. This project turns a pile of LEGO into a working drawing machine capable of reading simple G-code-style instructions and plotting 2D images.

Built for fun, learning, and flexing some mechanical + programming muscle 💪.

## 🧱 What It Does

- 3-axis movement: X and Y axes for 2D motion, Z-axis to raise/lower pen
- C++ firmware to control movement and interpret basic drawing commands
- Uses LEGO motors and structural components for full motion system
- Can plot basic shapes and designs from text commands

## ⚙️ Hardware

- LEGO Technic frame (custom design)
- 3 LEGO motors (1 per axis) — [e.g., EV3/Power Functions/WeDo]
- Pen mount made from LEGO + rubber bands (you know the vibe)
- Optional: Limit switches or touch sensors for homing

## 🧠 Software

- C++ codebase (runs on [your controller, e.g., EV3 brick / Arduino + LEGO-compatible motor driver])
- Serial input or hardcoded drawing instructions
- Simple command interpreter for linear motion (like fake G-code)

## 🗂 Project Structure

