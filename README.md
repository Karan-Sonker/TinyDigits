# Handwritten Digit Recognition on Microcontrollers

## Overview

This project implements a handwritten digit recognition system designed to run on microcontrollers. The goal is to recognize digits from images using a lightweight neural network model optimized for embedded systems.

## Features

- **Lightweight Model**: The neural network model is optimized for low memory and processing power, making it suitable for microcontroller applications.
- **Real-Time Recognition**: Capable of recognizing handwritten digits in real-time.
- **Cross-Platform Compatibility**: Designed to work with various microcontroller platforms.

## Getting Started

### Prerequisites

- Microcontroller (e.g., Arduino, Raspberry Pi Pico)
- Development environment set up for your microcontroller
- Python (for model training and testing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/karanSonker/TinyDigits.git
2. Navigate to the project directory:
   ```bash
    cd TinyDigits
    pip install -r requirements.txt


## Usage
Training the Model:
Use the provided scripts to train the model on a dataset of handwritten digits (e.g., MNIST).
Adjust parameters in the configuration file as needed.

Deploying on Microcontroller:
Compile the model for your specific microcontroller.
Upload the firmware to the microcontroller using your development environment.

Testing:
Use the provided test scripts to evaluate the model's performance.
Input images can be taken from a camera or uploaded from a computer.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.


Feel free to modify any sections to better fit your project's specifics!


