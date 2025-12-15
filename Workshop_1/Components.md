# Components

## 1. Problem Description

Modern homes increasingly incorporate automated systems that control devices such as lights, switches, and sensors. However, understanding how these systems operate internally can be complex, especially for educational purposes. There is a need for a simplified environment that allows the simulation of interactions between different domotic components in a controlled and understandable way.

The problem addressed in this project is the lack of a simple, extensible, and object-oriented simulation that models the behavior of basic home automation devices and their interactions without relying on physical hardware.


## 2. System Overview

The proposed solution is a domotic simulator that models a small home automation system. The simulator allows different components, such as switches, lights, and sensors, to interact through signals. These interactions are coordinated by a central simulation component.

The system focuses on logical behavior rather than real electrical connections. It is designed for educational purposes, allowing the study of object-oriented design principles and software architecture.

The simulator does not aim to control real devices or interact with external hardware.


## 3. Identification of Main Entities

Based on the analysis of the problem, the following main entities have been identified:

- **Component**: A generic abstraction representing any device in the system.
- **Switch**: A device capable of emitting a signal when activated or deactivated.
- **Light**: A device that reacts to signals by turning on or off.
- **Sensor**: A component that generates signals based on simulated environmental conditions.
- **Simulator**: A central entity responsible for managing the interaction between components.

These entities represent the core elements required to model the behavior of a basic domotic system.


## 4. Responsibilities of Each Entity

- **Component**: Defines the common attributes and behaviors shared by all devices in the system.
- **Switch**: Changes its internal state and produces a signal that can affect other components.
- **Light**: Receives signals and updates its state accordingly.
- **Sensor**: Simulates environmental input and generates corresponding signals.
- **Simulator**: Coordinates communication between components and ensures that signals are properly transmitted and handled.

Each entity has a clearly defined responsibility to promote modularity and maintainability.


## 5. Scope and Assumptions

The scope of this project is limited to a software-based simulation of domotic devices. The system assumes that all components communicate through logical signals managed by the simulator.

Assumptions made for this workshop include:
- The system operates in a controlled simulation environment.
- Device behavior is simplified to binary or discrete states.
- User interaction is limited to basic actions, such as activating switches or triggering sensors.

These assumptions help maintain a clear focus on object-oriented design rather than hardware-specific concerns.


## 6. Initial Class Diagram

An initial class diagram has been created to represent the main entities and their relationships at a high level. This diagram serves as a conceptual reference and will be refined in later workshops as the system design evolves.

