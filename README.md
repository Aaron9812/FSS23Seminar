# Large Language Model Entity Matching Evaluation

## Abstract

Entity matching, a critical aspect of data integration systems, aligns disparate records to their corresponding real-world entities. This project aims to thoroughly evaluate the effectiveness of Large Language Models (LLMs) - namely CHAT-GPT, Aleph Alpha, and GPT4All - in the field of entity matching.

Our analysis is designed around set benchmarks and prompts and incorporates an extensive error examination to identify possible limitations in the tested models. Findings from the study indicate that the LLMs exhibit significant proficiency in entity matching, achieving performance on par with a well-optimized RoBERTa model across various benchmarks, and even exceeding it in one instance. 

Upon consolidating these results, we conclude the paper by proposing potential future research directions in this area.

## Introduction

This repository houses the research and code for the project "Large Language Model Entity Matching Evaluation". Our goal is to determine the effectiveness of three Large Language Models - CHAT-GPT, Aleph Alpha, and GPT4All - in performing entity matching tasks.

## Usage 

Follow these steps to get the project up and running:

1. Set up a Python virtual environment. This project was built using Python 3.9.
    ```
    python3 -m venv env
    source env/bin/activate
    ```

2. Install the necessary packages from the requirements file.
    ```
    pip install -r requirements.txt
    ```

3. Download a GPT4All model from [this repository](https://github.com/nomic-ai/gpt4all).

4. Create an `.env` file in the root directory of the project. Use the example file as a basis.


## Repository Structure

This repository is organized as follows:

- `data`: This directory contains all the data required for the project. It includes:
  - `benchmark`: This sub-directory holds the WDC benchmarks used in the evaluation.
  - `results`: This sub-directory houses the results obtained from the evaluated models.
  - `test_datasets`: This sub-directory contains the benchmarks used in the testing process.
- `paper_data`: This directory contains data used for the paper, such as tables and other reference information.

Each model evaluated in this project has its own dedicated Jupyter notebook. This allows for independent analysis and results comparison between different models.
