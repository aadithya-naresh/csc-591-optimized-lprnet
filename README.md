# LPRNet Optimization Project

This project focuses on optimizing the LPRNet (License Plate Recognition Network) model using various techniques such as pruning, quantization, and TVM (Tensor Virtual Machine) optimization.

## Table of Contents

1. [Introduction](#introduction)
3. [Project Structure](#project-structure)
4. [Usage](#usage)
5. [Optimization Techniques](#optimization-techniques)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The LPRNet Optimization Project aims to improve the performance and efficiency of the LPRNet model for license plate recognition. We explore different optimization techniques to reduce model size, decrease inference time, and maintain accuracy.


## Project Structure

The project is organized as follows:

1. Clone GitHub Repo
2. Installation
3. Import necessary modules
4. LPRNet model loading and evaluation
5. Pruning
6. Quantization
7. TVM Baseline
8. TVM Optimization (including Autotuning, Relay Quantization, and Graph Level Transformation)
9. Testing inference speeds, model size, and accuracy

## Usage

To use this project, follow these steps:

1. Clone the LPRNet_Pytorch repository
2. Run the notebook cells in order, following the project structure
3. Upload the tuning_records.json into the lprnet_model folder after running the first block (git clone cell).

## Optimization Techniques

We apply the following optimization techniques:

1. **Pruning**: Reducing the number of parameters in the model
2. **Quantization**: Converting floating-point weights to lower-precision representations
3. **TVM Optimization**: Utilizing TVM for further performance improvements, including:
   - Autotuning
   - Relay Quantization
   - Graph Level Transformation

## Results

Our optimization efforts yielded the following improvements:

- Model size reduction: 72.60%
- Inference time reduction: 91.42%
- Accuracy change: -16.65%

These results demonstrate significant improvements in model size and inference speed, with a moderate trade-off in accuracy.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
