# Pre-Commit NB Scrub

A [pre-commit](https://pre-commit.com/) hook to remove all code outputs in all ipython notebook(s) in a given directory
using jupyter `nbconvert` utility.

## Installation

Add the following to your `.pre-commit-config.yaml` repos section

``` yaml
repos:
-   repo: https://github.com/TWAICE/precommit-nbscrub
    rev: 1.0.0
    hooks:
        - id: ipynb-output-scrub
```
