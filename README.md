# Machine Learning Coursework

This repository contains my machine learning coursework notebooks (assignments, exam practice, and a small project). The work is primarily in Jupyter notebooks using **PyTorch**, **scikit-learn**, and **TensorFlow/Keras**.

## Contents

- **Assignments**
  - `A2/` – regression basics (scikit-learn diabetes dataset)
  - `A3/` – notebook-based assignment work
  - `A4/` – CNN / LeNet-style classifier work (PyTorch)
- **Exam**
  - `exam/` – `mnist-classification.ipynb`, `finalexam.ipynb`
- **Project**
  - `groupProject/` – house-price regression notebook(s)
- **Other notebooks**
  - `TFlite.ipynb` – TensorFlow → TFLite conversion experiments
  - `3d-tof-7cx/` – ToF sensor visualization notebook
  - `gitlab-ta-checker/` – helper notebook(s)

## Quickstart (local)

Prereqs: **Python 3.10+**

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Data & artifacts

- Many notebooks download datasets automatically (e.g., torchvision / keras built-ins).
- Local datasets and generated artifacts (e.g., `data/`, `*.pth`, `*.h5`, `*.tflite`) are intentionally **not tracked** in git. See `.gitignore`.

## Notes

- If you run training notebooks on a machine with CUDA, PyTorch/TensorFlow will use the GPU when configured.
- Some notebooks include outputs/plots inline for readability on GitHub.

## Acknowledgement

- Some repository organization and documentation cleanup was done with help from an AI coding assistant.

## References

- [PyTorch “Training a Classifier” tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)

