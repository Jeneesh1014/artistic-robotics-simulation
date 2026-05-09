# Setup Guide

## Requirements

- Ubuntu
- ROS2 Jazzy
- Python 3

## Run turtlesim

```bash
ros2 run turtlesim turtlesim_node
```

## Build workspace

```bash
colcon build
source install/setup.bash
```

## Run nodes

Run each node in a separate terminal.

Example:

```bash
ros2 run artistic_robot parser_node
```
