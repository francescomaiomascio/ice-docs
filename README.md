# ICE Studio Documentation

[![Docs](https://img.shields.io/badge/docs-live-8FB9FF?style=flat)](https://francescomaiomascio.github.io/ICE-Studio-Docs/)
[![Status](https://img.shields.io/badge/status-active-111827?style=flat)](https://github.com/francescomaiomascio/ICE-Studio-Docs)
[![License](https://img.shields.io/badge/license-proprietary-6B7280?style=flat)](#)
[![Sponsor](https://img.shields.io/badge/support-GitHub%20Sponsors-7A7CFF?style=flat)](https://github.com/sponsors/francescomaiomascio)


**ICE Studio** is an **Integrated Cognitive Environment**  
for system-level software development.

It is not an IDE.  
It is not an AI tool.  
It is not a plugin-based editor.

**It defines a new category of system.**

---

## 📘 Documentation

👉 **Read the official ICE Studio documentation:**  
https://francescomaiomascio.github.io/ICE-Studio-Docs/

This site is the **canonical reference** for understanding ICE Studio:
its architecture, runtime model, cognitive principles, and design philosophy.

---

## 🔒 Source Code

The ICE Studio engine and core implementation are **intentionally not open source**.

This repository hosts **documentation only**.

Private source repository:  
https://github.com/francescomaiomascio/ICE-Studio

---

## What ICE Studio Is

ICE Studio is the reference implementation of **ICE Engine** —  
a cognitive runtime designed to orchestrate intelligence across:

- code
- knowledge
- agents
- runtime
- interfaces

ICE Studio does **not extend an IDE**.  
It replaces the IDE abstraction entirely.

### ICE Studio is not:
- an IDE
- a chatbot
- a plugin ecosystem
- an LLM wrapper

### It is closer to:
- a browser engine (e.g. Chromium)
- a game engine for cognition
- an operating runtime for knowledge-driven systems

---

## ICE Engine (The Core)

**ICE Engine** is the underlying runtime that powers ICE Studio.

ICE Engine does not “think”.  
**ICE Engine orchestrates thinking.**

It coordinates:

- cognitive agents
- local and remote LLM models
- structured knowledge layers
- lifecycle phases and transitions
- system-wide observability
- human–system interaction
- modular interfaces and protocols

The engine exists independently from any single project or UI.

---

## Architecture Overview

ICE Studio is built around **cognitive phases**, not screens.

### Preboot Phase

A deterministic bootstrap phase responsible for:

- environment verification
- capability discovery
- runtime topology (local / remote)
- system identity initialization
- minimal cognitive context creation

Preboot is not a setup wizard.  
**It is a cognitive bootstrap phase.**

---

### Dashboard Phase

The Dashboard represents the **global cognitive environment**.

It provides:

- system-wide awareness
- access to Global Knowledge
- orchestration across projects
- runtime diagnostics and logs

Dashboard ≠ workspace  
Dashboard is the system observing itself.

---

### Project Phase

A project is a **living cognitive entity**.

Each project has:

- its own knowledge
- history and timeline
- dedicated agents
- contextual objectives

Projects plug into a living system — they do not recreate it.

---

## Knowledge System (Three Layers)

ICE Studio enforces strict separation between knowledge layers.

### Global Knowledge
System-level knowledge about architecture, capabilities, protocols, and runtime state.

Used by:
- System Agent
- orchestrators
- decision engines

Does not contain user or project data.

---

### User Knowledge
Represents long-term patterns, preferences, and behavior.

Built through observation, not prompts.  
Local, private, and isolated.

---

### Project Knowledge
Project-specific context:
- code
- documents
- decisions
- objectives
- evolution timeline

This separation prevents contamination and enables targeted reasoning.

---

## Backend (Python Runtime)

The backend is the **cognitive engine**.

It is responsible for:

- agent orchestration
- knowledge routing
- lifecycle control
- logging, audit, and tracing
- model integration

This is not a simple API server.

Agents are **not chatbots** —  
they are specialized cognitive processes with single responsibilities.

---

## GUI Philosophy

**The GUI is a surface, not the core.**

It:
- renders state
- collects input
- mounts and unmounts phases

It does not:
- store knowledge
- make decisions
- perform reasoning

Preboot, Dashboard, and Project phases never coexist in the same runtime.

---

## Logging (Non-Negotiable Rule)

ICE Studio enforces **centralized, event-based logging**.

Direct file writes are forbidden.

All logs must:
- emit events via `ice_studio.logging.api`
- be routed through the logging runtime
- remain observable and auditable

---

## Extensibility & Protocols

ICE Studio supports:

- agent plugins
- UI plugins
- knowledge plugins
- distributed runtimes

Internal protocols (ICEP / ICENet) enable:
- runtime discovery
- remote coordination
- cognitive coherence across nodes

---

## Support the Project

If you believe in the vision behind ICE Studio and want to support its development:

<a href="https://www.buymeacoffee.com/francescomaiomascio" target="_blank">
  <img
    src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png"
    alt="Buy Me A Coffee"
    style="height: 60px !important; width: 217px !important;"
  />
</a>


Your support helps sustain long-term research,
system design, and the evolution of ICE Studio.

---

**ICE Studio is not an IDE.**  
**It is what comes after.**
