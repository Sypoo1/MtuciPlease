# MtuciPlease Project

This repository contains a project that consists of a frontend application and a backend application. The frontend is built using React and the backend is built using Django.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Downloading Git Submodules](#downloading-git-submodules)
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

## Running the Application

To run MtuciPlease, follow these steps:

1. Build and run the Docker containers:
docker compose up --build

The frontend application will be accessible at `http://localhost` and the backend application at `http://localhost:8000`.