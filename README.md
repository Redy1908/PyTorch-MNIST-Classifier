# NNDL

Repository for the Neural Networks and Deep Learning Exam Project - Master Degree Program in Computer Science - University of Naples Federico II (UNINA) 

## Requirements

- Linux operating system
- An Nvidia GPU compatible with the latest CUDA version

## Set-up (Linux)

- Update system packages:
  - `sudo apt update && sudo apt upgrade`
- Install build-essential and CUDA dependencies:
  -  `sudo apt install build-essential nvidia-cuda-toolkit`
  - If you are using WSL or other platforms install the CUDA dependencies from the official [website](https://developer.nvidia.com/cuda-toolkit)
- Create a new python virtual environment in the project direcory:
  -  `python -m venv .venv` 
- Activate the virtual environment:
  - `source .venv/bin/activate`
- Install the required packages: 
  - `pip install -r requirements.txt`, this will install the required packages
