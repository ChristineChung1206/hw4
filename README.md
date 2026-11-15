# Homework 4 code package

The `hw4.ipynb` notebook contains the complete programming solution, saved
outputs, and code that regenerates every figure. The written
exercises are included in the separate report.

## Run

1. Open a terminal in this `hw4` directory.
2. Install packages: `python -m pip install -r requirements.txt`.
3. Run all cells in `hw4.ipynb` with a Python 3 kernel.

The notebook reads `data/faithful.dat` and `data/faces/` and writes its figures
to `figures/` and numerical output to `results.json`. It does not download data
at runtime.

Sources: the [Old Faithful data](https://www.stat.cmu.edu/~larry/all-of-statistics/=data/faithful.dat)
and the [course Yale faces archive](https://cornelltech.github.io/cs5785-fall-2019/data/faces.zip),
both linked by the Homework 4 handout.

The notebook uses EM implemented from scratch. Scikit-learn is used only for
K-means and the permitted logistic regression classifier.
