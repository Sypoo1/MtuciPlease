# MtuciPlease Project

This repository contains a project that consists of a frontend application and a backend application. The frontend is built using React and the backend is built using Django.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Downloading Git Submodules](#downloading-git-submodules)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Docker and Docker Compose. If not, you can download them [here](https://www.docker.com/products/docker-desktop).
- You have a Linux machine. This guide is tailored for Linux environments.

## Installation

To install MtuciPlease, follow these steps:

1. Clone the repository:
git clone https://github.com/Sypoo1/MtuciPlease.git

2. Navigate to the project directory:
cd MtuciPlease

## Downloading Git Submodules

This project uses git submodules. To download the submodules, run the following command:

git submodule update --init --recursive

## Environment Variables

The backend application uses environment variables for configuration. These are stored in a `.env` file in the `MTUCI_please_backend` directory.

To create the `.env` file, navigate to the `MTUCI_please_backend` directory and create a new file named `.env`. Then, add your environment variables in this file.

Here's what each variable is for:

- `DEBUG`: A boolean that turns on/off debug mode in Django. For production, this should always be `False`.
- `SECRET_KEY`: A secret key for a particular Django installation. This should be set to a unique, unpredictable value.

Please make sure to update these environment variables according to your setup before running the application.

## Running the Application

To run MtuciPlease, follow these steps:

1. Build and run the Docker containers:
docker compose up --build

The frontend application will be accessible at `http://localhost` and the backend application at `http://localhost:8000`.