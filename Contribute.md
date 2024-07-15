# Contributing to PyGrid

First off, thank you for considering contributing to PyGrid! Your help is greatly appreciated. This guide will help you understand how you can contribute to the project.

## How Can I Contribute?

### Reporting Bugs

If you find a bug, please report it by opening an issue on the [GitHub issues page](https://github.com/Lincoln-developer/PyGrid/issues). Include as much detail as possible to help us understand and reproduce the issue. 

### Suggesting Enhancements

If you have an idea for an enhancement or a new feature, please open an issue on the [GitHub issues page](https://github.com/Lincoln-developer/PyGrid/issues). Clearly describe your idea and why you think it would be beneficial for PyGrid.

### Contributing Code

1. **Fork the Repository**: Click the "Fork" button at the top of the repository page to create your own fork of the project.
2. **Clone Your Fork**: Clone your fork to your local machine using:
    ```bash
    git clone https://github.com/Lincoln-developer/PyGrid.git
    cd pygrid
    ```
3. **Create a Branch**: Create a new branch for your work:
    ```bash
    git checkout -b feature/your-feature-name
    ```
4. **Make Your Changes**: Make your changes to the codebase.
5. **Commit Your Changes**: Commit your changes with a meaningful commit message:
    ```bash
    git add .
    git commit -m "Add feature: your-feature-name"
    ```
6. **Push to Your Fork**: Push your changes to your forked repository:
    ```bash
    git push origin feature/your-feature-name
    ```
7. **Submit a Pull Request**: Go to the original repository and create a pull request from your fork. Provide a clear description of your changes and why they should be merged.

### Writing Tests

Adding tests is a great way to ensure the code is reliable and maintainable. Please include tests for any new features or bug fixes. We use [pytest](https://pytest.org/) for our testing framework. To run the tests, use:

```bash
pytest
