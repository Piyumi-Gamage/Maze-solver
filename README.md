# Maze Solver Robot 🤖🧩

## Overview
A simple autonomous Maze Solver Robot designed to navigate through a maze using **ultrasonic sensors** and **decision-making algorithms**.  
The robot detects walls and decides whether to turn left, right, or move forward to reach the goal efficiently.

This project helped me explore concepts like sensor integration, real-time decision making, and obstacle detection in robotics.

## Features
- a maze-solving robot by integrating Arduino Uno, buck converter, motor drivers, and ultrasonic sensors.
- Wall-following and decision-based path finding (D controllers for smooth and accurate movement control.)
- Depth-First Search (DFS) algorithm for systematic maze navigation.

## How It Works
- The robot continuously reads distance values from sensors.
- Based on wall presence (left, right, front), it decides the next move.
- It follows a basic wall-following algorithm and depth-fist algorithm to escape the maze.

## Hardware Requirements
- Microcontroller (Arduino Uno)
- Ultrasonic Sensors
- Motor Driver
- Buck convertor
- DC Motors with wheels
- Chassis
- Power supply (Battery)

## Software Requirements
- Arduino IDE / PlatformIO
- C/C++ Programming
