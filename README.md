# quarto-example

Setup instructions:

* Install the Quarto CLI following [these instructions](https://quarto.org/docs/get-started/)
* Run `conda env create -f envs/quarto-env.yml` to create an environment with the notebook dependencies
* Run `quarto render hello.ipynb --to html` to generate HTML files from the Jupyter notebook.

This outputs a HTML file.  You can run `open hello.html` to open this file in your browser and see the beautiful output.
