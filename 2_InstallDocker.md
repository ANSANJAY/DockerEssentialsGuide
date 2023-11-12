Based on your class notes about installing and getting started with Docker, I will create a structured revision guide for your interview preparation:

### Title: Docker Installation and Usage Guide

1. **The Technical Concept**
   - **Docker Overview**: Docker is a platform for developing, shipping, and running applications in isolated environments called containers.
   - **System Requirements**: For Docker installation, a 64-bit Ubuntu system (Bionic, Cosmic, or Xenial version) is required.
   - **Installation Process**:
     - Check for older Docker versions and uninstall if necessary.
     - Set up the Docker repository.
     - There are two installation methods:
       1. Using package manager with `apt-get`.
       2. Using Docker's convenient script for automated installation.
   - **Post-Installation**:
     - Verify Docker installation with `docker version`.
     - Run a test container, such as Whalesay, to ensure proper setup.

2. **Curious Questions**
   - **Q1**: How do you check if your system has an older version of Docker installed?
     - **A1**: Use the command `dpkg -l | grep -i docker` to list any Docker packages installed.
   - **Q2**: What are the steps to install Docker using the package manager method?
     - **A2**: Update the repository using `apt-get`, install prerequisite packages, add Docker's official GPG keys, and then install Docker.
   - **Q3**: What is the purpose of the Whalesay container?
     - **A3**: Whalesay is a fun Docker image used for demonstration purposes, showing a whale displaying a message.

3. **Simple Explanation**
   - Docker allows you to run applications in containers, which are like lightweight, portable, and self-sufficient environments.
   - To install Docker on Ubuntu, you first ensure your system doesn't have an older version, then choose between two installation methods: using the package manager or a convenient script.
   - After installation, you can test Docker by running the Whalesay container, which simply displays a message in a fun way.

This structured guide should help you revise the Docker installation process effectively for your interviews. Good luck!