# precommit-ruff-demo

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Template repository that enforces code style using `ruff` and git hooks
configured using `pre-commit`.

## Quickstart

### Install dependencies

```sh
python -m pip install pipx
pipx install ruff
pipx install pre-commit
```

### Initialize git hooks

`pre-commit install`

That's it, the next time you commit your changes a `pre-commit` hook
will automatically lint and format your code.

##  License

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
