# pyfalldown

[![Release](https://img.shields.io/github/v/release/linhns/pyfalldown)](https://img.shields.io/github/v/release/linhns/pyfalldown)
[![Build status](https://img.shields.io/github/actions/workflow/status/linhns/pyfalldown/main.yml?branch=main)](https://github.com/linhns/pyfalldown/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/linhns/pyfalldown/branch/main/graph/badge.svg)](https://codecov.io/gh/linhns/pyfalldown)
[![Commit activity](https://img.shields.io/github/commit-activity/m/linhns/pyfalldown)](https://img.shields.io/github/commit-activity/m/linhns/pyfalldown)
[![License](https://img.shields.io/github/license/linhns/pyfalldown)](https://img.shields.io/github/license/linhns/pyfalldown)

**pyfalldown** is a platformer game built with
[pygame](https://www.pygame.org/), inspired by the classic arcade era.

In this game, you guide a circular ball downward, navigating through platforms.
Your objective is to collect triangles while avoiding squares. Be careful not to
touch the top or bottom edges of the screen!

![Demo](https://github.com/linhns/pyfalldown/blob/main/docs/assets/images/pyfalldown.gif)

## Installation

- Using [pip](https://github.com/pypa/pip):

  ```shell
  pip install pyfalldown
  ```

  Then, run the game:

  ```shell
  pyfalldown
  ```

  or:

  ```shell
  python -m pyfalldown
  ```

- Run without installation using [uv](https://github.com/astral-sh/uv):

  ```shell
  uvx pyfalldown
  ```

## Rules

- The game is over if the ball hits the top or bottom edge of the screen.
- Collecting a triangle earns you a random score between 1 and 5 points.
- Hitting a square deducts a random 1 to 5 points from your score.

## Usage

- Move ball using `Left`/`Right` arrow keys.
