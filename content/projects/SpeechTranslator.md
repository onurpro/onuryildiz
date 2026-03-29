---
title: "Distributed Speech-to-Speech Translator"
date: 2025-12-01
draft: false
description: "A real-time speech translator running across three embedded Linux nodes, orchestrated over a custom TCP/IP protocol."
weight: 4
---

**Role:** Developer
**Course:** Academic Project — Sep 2025 to Dec 2025

## Project Overview

A distributed, real-time speech-to-speech translation system running across **three specialized AI inference nodes** on embedded Linux hardware, orchestrated over a custom network protocol.

## Technical Highlights

### Custom Network Protocol
Engineered a **C-based TCP/IP network protocol** using a Hub-and-Spoke topology to orchestrate asynchronous data flow between the three inference nodes.

### Cross-Compilation Monorepo
Architected a unified **monorepo using CMake Presets** to manage cross-compilation from x86 host to ARM64 target for **four distinct C/C++ binaries**, resolving conflicting embedded dependencies.

### LLM Memory Management
Eliminated critical LLM memory corruption and hallucination issues on the **BeagleBone AI (Cortex-A53)** by implementing stateless context management and systematically resetting the KV cache per request.

### System-Level Integration
Utilized C/C++ on the embedded environment to implement:
- **ALSA** audio interfacing for real-time microphone input and speaker output
- A **multi-threaded Text User Interface** built with ncurses

## Key Learnings

This project deepened my understanding of embedded Linux development, cross-compilation toolchains, real-time networking, and the challenges of running AI inference on resource-constrained hardware.
