# Wine Dataset Model Exploration

## Project Overview

This project involves exploring the Wine dataset, building machine learning models, and generating model cards for each model. The Wine dataset contains chemical analysis results of wines grown in the same region in Italy but derived from three different cultivars. The goal is to classify the wines based on their chemical properties.

## Directory Structure

├── notebooks
│ └── 01-notebook.ipynb # Jupyter notebook with data exploration and model training
├── model_cards # Directory where generated model cards are saved
├── data # Directory containing the Wine dataset
├── models # Directory to save trained models
|-- requirements.txt
|-- LICENSE
|-- pyproject.toml
└── README.md # Project README file

## Getting Started

### Prerequisites

- Python 3.11 or higher
- Required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Jupyter Notebook

### Installation

1. Clone the repository:

``` sh
git clone https://github.com/BlvckSanek/experiment
cd experiment
```

2.Install the required libraries

```sh
pip install -r requirements.txt
```

### Running the Notebook

1. Navigate to the [`notebook`](/notebooks)

```sh
cd notebooks
```

2.Start Jupyter Notebook:

```sh
jupyter notebook
```

3.Open [`01-notebook.ipynb`](/notebooks/01-notebook.ipynb)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- The Wine dataset is sourced from the UCI Machine Learning Repository.
- Thanks to the developers of the Python libraries used in this project.
