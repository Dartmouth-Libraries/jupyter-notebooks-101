# Jupyter Notebooks 101

## Intro

- PowerPoint Slides:
  - What is Jupyter?
  - What is IPython?
  - Why interactive computing?
  - Notebooks and kernels
  - Jupyter Notebook
  - JupyterLab
  - VS Code
  - Google Colab
  - JupyterHub

## First steps

- Walk through layout of Jupyter Notebook
- Comparison Notebook and Lab view
- Markdown cells:
  - Formatted text
  - Equations
  - HTML
  - Reference files (images and video)
- Code cells:
  - Accepted code depends on kernel
  - Execute
- Producing figures
  - Sample seaborn figure
  - Changing format to SVG
  - Save to file
- Magic commands
  - system escape `!`
  - %who
  - ?obj
  - %timeit
  - %prun
  - %history
  - %%writefile
  - %quickref
- [Pitfalls](https://scicomp.aalto.fi/scicomp/jupyter-pitfalls/):
  - Discourages modularity
  - Difficult to integrate into a bigger system, easily leads to "God notebooks"
  - Difficult to test code
  - Difficult to debug
  - Version control can be annoying
  - Running code out of order can cause poorly defined state
- Use cases for notebooks:
  - low- to medium-complexity code
  - rapid prototyping
  - educational
  - reproducibility (but not reusability)
