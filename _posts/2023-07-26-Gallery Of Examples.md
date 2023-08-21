---
title: Setting up Gallery of Examples
---
### Why use Sphinx Gallery
We utilized [Sphinx Gallery](https://sphinx-gallery.github.io/stable/index.html) to automate example galleries in our documentation because
it offers a streamlined solution for generating documentation from Python scripts,
including code execution, output capture, and figure rendering.

### Primary Objectives of Gallery
- Automatic Example Generation: We aimed to create example galleries by
  running pure Python scripts that are embedded within the documentation,
  capturing both the code outputs and the generated figures.
- Explanation-Code Fusion: Gallery involves embedding reStructuredText (reST)
  markup within the example Python scripts. This enabled us to blend explanatory content with the code,
  creating an engaging learning experience for users.
- Jupyter Notebook Integration: To cater to different learning preferences, the gallery automatically generates a
  Jupyter Notebook and source code for each example page. This notebook and python filw would contain the embedded example script, outputs, and figures.
