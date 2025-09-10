# MDQuantumLite2

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![PyPI](https://img.shields.io/pypi/v/mdquantumlite2)

**MDQuantumLite2** is a lightweight and efficient Python library designed for performing molecular dynamics simulations with quantum mechanical insights. It provides tools for researchers and developers to model and analyze molecular systems with ease, leveraging optimized algorithms for performance.

## Features

- **Quantum-Inspired Simulations**: Incorporate quantum mechanical principles into molecular dynamics simulations.
- **Lightweight and Fast**: Optimized for performance with minimal dependencies.
- **Flexible Configuration**: Easily define molecular systems, force fields, and simulation parameters.
- **Extensible**: Modular design allows for easy integration with other scientific computing libraries.
- **Cross-Platform**: Compatible with Python 3.8+ on Windows, macOS, and Linux.

## Installation

You can install `mdquantumlite2` directly from PyPI using pip:

```bash
pip install mdquantumlite2==0.1.0
```

## Quick Start

Here's a simple example to get you started with `mdquantumlite2`:

```python
from mdquantumlite2 import MDSimulation

# Define a simple molecular system
system = MDSimulation(
    molecules=["H2O", "H2O"],
    box_size=[10.0, 10.0, 10.0]
)

# Configure simulation parameters
system.set_parameters(
    temperature=298.0,  # Kelvin
    time_step=1.0,      # Femtoseconds
    total_steps=1000
)

# Run the simulation
system.run()

# Analyze results
results = system.get_trajectory()
print(results)
```

## Documentation

For detailed documentation, including API references and advanced usage examples, visit the [official documentation](https://github.com/Parham-Dehghan/MD_library/wiki) (coming soon).

## Requirements

- Python 3.8 or higher
- NumPy >= 1.20
- SciPy >= 1.7

Install dependencies using:

```bash
pip install numpy scipy
```

## Contributing

Contributions are welcome! To contribute to `mdquantumlite2`:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, bug reports, or feature requests, please open an issue on the [GitHub repository](https://github.com/Parham-Dehghan/MD_library/issues).

Follow the project on GitHub for updates: [MDQuantumLite2 Repository](https://github.com/Parham-Dehghan/MD_library)

---

Happy simulating! 🚀