# DL Video Analysis

Deep Learning based Video Analysis project for extracting features from video data and performing model training/testing using deep learning techniques.

## Project Structure

```text
DL-Video-Analysis/
│
├── feature_extraction.ipynb
├── model_training.ipynb
├── model_testing.ipynb
├── dataset/
├── output.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## Dataset

This project uses the SoccerNet dataset for video analysis tasks.

Dataset source:

SoccerNet provides:

- Soccer match videos
- Event annotations
- Labels and metadata
- Additional supporting files

### Download Instructions

1. Download the required dataset files from the official SoccerNet source.
2. Extract the downloaded files.
3. Place the dataset inside the project directory:

```text
DL-Video-Analysis/
│
├── dataset/
│   ├── videos
│   ├── annotations
│   └── other_files
│
├── feature_extraction.ipynb
├── model_training.ipynb
├── model_testing.ipynb
```

4. Update dataset paths inside notebooks if required.

## Notes

The dataset is not included in this repository due to file size limitations.

## Features

- Soccer video event analysis
- Video feature extraction
- Deep learning model training
- Model testing and evaluation
- CSV output generation
- Processing of video datasets

## Technologies Used

- Python
- PyTorch
- OpenCV
- Transformers
- TorchVision
- Torch Geometric
- NumPy
- Pandas

## Installation

Clone repository:

```bash
git clone https://github.com/YOUR_USERNAME/DL-Video-Analysis.git
cd DL-Video-Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run

Open Jupyter Notebook:

```bash
jupyter notebook
```

Execute in order:

1. `feature_extraction.ipynb`
2. `model_training.ipynb`
3. `model_testing.ipynb`

## Output

The project generates CSV output containing processed or predicted results from video analysis.

## Author

Ananyo Sen
