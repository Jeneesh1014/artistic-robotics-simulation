# Project Overview

The project simulates a voice-controlled robotic drawing system using ROS2 Jazzy.

The workflow is divided into three main parts:

1. Speech-to-text node
2. Parser node
3. Planner node

The speech node converts voice input into text commands.

The parser node processes those commands and extracts structured information such as:

- shape
- size

The planner node receives the structured command and controls the robot movement inside the simulation.

The current implementation focuses on basic geometric shapes:

- square
- circle
- triangle

The main goal of the project is to understand ROS2 communication, modular robotics architecture, and simulation workflows.
