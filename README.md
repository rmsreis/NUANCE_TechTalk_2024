# NUANCE Tech Talk 2024 - Electron Microscopy Data Analysis Crash Course
Python codes for EM analysis presented at NUANCE Tech Talk on May 16, 2024

## Introduction
This crash course provides a series of Jupyter notebooks designed to introduce techniques for analyzing electron microscopy data using Python. The course covers various dataset dimensions from simple 2D images to complex 5D datasets.

## Prerequisites
Before starting, ensure you have installed the following software:
- **Anaconda**: A free and open-source distribution of Python and R for scientific computing, which simplifies package management and deployment.
- **Git**: A version control system used to manage the source code.

## Installation Instructions

### Installing Anaconda
Anaconda simplifies package management and deployment for Python/R and is recommended for this course to manage environments and dependencies efficiently.

1. **Download Anaconda**:
   - Visit the [Anaconda Distribution page](https://www.anaconda.com/products/individual) and download the installer for your operating system.

2. **Install Anaconda**:
   - **Windows**:
     - Run the downloaded installer.
     - Choose the install location and ensure that “Add Anaconda to my PATH environment variable” is checked.
     - Complete the installation and restart your computer if required.
   - **macOS**:
     - Open the downloaded `.pkg` file and follow the instructions.
     - Ensure that the installer is allowed to install in the desired directory (administrator privileges may be required).
   - **Linux**:
     - Open a terminal and navigate to the directory containing the downloaded script.
     - Run the script with `bash Anaconda3-xxxx.xx-Linux-x86_64.sh` (replace `xxxx.xx` with the version number).
     - Follow the on-screen instructions during the installation.

### Cloning the Repository with Git
To download the course materials, you will need to clone the repository using Git.

1. **Install Git** (if not already installed):
   - **Windows/Linux/macOS**: Download from [Git SCM](https://git-scm.com/downloads) and follow the installation guide for your OS.

2. **Clone the Repository**:
   - Open a terminal or command prompt.
   - Navigate to the directory where you want to store the course materials.
   - Run the following command:
   ```bash
   git clone https://github.com/rmsreis/NUANCE_TechTalk_2024.git
