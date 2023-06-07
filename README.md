# Welcome to TerraQi's Model Development Repository
This repository contains the code and instructions to train and explore machine learning models to predict renewable energy generation.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you can run the code in this repository, make sure you have the following prerequisites installed:

- Conda (Miniconda or Anaconda)
- Python 3.8 or above

## Installation

To set up your environment and install the required dependencies, follow these steps:

1. Download and install Conda from the [official Conda website](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

2. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/SamSSLF/terraqi-model-development.git

3. Navigate to the repository's root directory:

    ```shell
   cd terraqi-model-development

4. Create a new Conda environment
    
    ```shell
    conda create --name terraqi python=3.10

5. Activate the newly created environment

    ```shell
    conda activate terraqi

6. Install the required dependencies

    ```shell
    pip install -r requirements.txt
    ```
    
    A dependency called cfgrib requires a conda installation as follows:

    ```shell
    conda install -c conda-forge cfgrib

## Usage
1. Download data from ECMWF
2. Choose the terraqi Python interpreter in VS Code and open jupyter notebooks from within VS Code.