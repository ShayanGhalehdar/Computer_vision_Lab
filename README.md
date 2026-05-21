# Computer Vision Lab — Classical Methods

A series of lab assignments implementing classical computer vision techniques in Python (NumPy, scikit-learn, OpenCV). Completed as part of a Computer Vision course at Sharif University of Technology.

## Labs

| Lab | Topic |
|---|---|
| 1 | PCA and eigenfaces — face representation via principal component analysis. |
| 2 | Linear regression for emotion intensity estimation. |
| 3 | Fisher LDA classification. |
| 4 | SVM classification — including kernel methods to increase dimensionality (RBF, polynomial). |
| 5 | Feature extraction filters — Canny, Sobel, Prewitt, and morphological operations. |
| 6 | Keypoint detection — Laplacian-of-Gaussian (LoG) blob detector and SIFT. |
| 7 | Feature descriptors — Local Binary Patterns (LBP), Gabor filters for texture, Histogram of Oriented Gradients (HOG). |

## Tech Stack

- Python 3
- NumPy, SciPy
- scikit-learn (PCA, LDA, SVM, regression)
- OpenCV (filters, SIFT, HOG)
- Matplotlib (visualization)
- Jupyter notebooks

## Repository Structure

```
Lab1 - PCA method and deriving eigenfaces/
Lab2 - Linear regression for emotion intensity/
Lab3 - Fisher LDA classification/
Lab4 - SVM classification (and use kernels to increase dimension)/
Lab5 - Various Feature Extraction Filters ( canny - sobel - prewitt - morphological ops)/
Lab6 - Filters to find key points (LOG the blub detector - SIFT)/
Lab7 - Feature extraction descriptors ( LBP light intensity - Gabor texture - HOG)/
```

## How to Run

```bash
python -m venv .venv && source .venv/bin/activate
pip install numpy scipy scikit-learn opencv-python matplotlib jupyter
jupyter notebook
```

Then open any lab notebook.

## License

MIT — see [LICENSE](LICENSE).
