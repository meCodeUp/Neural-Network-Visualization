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

## DISCLAIMER

This software is an experimental code developed solely for demonstration purposes and to visualize the basic functioning of a neural network.

## Please note:

1. No Guarantee of Accuracy: The values, calculations, and results presented in this software do not claim to be accurate or precise. They serve only to illustrate the concept of a neural network.

2. Experimental Nature: This code is experimental and not suitable for production use or scientific purposes. It may contain errors, inaccuracies, or simplified representations.

3. Visualization Purpose: The primary purpose of this software is to visually represent the structure and basic functionality of a neural network. It is not designed to perform precise or reliable calculations.

4. No Liability: The developers and providers of this software assume no liability for any damages or consequences that may arise from the use or misinterpretation of the information presented.

5. Educational Purpose: This software is intended as a learning and teaching tool to provide a basic understanding of neural networks. It does not replace expert knowledge or professional implementations.

6. Simplified Model: The neural network model presented here is greatly simplified and may not accurately represent the complexity and capabilities of advanced neural network architectures used in real-world applications.

7. Not for Decision Making: The outputs and results from this software should not be used for any decision-making processes or as a basis for any kind of analysis or conclusion.

8. Continuous Development: This software is subject to change and may be updated or modified without notice. The current version may not reflect the most recent developments in neural network theory or practice.

By using this software, you agree to this disclaimer and acknowledge that the information and calculations presented may not reflect reality or the current state of the art in the field of neural networks.


