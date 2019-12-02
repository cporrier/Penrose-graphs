# Fully leafed Penrose trees

Files in this repo were used to study the problem of fully leafed induced subtrees and the leaf function of graphs corresponding to Penrose tilings of the plane. This study is the object of the article *The Leaf Function of Graphs Associated with Penrose Tilings*, written with Alexandre Blondin Massé.

Early computations were done using SageMath (Jupyter notebooks).

- `Empires.ipynb` can be used to generate and plot the 7 vertex configurations and their "kingdoms", as defined in the article.
- `Penrose_graph_and_IMT_kd.ipynb` is meant to generate a patch using the substitution method, plot it, define and plot its corresponding graph, and find its leaf function using the branch and bound algorithm for the leaf function of a graph, which was conceived and implemented in Python by Émile Nadeau in the file `IMT.py`. Note that the time complexity is exponential and that a few minutes are needed to reproduce the given example.

To run these programs, you can install Sagemath on your computer (see http://www.sagemath.org/ for download) or simply use it online via https://cocalc.com/

Licence: MIT (see `LICENSE` file)
