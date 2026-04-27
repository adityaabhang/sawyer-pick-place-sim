# Sawyer Pick-and-Place Simulator

A CoppeliaSim-based robotic pick-and-place simulation using a Sawyer robot to pick and place cuboid objects by color.

## Overview

This project implements an pick-and-place task where a Sawyer robot:
- Known cordinates 6 cuboid objects (2 blue, 2 green, 2 red)
- Picks each object from the workspace platform
- Places objects into color-matched bins 
- Uses inverse kinematics for motion planning

## Demo

<video width="100%" controls>
  <source src="sawyer-pick-place-sim.mp4" type="video/mp4">
</video>

## Project Structure

```
├── README.md
├── sawyer-pick-place-sim.ttt          # CoppeliaSim scene file
└── sawyer-pick-place-sim.mp4          # Simulation execution video
```

## Requirements

### Software
- **CoppeliaSim** (v4.10) 

## Quick Setup

### 1. Load the Scene
1. Open CoppeliaSim
2. File → Open → `sawyer-pick-place-sim.ttt`
3. Scene loads with:
   - Sawyer 7-DOF robotic arm
   - 6 cuboid objects (2 each: blue, green, red)
   - 3 colored bins for sorting
   - Workspace platform

### 2. Run the Simulation
1. Locate the script associated with the Sawyer robot in the Scene tree (left panel)
2. Click **Play** (▶) to start simulation
3. Robot executes pick-and-place sequence automatically

## References

- [CoppeliaSim Documentation](https://www.coppeliarobotics.com/helpFiles/)
- [Sawyer Robot Specifications](https://en.wikipedia.org/wiki/Sawyer_(robot))

