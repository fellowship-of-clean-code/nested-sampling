# Nested sampling seminar

See the notes for [the original talk](http://htmlpreview.github.io/?https://github.com/fellowship-of-clean-code/nested-sampling/blob/main/nested-sampling-seminar.html),
and the ones for [the tutorial at the PRIN meeting](http://htmlpreview.github.io/?https://github.com/fellowship-of-clean-code/nested-sampling/blob/main/nested-sampling-tutorial-PRIN.html).

To build:

```
quarto render nested-sampling-seminar.qmd
```

(and similarly for the other files).

The dependencies are listed in `pyproject.toml`, you can install them with `pip` (`pip install .`) 
or `uv` (one single command: `uv run quarto render nested-sampling-seminar.qmd`).