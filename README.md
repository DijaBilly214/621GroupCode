# Biomedical Image Analysis: Diagnosing Chest CT Scans for Covid-19

This repository contains the code and documentation for a biomedical image analysis system developed as part of the CSC621-821 course under Dr. Kazunori Okada. The system focuses on diagnosing Covid-19 in chest CT scans using advanced image processing techniques.

## Overview

The project leverages the capabilities of the SimpleITK library in Python to process 3D medical images. It implements a deformable model-based level set method for segmentation, crucial for accurately delineating lung fields and identifying potential Covid-19 infections.

## Team Members

- Khadija Khan - Registration Component Lead
- Young So - Quantification and Evaluation
- Weiting Liao - Quantification and Evaluation
- Aryaman Patel - Segmentation Component Lead
- Bhargava Kadiyala 

## System Components

- **Demons Registration**: Aligns different sets of images for accurate comparison and analysis.
- **Level Set Segmentation**: Accurately segments regions of interest, particularly lung fields and areas potentially affected by Covid-19.
- **Quantitative Analysis** 

## Installation

To set up the project environment:

```bash
git clone https://github.com/your-github-username/your-repo-name.git
cd your-repo-name
```

### Dependencies

- Python 3.x
- SimpleITK
- NumPy
- Matplotlib
- IPython
- Jupyter Notebook (for running the script interactively)

### Installing

- Ensure Python 3.x is installed on your system.
- Install required Python packages:
  ```bash
  pip install simpleitk numpy matplotlib ipython jupyter
- Use for running Jupyter notebook : https://insightsoftwareconsortium.github.io/SimpleITK-Notebooks/

### Executing the Program

- Clone the repository or download the script.
- Open the script in Jupyter Notebook.
- Run the cells sequentially to perform image segmentation.
