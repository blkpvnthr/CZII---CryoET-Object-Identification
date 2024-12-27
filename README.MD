# CZII - CryoET Object Identification

This repository contains code and resources for the CZII - CryoET Object Identification competition. The goal of this project is to develop machine learning (ML) algorithms that automatically annotate diverse protein complexes in 3D cellular images, which will help accelerate discoveries in biomedical science and advance disease treatment.

## Project Overview

Cryo-electron tomography (cryoET) creates 3D images of cells, providing detailed views of proteins within their natural environment. The task is to identify and annotate specific protein complexes in cryoET tomograms, with a focus on accurately detecting five key particle types.

### Key Information
- **Competition Goal**: Detect and annotate protein complexes in 3D cryoET images.
- **Evaluation Metric**: F-beta metric with a beta value of 4, emphasizing recall over precision.
- **Data Format**: Input data consists of 3D tomograms, and the output requires 3D coordinates for detected particles in each tomogram.

## Project Structure

- `data/`: Contains data files and any preprocessed data.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model development.
- `src/`: Source code for data loading, preprocessing, model training, and evaluation.
- `requirements.txt`: List of dependencies required to run this project. 
- `README.md`: Project documentation.
- `submission.csv`: Example submission file for the competition.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cryoet-object-identification.git
   cd cryoet-object-identification

2. Install dependencies:
    ``` pip install -r requirements.txt

3. Launch Jupyter Notebook for interactive development:
    jupyter notebook


## Data Preparation
Download the data from the competition page and place it in the data/ directory.
Ensure the data is in the correct format (3D arrays or images as specified by the competition) and verify using the notebooks provided in notebooks/.

## Requirements
See requirements.txt for a full list of dependencies. Main libraries include:

- numpy
- pandas
- torch
- scikit-learn
- tqdm
- jupyter

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve this project.


## Acknowledgements
- CZII - CryoET Object Identification: The Chan Zuckerberg Initiative sponsors this competition.
- PyTorch: For the deep learning framework used to build and train models.
- scikit-learn: For model evaluation and metrics.
