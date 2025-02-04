### Overview
This repository contains code for analyzing and training models for the LUNA16 challenge using PyTorch. The LUNA16 challenge focuses on the automatic detection of lung nodules in chest CT scans.

### Files
The repository contains the following key Jupyter Notebooks:
- [`luna16-nodule-analysis.ipynb`](https://github.com/danielinux7/LUNA16-PyTorch/blob/main/luna16-nodule-analysis.ipynb): This notebook is used for analyzing lung nodules.
- [`luna16-training.ipynb`](https://github.com/danielinux7/LUNA16-PyTorch/blob/main/luna16-training.ipynb): This notebook is used for training the model on the LUNA16 dataset.

### Prerequisites
- Python 3.10 or later
- PyTorch
- Jupyter Notebook

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/danielinux7/LUNA16-PyTorch.git
   cd LUNA16-PyTorch
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. **Analyzing Lung Nodules:**
   Open and run the `luna16-nodule-analysis.ipynb` notebook to perform analysis on lung nodules. This notebook includes steps for data preprocessing, visualization, and nodule detection.

2. **Training the Model:**
   Open and run the `luna16-training.ipynb` notebook to train the model. The notebook includes steps for data loading, model definition, training loop, and evaluation metrics.

### Data
Ensure you have access to the LUNA16 dataset and have it properly downloaded. Update the notebook paths to point to your local dataset files.

### Contribution
Contributions are welcome. Please fork the repository and submit a pull request with your changes.

### License
This project is licensed under the Apache 2.0 License. See the [LICENSE](https://github.com/danielinux7/LUNA16-PyTorch/blob/main/LICENSE) file for more details.

Feel free to refer to the notebooks for detailed steps and code explanations.
