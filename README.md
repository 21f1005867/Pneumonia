# PneumoniaMNIST Data Augmentation & Classification

This project demonstrates data augmentation and deep learning classification on the PneumoniaMNIST dataset using PyTorch and torchvision.

## Features

- Loads PneumoniaMNIST `.npz` data
- Custom PyTorch `Dataset` class for numpy arrays
- Advanced data augmentations using `torchvision.transforms`
- Model training, validation, and test pipeline
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score

## Requirements

Install dependencies with:
pip install -r requirements.txt


## Usage

1. **Prepare Data:**  
   Download the `pneumoniamnist.npz` file and place it in your project directory or update the path in the notebook.

2. **Run the Notebook:**  
   Open and execute `wit_augmentation_for.ipynb` step by step.

3. **Modify Augmentations:**  
   You can adjust the `transform` and `test_val_transforms` in the notebook to experiment with different data augmentation strategies.

## Main Libraries Used

- [PyTorch](https://pytorch.org/)
- [torchvision](https://pytorch.org/vision/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [Pillow (PIL)](https://python-pillow.org/)
- [tqdm](https://tqdm.github.io/)
- [scikit-learn](https://scikit-learn.org/)

## Notes

- The notebook is GPU-ready and can be run on Kaggle, Colab, or any local machine with a compatible GPU.
- Data augmentations are tailored for medical images but can be easily modified for other use cases.

## License

This project is for educational and research purposes.

---

