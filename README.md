# recommender-systems-social-network-analysis

Linkedin social network analysis done for the L4 recommender systems module.

## Data Acquisition

To obtain the data used in this project, please follow these steps:

- Go to [LinkedIn](https://www.linkedin.com/)
- Go to Settings & Privacy → Data Privacy → Get a copy of your data
- Use 'Download larger data archive' option
- Once the request is ready, download the zip file
- Inside the zip, find the file named `Connections.csv` or similar
- Save it in the `data/` folder
- Rename it to `Connections.csv` if necessary
- The data is now ready to be used in the notebooks

> **Note:** The data only contains your connections, not their connections. To build a more extensive social network, additional data collection methods would be required.
> For privacy reasons, the actual data file is not included in this repository.

## Notebooks

The main analysis is performed in the `social-network-analysis.ipynb` notebook located in the `notebooks/` folder. This notebook includes data loading, preprocessing, network construction, visualization, and analysis steps.

## Prerequisites

- Python 3.11 or higher
- Poetry for dependency management

## Setup

1. Clone the repository

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory

    ```bash
    cd recommender-systems-social-network-analysis
    ```

3. Install dependencies using Poetry

    ```bash
    poetry install
    ```

4. Activate the virtual environment

    ```bash
    poetry shell
    ```

5. Launch Jupyter Notebook

    ```bash
    jupyter notebook
    ```

6. Open the `social-network-analysis.ipynb` notebook and run the cells to perform the analysis.
