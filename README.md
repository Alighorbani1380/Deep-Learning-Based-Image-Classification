
# Deep Learning-Based Image Classification

This repository presents a comprehensive implementation and comparison of several models for image classification using both deep learning and traditional machine learning approaches. The goal is to examine how different architectures and kernels perform in terms of accuracy, generalization, and computational cost.

## Contents

- Feature extraction using classic computer vision methods
- CNN-based classification using AlexNet and VGG
- SVM classification with various kernels (linear, polynomial, RBF, sigmoid)
- Accuracy comparisons and confusion matrix visualizations
- Complete training and evaluation workflows in Jupyter notebooks

## Models and Performance

The following models were implemented and evaluated:

| Model                | Accuracy |
|---------------------|----------|
| AlexNet             | 77.52%   |
| VGG                 | 77.56%   |
| SVM with Linear     | 74.53%   |
| SVM with Polynomial | 74.75%   |
| SVM with RBF        | 75.63%   |
| SVM with Sigmoid    | 66.24%   |

The deep learning models were implemented using PyTorch, while the SVM models use scikit-learn. The accuracy values are based on the test set performance, and detailed results are included in the individual notebooks.

## File Structure

```
Report.pdf                        # Full report with methodology, results, and conclusions
Preprocess&featureEx.ipynb  # Image preprocessing and feature extraction
Alexnet_0_7752.ipynb        # AlexNet model training and evaluation
VGG0_0.7756.ipynb           # VGG model training and evaluation
SVG_linear_0.7453.ipynb     # SVM with linear kernel
SVG_poly_0.7475.ipynb       # SVM with polynomial kernel
SVG_RBF_0.7563.ipynb        # SVM with RBF kernel
SVG_sigmoid_0_6624.ipynb    # SVM with sigmoid kernel
```

## Visualizations

![image](https://github.com/user-attachments/assets/c033024b-eeca-42cd-911e-f0213605d567)


```markdown
### Confusion Matrix (VGG and AlexNet)
![image](https://github.com/user-attachments/assets/3d9f07a3-0081-49a3-a5fd-1dcaa60f60a5)

### Confusion Matrix (CNN)
![image](https://github.com/user-attachments/assets/0f865872-ecaa-463b-9a3a-8d10230ebf54)


### Example Data Agumentation
![image](https://github.com/user-attachments/assets/2f1847c6-f435-466d-b2b3-b1a27fc80ef9)



## How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

2. Launch Jupyter and run the notebooks in the following order:

```bash
jupyter notebook
```

Recommended execution order:
- Preprocess&featureEx.ipynb
- Then, one of the classification notebooks (e.g., AlexNet or VGG)
- Compare outputs and results across different models

## Requirements

- Python 3.8+
- Jupyter Notebook
- numpy
- matplotlib
- scikit-learn
- torch
- torchvision


## Report

The file `Report.pdf` contains a formal report of the entire project including:
- Dataset description
- Preprocessing pipeline
- Model architectures and settings
- Evaluation metrics
- Discussion and conclusion

## Notes

- All results are reproducible and contained within the notebooks.
- You are encouraged to experiment with hyperparameters or test new architectures.

## License

This project is shared for academic and learning purposes. You are free to use or adapt it for your own projects, with proper citation if used in research.

---

Prepared and maintained by [Ali Ghorbani]
