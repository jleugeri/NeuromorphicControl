# Introduction to Neuromorphic Control

Course page for the lecture "Introduction to Neuromorphic Control", summer term 2026, Osnabrück University.

## Contents

| Directory | Description |
|-----------|-------------|
| [`lectures/`](lectures/) | Lecture slides and recordings |
| [`homework/`](homework/) | Homework exercises (Jupyter notebooks) and solutions |
| [`script/`](script/) | Course script |
| [`resources/`](resources/) | Supplementary material and references |

## Repository Structure

```
NeuromorphicControl/
├── lectures/
│   ├── README.md
│   └── NN_<topic>/          # one folder per lecture
│       ├── README.md        # recording link, topics covered
│       └── slides.*         # slide deck
├── homework/
│   ├── README.md
│   └── hwNN_<topic>/        # one folder per assignment
│       ├── exercise.ipynb   # notebook for students
│       └── solution.ipynb   # notebook with solutions
├── script/
│   └── README.md
└── resources/
    └── README.md
```

## Getting Started

The homework exercises are provided as [Jupyter](https://jupyter.org/) notebooks.

**Option A – Google Colab (no installation needed):** click the *Open in Colab* badge at the top of any notebook to run it directly in your browser.

**Option B – Local setup:** install the dependencies and launch JupyterLab:

```bash
pip install jupyterlab numpy matplotlib
jupyter lab
```
