---
title: "SubVision ROV"
date: 2024-10-01
draft: false
description: "Leading the electronics and system architecture for an underwater ROV at a student-led robotics startup."
weight: 5
---

**Role:** Project Lead & Electronics Lead
**Status:** In Progress

## Project Overview

SubVision Robotics is a student-led startup developing an underwater Remotely Operated Vehicle (ROV) prototype for a first funding round. As Project Lead and Electronics Lead, I am responsible for the planning and architectural design of the ROV's hardware and electronic systems.

## System Architecture

I architected a system using an onboard **Raspberry Pi 4** to bridge a surface computer with a custom sensor board, enabling the surface computer to run **SLAM algorithms** for underwater navigation and mapping.

### Sensor Board

The sensor board is designed around an **STM32 microcontroller** running a **Real-Time Operating System (RTOS)** to ensure correctly timed data collection from:

- **IMU** — Inertial measurement for orientation and motion tracking
- **GPS** — Surface-level positioning
- **Optical Flow Sensors** — Visual motion estimation underwater

### Power System

I engineered the power system incorporating a **12V surface battery** and a **DC-DC converter**, and managed electrical designs for UVC light implementation and watertight enclosure penetrators.

## Key Responsibilities

- Leading overall project planning and architectural design
- Designing the full hardware and electronic system stack
- Bridging embedded compute (RPi4 + STM32) with surface-level algorithms
- Managing electrical integration for sensors, power, and enclosure systems
