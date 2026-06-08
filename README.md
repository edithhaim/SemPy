# SemPy Networks
Python tools for constructing, analyzing and visualizing semantic networks from verbal fluency and Woseco data.

## Overview

SemPy provides methods for transforming behavioural language from the verbal fluency and Woseco tasks into semantic networks. It is based on the SemNA methodology from Christensen & Kenett (2023). SemPy adapts this approach to Python and creates networks, visuals and extracts network-level characteristics relevant to cognitive and creativity research.

The repository includes procedures for:

* Building semantic networks from verbal fluency and Woseco data
* Computing graph-theoretical metrics
* Detecting community structure
* Visualising semantic networks

## Main File

### SemPy_Networks.ipynb

Jupyter notebook containing the complete workflow for:

* Data preprocessing and lemmatization
* Response matrix generation
* Network construction
* Network analysis
* Community detection
* Visualisation

## Requirements

Typical dependencies include:

* pandas
* numpy
* networkx
* scipy
* matplotlib
* spacy

## Input Data

The notebook accepts participant-by-response datasets where the responses are provided in an "Output" column in the form ['response1', 'response2', 'response3', ...].
An example dataset is found as "VF and WSC_Responses.xlsx"

## Applications

The code can be used for:

* Verbal fluency network construction
* Woseco network construction
* Creativity research
* Cognitive network science
* Exploratory semantic structure analysis

## Citation
* Christensen, A. P., & Kenett, Y. N. (2023). Semantic network analysis (SemNA): A tutorial on preprocessing, estimating, and analyzing semantic networks. Psychological Methods, 28(4), 860.
* Haim, E., Haim, K., Beaty, R.E., Siew, C.S.Q., Stella, M. (2026). Introducing multiplex semantic networks as multifaceted representations of creative associative knowledge across multilingual samples. arXiv.

## License
MIT License.
