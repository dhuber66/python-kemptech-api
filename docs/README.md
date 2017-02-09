Building
========
We're using `sphinx_rtd_theme` make sure to `pip install sphinx_rtd_theme` to build

Use `sphinx-apidoc ../ -o source/ -e -f` to generate sources and insert them into `source/`. 

Edit `source/config.py` to bump the version or change settings

To build run: `make html`

Docs can be found in `docs/build/html/index.html`

`requirements.txt` found in this folder contains sphinx and the sphinx theme 

To push docs live, move ./build/html/ into `gh-pages` branch.