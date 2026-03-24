# Autonomous Lane-Keeping System with Hybrid VLA Reasoning

A real-time autonomous driving system developed in CARLA, combining object detection, multi-object tracking, semantic scene abstraction, hybrid Vision–Language–Action reasoning, and Pure Pursuit lane control.

## Overview

This project integrates:

- YOLOv5 for object detection
- ByteTrack for multi-object tracking
- Scene state abstraction
- Hybrid VLA decision layer
- Pure Pursuit for lane-keeping
- Safety guard override for braking and traffic compliance

## System Architecture

Camera (CARLA)  
→ YOLOv5 Object Detection  
→ ByteTrack Multi-Object Tracking  
→ Scene State Representation  
→ Hybrid VLA Reasoning  
→ Pure Pursuit Lane Controller  
→ Safety Guard  
→ CARLA Vehicle Control

## Key Features

- Real-time object detection
- Multi-object tracking with stable IDs
- Lane-keeping using Pure Pursuit
- Traffic light compliance
- Obstacle-aware braking
- Hybrid semantic reasoning layer

## Project Structure

```text
.
├── vla/
├── bytetrack/
├── *.py
├── *.yaml
└── README.md
