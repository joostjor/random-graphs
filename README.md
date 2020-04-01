# Random graph visualization

The aim of this project is to facilitate reuse of simulations of various random graph models.
These simulations could be used either for visualization purposes or for computational analysis.
Although at the moment only the geometric inhomogeneous random graph model is available, I expect to add other (spatial) models soon.

Quite some models are readily available in the NetworkX python package.

In the future I might open a pull request there.

Supported graphs:
  - Geometric Inhomogeneous Random Graphs

## Using figures/simulation
I warmly support you to use any of the figures generated with this code in papers/presentations/etc.
Please don't forget to include a reference to this github project, so that it may be checked by referees,
but also might be reused by other interested people, so that not everybody are reinventing the wheel.

### Reference example
BibTex (Substitute the used commit code):
```
@misc{jorritsma-randomgraphs2020,
  author = {Jorritsma, Joost},
  title = {Random Graph Simulations},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/joostjor/random-graphs}},
  commit = {519c6e3}
}
```

## Questions
If you have any troubles, questions or requests, please don't hesitate to contact me!

## Run Python Code
1. Make sure a Python 3 version is installed.
2. Create a virtual environment containing the right packages:
  ```
  $ python -m venv <name-of-env>`
  $ source <name-of-env>/bin/activate
  $ pip install -r requirements.txt
  ```
3. Adjust the parameters in the file to your need and run the code, e.g., `python girg.py`
