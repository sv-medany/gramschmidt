# Gram-Schmidt Procedure for Signal Orthogonalization

This code demonstrates the implementation of the Gram-Schmidt procedure for signal orthogonalization. It takes two rectangular pulse input signals and applies the Gram-Schmidt process to obtain a set of orthogonal basis functions.

## Code Overview

The provided code performs the following steps:

1. Defines the time vector and input signals: Two rectangular pulse signals, `rect1` and `rect2`, are defined as the input signals. These signals are combined into a matrix `A`.

2. Applies the Gram-Schmidt procedure: The code initializes the basis functions matrix `basis_funcs` and calculates the first basis function by normalizing `rect1` using its energy. It then iteratively calculates the remaining basis functions by projecting each input signal onto the previous basis functions and obtaining the orthogonal complement. The basis functions are normalized using the energy of the orthogonal complement.

3. Plots the sample space: The code plots the input signals in the sample space, displaying how they relate to each other.

4. Plots the original signals: The code plots each original input signal separately to visualize its amplitude variation over time.

5. Plots the basis functions: The code plots each basis function separately, showcasing their orthogonality and amplitude variation over time.

## Prerequisites

To run this code, you need the following:

- MATLAB or Octave installed on your machine.

## Usage

1. Open MATLAB or Octave.

2. Copy the provided code into the MATLAB/Octave editor.

3. Run the code.

4. Observe the generated plots to visualize the sample space, original signals, and basis functions.

## Contributing

Contributions to this project are welcome! If you have any ideas or improvements, feel free to submit a pull request. Make sure to follow the existing code style and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

