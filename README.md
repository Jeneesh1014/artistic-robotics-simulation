# Artistic Robotics Simulation

This project is part of the Intelligent Robotics course at Hof University of Applied Sciences.

The goal of the project is to simulate a voice-controlled robotic drawing system using ROS2 Jazzy. The robot receives spoken commands, interprets them, and performs drawing actions inside a simulation environment.

Current implementation focuses on simple shape drawing such as:

- circle
- square
- triangle

The system is divided into multiple ROS2 nodes:

- Speech-to-text node
- Parser node
- Planner node

Each node is responsible for a specific part of the workflow and communicates through ROS2 topics.

## Project Workflow

Voice Command
→ Speech Processing
→ Command Parsing
→ Motion Planning
→ Shape Drawing

## Technologies

- ROS2 Jazzy
- Python
- Turtlesim
- ROS2 Topics and Messages

## Current Focus

The current phase of the project focuses on:

- node communication
- command parsing
- simulation testing
- modular system design

Future improvements may include:

- more complex commands
- better natural language handling
- advanced drawing logic
- intelligent motion planning

## My Contribution

I am mainly working on the parser node.

Responsibilities include:

- extracting commands from speech input
- identifying shapes and parameters
- converting text into structured drawing instructions
- testing topic communication between nodes

## Learning Goals

This project is helping us understand:

- ROS2 architecture
- distributed robotic systems
- node communication
- robotic simulation workflows
- basic natural language command processing
