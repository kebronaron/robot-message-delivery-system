# Robot Message Delivery System

## Project Overview

The Robot Message Delivery System is a team software engineering project designed to connect a web application, backend services, cloud infrastructure, and a robotic delivery system.

**Purpose:** Enable users to create and manage delivery messages through a web interface, with the goal of supporting delivery operations through a ROS 2-based robot.

**Intended audience:** Software developers joining the project who need to understand its main technologies, components, and integration goals.

## Technology Stack

| Component | Technology | Role |
|---|---|---|
| Frontend | React, TypeScript | User interface for creating and managing delivery messages |
| Backend | Python, Flask | REST API communication and application logic |
| Database | PostgreSQL | Relational data storage |
| Cloud infrastructure | AWS | Cloud services supporting the application's architecture |
| Robotics | ROS 2 | Intended integration with the robotic delivery system |

## System Architecture

The proposed architecture includes the following components:

1. **Frontend:** A React and TypeScript application provides the user interface for delivery-message management.
2. **Backend:** A Flask-based REST API connects frontend requests to backend application logic.
3. **Database:** PostgreSQL supports relational data storage for the application.
4. **Cloud infrastructure:** AWS provides the cloud environment for supporting application services.
5. **Robotic system:** ROS 2 is the framework identified for integrating the application with the robot.

### Conceptual Data Flow

User → React/TypeScript Frontend → Flask REST API → PostgreSQL Database

Cloud infrastructure supports the application, while ROS 2 integration is part of the overall system design.

*Note: This is a conceptual overview, not a verified description of every deployed service or communication path.*

## Implementation Details Requiring Verification

Before a new developer can independently set up or extend the application, the team should confirm and document the following:

- Which frontend, backend, and robotics components are currently operational.
- Which AWS services are actively deployed and how they connect.
- Whether communication between the backend and ROS 2 system has been implemented.
- The available REST API endpoints and their request and response formats.
- The required development environment, dependencies, and local setup commands.

These details are intentionally marked as unverified rather than presented as completed functionality.

## Guidance for New Contributors

New contributors should begin by reviewing the project architecture and identifying the component they will work on. They should confirm the current implementation status with the team before making changes to application interfaces or integration points.

Once the team verifies the setup instructions, API contracts, and deployment configuration, those details should be added to this README to make onboarding more independent.
