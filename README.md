# Nested sampling seminar

See the notes at [this link](http://htmlpreview.github.io/?https://github.com/fellowship-of-clean-code/nested-sampling/blob/main/nested-sampling-seminar.html).

To build:

```
quarto render nested-sampling-seminar.qmd
```

The dependencies are listed in `pyproject.toml`, you can install them with `pip` (`pip install .`) 
or `uv` (one single command: `uv run quarto render nested-sampling-seminar.qmd`).