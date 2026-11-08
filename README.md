# CS 6220 Homework 4

Local project for frequent itemsets, association rules, and hierarchical clustering. Work lives in `hw4.ipynb`. Input files go in `data/`.

## Setup

From this directory:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name cs6220-hw4 --display-name "Python (cs6220-hw4)"
```

## Run

```bash
source .venv/bin/activate
jupyter notebook hw4.ipynb
```

You can also open `hw4.ipynb` in JupyterLab, VS Code, or Cursor and select the `cs6220-hw4` kernel.
