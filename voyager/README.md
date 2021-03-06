[Voyager](https://vega.github.io/voyager/) is a recommendation-powered visualization browser. It is good for *exploring* data, and it may be good enough to help you discover a trend or correlation you otherwise missed--or at least see it faster. It is a product of Univ. Washington's [Interactive Data Lab](https://idl.cs.washington.edu/papers/voyager/). Essentially, it's like a free version of Tableau. Even better, it outputs in Vega-lite formats (web-friendly, JSON formatted like D3).<br>

Normally, [Voyager](https://github.com/vega/voyager) requires some wrangling with javascript in nodejs (using a node package manager like npm), however, there is a Python labextension that builds this into JupyterLab (the next step in iPython/Jupyter notebooks, etc.)! In this repo, a python environment `voyager.yml` (and `voyager_windows.yml` for windows) has been built to make it easy to run the specific versions of Jupyterlab, nodejs, etc. to run lab-extension. <br>

To install the environment run
```conda env create -f voyager.yml``` <br>
