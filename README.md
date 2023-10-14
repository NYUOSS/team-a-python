# python-template
[![CI Python](https://github.com/vchrombie/team-a-python/actions/workflows/ci-python.yml/badge.svg?branch=master)](https://github.com/vchrombie/team-a-python/actions/workflows/ci-python.yml)

This is a template repository for Python projects that provides a starting point for designing and developing Python applications. It includes a basic project structure, configuration for continuous integration, static analysis, code formatting, and more. You can use this template as a foundation for your Python projects.

## Features

- **Programming language**: [Python](https://www.python.org/)
- **Runtime environment**: [Python 3.9](https://docs.python.org/3/library/python.html)
- **Testing framework**: [pytest](https://docs.pytest.org/en/7.4.x/)
- **Continuous Integration**: [GitHub Actions](https://docs.github.com/en/actions)
- **Static analysis**: [flake8](https://github.com/PyCQA/flake8)
- **Code formatting**: [black](https://github.com/psf/black)
- **Package manager**: [Poetry](https://python-poetry.org/)
- **License**: [MIT](LICENSE)

## Getting started

1. Click the `Use this template` button to [create a new repository from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
2. Clone your new repository to your local machine.
    ```bash
    git clone https://github.com/vchrombie/python-template
    ```
3. Install the required dependencies using Poetry.
    ```bash
    poetry install
    ```
4. Activate the virtual environment using Poetry.
    ```bash
    poetry shell
    ```
5. Run tests using pytest.
    ```bash
    pytest
    ```
6. Run static analysis using flake8.
    ```bash
    flake8
    ```
7. Run code formatting using black.
    ```bash
    black .
    ```
8. Start building your project!
9. You can add the source code of your project to the `src` directory and tests to the `tests` directory.
10. Push your changes to the `master` branch of your repository to trigger a CI build on GitHub Actions.

## Team 🅰️

- Carolina Martin
- Jessie Theisen
- Sonia Susanto
- Yamini Lakshmi Narasimhan
- Venu Vardhan Reddy Tekula
