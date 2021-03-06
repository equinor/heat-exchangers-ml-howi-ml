# howi-ml
HoWi ML is a top-level machine learning package for prototyping and comparison between different scikit-learn, MLP, LSTM and GRU model architectures. It originates from a master thesis focusing on the use of Machine Learning regression models for the oil and gas domain.

The package is published on PyPi. To install, do the following:
- Install Python 3.6
- Create a new virtual environment
- pip install howiml

Additional packages like Tensorflow, Keras etc. are automatically installed.

# Usage
Code documentation is available in the "doc" folder

Two examples using the stateless (default) and stateful module are seen in the top-level repository ("example_stateful.ipynb" and "example_stateless.ipynb", respectively).

Some features of the package are:
- Stateless top-level module with most required functionality to define and compare machine learning regression models
- Similar, stateful top-level module for inexperienced users
- A lot of underlying functionality for more advanced users, available from howiml.utils

Usage is as follows:
- Make sure your dataset is available in .csv format, with column names in the first row and each data row in subsequent rows
- Define the required metadata for your dataset. It is suggested that you implement a local config file and import this in your project, e.g. configs.py with methods to extract all the same metadata as seen defined in the notebook examples
