# Articulated Aquatic Simulation (& machine learning)

This project is a **2D physics simulation** of an articulated structure (like an aquatic creature) built using **Pygame**. It features points connected by "limbs" (rigid springs) and animated through joint control. Movement is generated via periodic angular forces applied to the joints.

## Purpose

Simulate the dynamic behavior of an articulated organism in a simplified environment. Ultimately, the goal of this foundation will support **machine learning experiments** (not yet implemented), where the IA will learn how to control the creatures.

## Features

- Real-time simulation with Pygame
- Points connected by elastic limbs with configurable stiffness
- Animated joints with cyclic target angles
- Camera that dynamically centers on the creature
- Visual grid to better observe motion and positioning
- 1st & 2nd law of Newton implemented for realistic physics

## Controls

- **Enter**: Start / Pause the simulation  
- **C**: Exit the simulation

## Dependencies

- `pygame`
- `numpy`

Install them via:

```bash
pip3 install pygame numpy
