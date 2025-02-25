# Defect Detection Model

This Jupyter Notebook, `Defect Detection Model.ipynb`, contains data analysis and machine learning modeling to detect defects in images. The analysis is based on the data provided in the `train.csv` directory and the corresponding defect annotations.

## Contents

1. **Introduction**
   - Overview of the defect detection problem and the objectives of the analysis.

2. **Data Loading and Preprocessing**
   - Steps to load and preprocess the image data and defect annotations.

3. **Model Training and Evaluation**
   - Training machine learning models to detect defects in images and evaluating their performance.

4. **Visualization of Results**
   - Visualizing the model predictions by overlaying defect masks on the original images.

5. **Conclusion**
   - Summary of findings and potential recommendations for improving defect detection.

## Data Source

- `train.csv`: CSV file containing the training images encoder pixels.
- `test.csv`: CSV file containing the training images encoder pixels.
- `defect_and_no_defect.csv`: CSV file containing the defect annotations for the images.
- `train_images/`: Directory containing the training images.

## How to Run

1. Ensure you have Jupyter Notebook installed.
2. Open the `Defect Detection Model.ipynb` file in Jupyter Notebook.
3. Run the cells sequentially to execute the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn
- Skimage