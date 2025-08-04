# SB3-SAI-RL-Docker-Template

A Docker-based template for training reinforcement learning (RL) models using [Stable-Baselines3](https://stable-baselines3.readthedocs.io/en/master/index.html) (SB3) and [SAI platform](https://competesai.com/) by ArenaX Labs. This repository provides a containerized environment that facilitates easy setup and deployment of reinforcement learning experiments with minimal configuration.

## Introduction

This repository offers a template for building RL training environments using SB3 and Sai-rl platform, packaged inside a Docker container. It aims to simplify the setup process, making it easier to start RL experiments without worrying about dependencies or environment management.

SB3 is a popular library for training RL models, while the SAI platform provides a collection of environments based on the Gymnasium standard.

## Installation

### Prerequisites

- **Docker**: You must have Docker installed on your machine. Follow the installation instructions on the [official Docker website](https://docs.docker.com/get-docker/).

- **Git**: Ensure that you have Git installed for cloning the repository. [Download Git here](https://git-scm.com/downloads).

- **Python 3.6+**: Docker images typically come with a Python environment, but it's useful to have Python installed locally if needed for certain commands.

### Setup Instructions

Clone this repository:

```bash
git clone https://github.com/Saad135/sb3-sai-rl-docker-template.git

cd sb3-sai-rl-docker-template
```

### Dev containers

If you are using VSCode and have the devcontainers extension installed, VSCode should automatically detect the `.devcontainer` configuration if it's present. To reopen the folder in the devcontainer, follow these steps:

1.  In the **VSCode** window, press `Ctrl + Shift + P` to open the Command Palette.
2.  Search for and select **Dev Containers: Reopen in Container**.

VSCode will:

- Build the Docker container (if it's not built already).
- Open the project in a new window with the environment defined in the container.

> **Note**: The first time it may take a few minutes to build the Docker image and set up the environment.

### Docker Compose

To build and run the docker image using docker compose, run `docker compose up`.

### Pre-built image

If you are looking for an already built image, you can download the image for this docker-hub repo: https://hub.docker.com/r/saad1998/franka-golf-saad
