---
title: Wordguess
category: project
format: notes
feed: show
date: 2026-01-01
---
<!-- markdownlint-disable MD059 -->

[Wordguess](https://ubc-mds.github.io/wordguess/) is a [pyOpenSci](https://www.pyopensci.org/) package with essential functions for a word-guessing game, inspired by [Wordle](https://www.nytimes.com/games/wordle/index.html).

The `wordguess` package is designed for developers to create guessing games. The package provides functionality for word validation, feedback generation, and corpus management. It can compare user guesses to the target word and provide feedback on the accuracy of the guesses in terms of correct letters and their positions, including numerical and human-readable expressions. Additionally, features for scoring and hinting are included to enhance development of word-guessing games. `wordguess` provides the back-end foundation needed to handle the underlying string comparisons and state tracking.

`wordguess` fits perfectly into the Python ecosystem by offering a simple foundation for word-based projects. It uses standard Python practices, making it a great tool for learning to code or for developers who want to quickly add logic to their game ideas. Because the package emphasizes clean type-hinting and standardized docstrings, it serves as an excellent resource for developers learning about string manipulation, algorithmic logic, and package distribution. It bridges the gap between simple script-based games and production-ready modular code.

To install the package, run the following command:

    ```bash
    pip install -i https://test.pypi.org/simple/ wordguess
    ```

The analysis was built on top of these key dependencies:

    - Continuous integration/development: GitHub Actions
    - Documentation: Quarto, quartodoc
    - Dependency management: Conda, Hatch
    - Python package template: Copier, pyOpenSci
    - Testing: Codecov, pytest

Click [here](https://ubc-mds.github.io/wordguess/) to view the package manual.

To view the source code, build the package locally, or contribute to the project, visit the [GitHub <img src="../../assets/img/github-icon.svg" alt="drawing" width="16"/>](https://ubc-mds.github.io/wordguess/) repository.

<u>Technologies</u>: GitHub Actions • Hatch • quartodoc • pytest • Python
