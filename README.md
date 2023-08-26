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
sphinx-autobuild -b html . _build/
```

You should now be able to view it at ``http://127.0.0.1:8000``.
