# Neural Network Visualization

This project provides an interactive visualization of a simple neural network, demonstrating the training process and how the network learns to map inputs to outputs.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Features

- Visual representation of a 3-layer neural network (input, hidden, output)
- Real-time visualization of neuron activations and weight adjustments
- Interactive controls for starting, stopping, and adjusting training speed
- Step-by-step explanation of the network's operations
- Customizable training examples and network parameters

## Installation

1. Clone the repository:

2. Navigate to the project directory:

3. Open the `index.html` file in a modern web browser.

No additional dependencies or installation steps are required as this is a pure HTML/JavaScript implementation.

## Usage

1. Open the `index.html` file in a web browser.
2. Click the "Start Training" button to begin the training process.
3. Use the speed dropdown to adjust the training speed between "Slow" and "Fast".
4. Click the "Stop Training" button to pause the training at any time.
5. Use the "Show Info" button to toggle an explanations of each training step.

## How It Works

The visualization demonstrates a simple feedforward neural network with backpropagation:

1. **Forward Propagation**: Input values are processed through the network layers.
2. **Activation**: Neuron activations are calculated using the sigmoid function.
3. **Error Calculation**: The difference between expected and actual outputs is computed.
4. **Backpropagation**: Errors are propagated backwards to adjust weights.
5. **Visualization**: The process is visually represented on an HTML canvas.

The network trains on a set of predefined examples, attempting to minimize the difference between its outputs and the expected results.

## Contributing

Contributions to improve the visualization or extend its capabilities are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch 
3. Commit your changes 
4. Push to the branch 
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` file for more information.

