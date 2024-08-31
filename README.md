# POLYGLON 🌐🔄

## Overview

**POLYGLON** is a versatile library designed to bridge the gap between different programming languages by allowing you to import and utilize code from one language in another. Whether you want to use a C++ class or function in Python, POLYGLON handles different syntax and paradigms, making it easy to integrate and leverage code across over 70 programming languages. 🚀

## Features

- **Cross-Language Integration**: Import and use code from any of over 70 programming languages in your projects. 🌍
- **Syntax and Paradigm Handling**: Manage different programming languages' syntax and paradigms seamlessly. 🧩
- **Speed and Optimization**: Designed with performance and optimization in mind. ⚡
- **Portability**: Works across various platforms and environments. 🌐

## Installation

You can install POLYGLON via pip:

```bash
pip install polyglon
```

## Usage

Here’s a quick example of how to use POLYGLON to import C++ code into Python:

```python
from polyglon import lang

# Importing an external file named main.c++ with classes Add and Subtract
add, subtract = lang.LoadCpp('main.c++', (Add, Subtract))
```

In this example, `main.c++` contains two classes, `Add` and `Subtract`, which are imported into Python for use.

## Supported Languages

POLYGLON supports over 70 different programming languages. For a full list of supported languages, please refer to the [Documentation](DOCUMENTATION.md).

## Contributing

We welcome contributions to POLYGLON! To contribute:

1. **Fork the Repository**: Create your own copy of the repository on GitHub. 🍴
   
2. **Create a Branch**: Make a new branch for your feature or bug fix. 🌿
   
3. **Make Changes**: Implement your changes in your branch. ✍️
   
4. **Submit a Pull Request**: Open a pull request with a description of your changes. 🚀

Please refer to our [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE). 📝

## Contact

For support or questions, please reach out to us at [your-email@example.com]. 📧
