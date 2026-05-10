# LeetCode Top 150

A growing collection of solutions to the [LeetCode Top Interview 150](https://leetcode.com/studyplan/top-interview-150/) problem set, implemented in Python and documented with Jupyter Notebooks.

Each notebook includes:

- Problem statement and constraints
- Solution with a LeetCode-style class implementation
- Approach explanation and intuition
- Time and space complexity analysis

## Progress

| # | Problem | Category | Time | Space |
| --- | ------- | -------- | ---- | ----- |
| 26 | [Remove Duplicates from Sorted Array](array-strings/26.%20Remove%20Duplicates%20from%20Sorted%20Array.ipynb) | Array / String | O(n) | O(1) |
| 27 | [Remove Element](array-strings/27%20Remove%20Element.ipynb) | Array / String | O(n) | O(1) |
| 88 | [Merge Sorted Array](array-strings/88%20Merge%20Sorted%20Array.ipynb) | Array / String | O((m+n) log(m+n)) | O(1) |
| 189 | [Rotate Array](array-strings/189%20Rotate%20Array.ipynb) | Array / String | O(n) | O(1) |

### Solved: 4 / 150

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for dependency management and requires Python 3.13+.

```bash
# Install dependencies
uv sync

# Launch Jupyter
uv run jupyter notebook
```

## Structure

```text
leetcode-top-150/
└── array-strings/    # Array & String problems
```

New categories will be added as more problems are solved.
