# Tutorials
A repository for Insight guides, tutorials and documentation!


## Installation

To install the required packages, run the following command:

```bash
poetry install
poetry shell
```


## Build

To build the documentation, run the following command:

```bash
sphinx-build -b html . _build/
```

## Viewing the documentation

To view the documentation, run an http server in the `_build` directory:

```bash
cd _build
python -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.
