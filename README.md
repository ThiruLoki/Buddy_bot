# Buddy Bot

## Overview

Buddy Bot: Your autonomous office robot, designed to assist and streamline indoor tasks in the workplace. It combines the power of ROS 2 with a customizable hardware platform, making it an ideal choice for robotics enthusiasts, researchers, and students. This repository contains all the necessary resources and instructions to get started with Buddy Bot.

## Features

- Differential drive system for precise control
- Modular design for easy customization
- ROS 2-based software stack
- Gazebo simulation environment included
- Support for various sensors and actuators
- Comprehensive documentation

## Prerequisites

Before using Buddy Bot, ensure that you have the following prerequisites:

- Ubuntu 20.04 or later
- ROS 2 Foxy Fitzroy or later
- Gazebo 11 or later
- Python 3.x


For detailed installation instructions, please refer to the [Installation Guide](docs/Installation.md).

## Installation

Follow these steps to set up Buddy Bot on your system:

```bash
# Clone the repository
https://github.com/ThiruLoki/buddy_bot.git

# Navigate to the project directory
cd buddy-bot

# Install ROS 2 dependencies
rosdep install --from-paths src --ignore-src -r -y

# Build the project
colcon build
