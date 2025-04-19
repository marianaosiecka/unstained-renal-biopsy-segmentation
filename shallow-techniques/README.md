# unstained-renal-biopsy-segmenation

These experiments were carried out in the context of understanding the feasibility of segmenting unstained renal biopsy samples using machine learning techniques such as K-NN and K-means.


## Installation

Follow these steps to set up the project environment and install dependencies.

### Prerequisites

- **Python 3.11**: Ensure Python 3.11 is installed on your system. Download it from python.org if needed.
- A compatible operating system (Windows, macOS, or Linux).

### Setting Up a Virtual Environment

1. **Create a virtual environment**:

   ```bash
   python3.11 -m venv MyEnv
   ```

2. **Activate the virtual environment**:

   - On **Windows**:

     ```bash
     MyEnv\Scripts\activate
     ```

   - On **macOS/Linux**:

     ```bash
     source MyEnv/bin/activate
     ```

   Once activated, your terminal should show `(MyEnv)` indicating the virtual environment is active.

### Installing Dependencies

Install the required Python packages using `pip`. Run the following command in the activated virtual environment:

```bash
pip install opencv-python matplotlib numpy scikit-learn tqdm scikit-image scipy
```

#### Dependency Details

- `opencv-python`: For image loading, processing, and feature extraction (e.g., Canny edges, Gabor filters).
- `matplotlib`: For generating visualization plots of segmentation results.
- `numpy`: For array operations and numerical computations.
- `scikit-learn`: For KNN classification and metrics like confusion matrix.
- `tqdm`: For progress bars during training (optional, used in some scripts).
- `scikit-image`: For texture features like LBP and GLCM.
- `scipy`: For distance transform and Hungarian algorithm in segmentation metrics.

#### Recommended Versions

To ensure compatibility, you can install specific versions:

```bash
pip install opencv-python==4.10.0 matplotlib==3.9.2 numpy==1.26.4 scikit-learn==1.5.1 tqdm==4.66.5 scikit-image==0.24.0 scipy==1.14.1
```

### Verifying Installation

To confirm the dependencies are installed correctly, run:

```bash
pip list
```

This will display the installed packages and their versions.

## Usage

1. Run the training scripts for binary or multiclass KNN segmentation.
2. Execute the testing scripts to generate segmented images and comparisons.
3. Evaluate results using the evaluation scripts, which produce metrics such as IoU, Dice, and accuracy.

See individual script comments for detailed instructions.


