# Lockboxes

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/alx-interview/0x01-lockboxes/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/alx-interview/0x01-lockboxes.svg)](https://github.com/alx-interview/0x01-lockboxes/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/alx-interview/0x01-lockboxes.svg)](https://github.com/alx-interview/0x01-lockboxes/network)

> This project is part of ALX's curriculum and focuses on solving the Lockboxes problem.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and may contain keys to other boxes. This project contains a Python function that determines if all the boxes can be opened.

### Tasks

- [x] Implement the `canUnlockAll` function.
- [x] Create test cases to validate the function's correctness.

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the project folder, is mandatory
- Your code should be documented
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable

## Usage

You can use the `canUnlockAll` function in your Python scripts to determine if a list of locked boxes can be opened. Here's an example of how to use it:

```python
from lockboxes import canUnlockAll

boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))  # Output: False

