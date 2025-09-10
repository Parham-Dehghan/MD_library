# Contributing to MDQuantumLite2

Thank you for your interest in contributing to **MDQuantumLite2**! We welcome contributions from the community to help improve this lightweight Python library for quantum-inspired molecular dynamics simulations. Whether you're fixing bugs, adding features, or improving documentation, your efforts are greatly appreciated.

## How to Contribute

### 1. Getting Started
- **Fork the Repository**: Click the "Fork" button on the [MDQuantumLite2 GitHub repository](https://github.com/Parham-Dehghan/MD_library) to create a copy under your GitHub account.
- **Clone Your Fork**: Clone your forked repository to your local machine:
  ```bash
  git clone https://github.com/YOUR-USERNAME/MD_library.git
  ```
- **Install Dependencies**: Ensure you have Python 3.8+ and the required dependencies installed:
  ```bash
  pip install numpy scipy
  pip install mdquantumlite2==0.1.0
  ```

### 2. Development Workflow
- **Create a Branch**: Create a new branch for your changes:
  ```bash
  git checkout -b feature/your-feature-name
  ```
  Use descriptive branch names (e.g., `fix/bug-123`, `feature/add-new-algorithm`).
- **Make Changes**: Implement your changes, ensuring code quality and adherence to the project's coding standards (see below).
- **Test Your Changes**: Test your code locally to ensure it works as expected. Add or update tests if applicable.
- **Commit Changes**: Write clear, concise commit messages:
  ```bash
  git commit -m "Add feature: describe your change here"
  ```
- **Push to Your Fork**: Push your branch to your forked repository:
  ```bash
  git push origin feature/your-feature-name
  ```
- **Open a Pull Request**: Go to the [MDQuantumLite2 repository](https://github.com/Parham-Dehghan/MD_library) and open a Pull Request (PR) from your branch. Provide a detailed description of your changes in the PR.

### 3. Coding Standards
- **Python Style**: Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) guidelines for Python code.
- **Documentation**: Update docstrings and relevant documentation for any new or modified code.
- **Testing**: Ensure new features or bug fixes include appropriate unit tests. Use `unittest` or `pytest` for testing.
- **Performance**: Optimize code for efficiency, as MDQuantumLite2 prioritizes lightweight and fast simulations.
- **Compatibility**: Ensure code is compatible with Python 3.8+ and dependencies (NumPy >= 1.20, SciPy >= 1.7).

### 4. Types of Contributions
We welcome the following contributions:
- **Bug Fixes**: Address issues reported in the [Issues](https://github.com/Parham-Dehghan/MD_library/issues) section.
- **New Features**: Propose and implement new functionality (discuss in an issue first).
- **Documentation**: Improve README, wiki, or inline documentation.
- **Performance Improvements**: Optimize algorithms or reduce computational overhead.
- **Tests**: Add or improve unit tests to increase code coverage.

### 5. Reporting Issues
If you encounter bugs or have feature requests:
- Check the [Issues](https://github.com/Parham-Dehghan/MD_library/issues) page to avoid duplicates.
- Open a new issue with a clear title and description, including:
  - Steps to reproduce the issue (if applicable).
  - Expected behavior vs. actual behavior.
  - Environment details (Python version, OS, etc.).

### 6. Pull Request Guidelines
- **Reference Issues**: Link your PR to relevant issues (e.g., "Fixes #123").
- **Clear Description**: Explain what your PR does, why it’s needed, and how it was tested.
- **Keep It Focused**: Address one feature or bug per PR for easier review.
- **Follow Template**: Use the PR template (if provided) in the repository.
- **Be Responsive**: Address feedback from maintainers promptly.

### 7. Code of Conduct
We are committed to fostering a welcoming and inclusive community. All contributors are expected to adhere to the [Code of Conduct](CODE_OF_CONDUCT.md). Please be respectful and professional in all interactions.

### 8. Getting Help
- **Questions**: Post questions in the [Issues](https://github.com/Parham-Dehghan/MD_library/issues) section or join discussions in the repository.
- **Contact**: For urgent matters, reach out via the repository’s contact details.

## License
By contributing to MDQuantumLite2, you agree that your contributions will be licensed under the [MIT License](LICENSE).

## Acknowledgments
Thank you for helping make MDQuantumLite2 better! Your contributions drive the advancement of quantum-inspired molecular dynamics simulations.

Happy coding! 🚀