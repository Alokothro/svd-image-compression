# svd-image-compression

Compressing images with the singular value decomposition.

**MATH 344L: Applied Linear Algebra Lab, Project 1**

## About

A grayscale image is just a matrix of brightness values, where 0 is black and 255 is white. In this
project we use the singular value decomposition (SVD) to approximate an image by a lower-rank matrix.
Keeping only a few patterns means storing much less data while the picture stays recognizable.

## Milestones

| # | Notebook | What it covers |
|---|---|---|
| 1 | [Images as matrices](notebooks/01%20image%20as%20matrix.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alokothro/svd-image-compression/blob/main/notebooks/01%20image%20as%20matrix.ipynb) | Grayscale and color images as matrices, the `uint8` overflow trap, matrix rank, rank-1 images, and turning my own photo into a matrix |

## Repository layout

```
notebooks/   Colab notebooks, one for each milestone
src/         Reusable Python programs, such as compress.py
figures/     Plots and images used in the project or presentation
```

## Running the notebooks

The easiest way is the **Open in Colab** button above, then **Runtime → Run all**. Part E asks you to
upload a photo.

To run them on your own computer instead:

```bash
pip install -r requirements.txt
```

## License

This project is released under the [MIT License](LICENSE).
