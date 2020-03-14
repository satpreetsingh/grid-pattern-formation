# Grid cells in artificial neural networks

Code to reproduce the trained RNN in [** A unified theory for the origin of grid cells through the lens of pattern formation**](https://papers.nips.cc/paper/9191-a-unified-theory-for-the-origin-of-grid-cells-through-the-lens-of-pattern-formation). Training an RNN on a path integration task produces grid-like representations. A set of pre-trained weights is stored in [**models/example_trained_weights.npy**](models/example_trained_weights.npy).

* [**inspect_model.ipynb**](inspect_model.ipynb):
  Train a model and visualize its hidden unit ratemaps.
  
* [**main.py**](main.py):
  or, train a model from the command line.

## Result

![grid visualization](./docs/RNNgrids.png)
