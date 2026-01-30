# Devops-task-10
# Task 10: Docker Volumes & Networking

## Objective
To understand Docker data persistence using volumes and container-to-container
communication using custom Docker networks.

## Tools Used
- Docker
- Linux (WSL)

## Architecture
Two containers are connected using a custom bridge network.
A Docker volume is mounted to persist application data even after
container removal.

## Volume Configuration
- Docker volume created using CLI
- Volume mounted inside container
- Data stored inside volume directory

## Network Configuration
- Custom Docker bridge network created
- Containers attached to same network
- Communication verified using container names

## Data Persistence Proof
1. Data written inside mounted volume
2. Container removed
3. Container recreated with same volume
4. Data verified as persistent

## Deliverables
- Volume and network configuration
- Screenshots of volume and network inspection
- Data persistence proof screenshots

## Final Outcome
Clear understanding of Docker volumes, networks,
and container data persistence.
