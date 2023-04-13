# Model of Find KeyWords In Text

[![CircleCI](https://circleci.com/gh/EneasJr-Rodrigues/model_fkeywords.svg?style=shield&circle-token=616f1a5503dbf230d7aa84a7bfd60e9cb166c834)](https://app.circleci.com/pipelines/github/EneasJr-Rodrigues/model_fkeywords)
[![Python required version: 3.8.10](https://img.shields.io/badge/python-3.8.10-blue.svg?style=flat-square)](https://www.python.org/downloads/release/python-3810)
[![pre-commit](https://img.shields.io/badge/pre--commit-disabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This project was created by the [Eneas Rodrigues](https://github.com/EneasJr-Rodrigues/model_fkeywords).
Contact them for instruction on how to build, run and test it.
This project generates wheel file, and allows installation in other IDE or Google Colab
The project's internal directories have a Python notebook to use for testing.

## Install Model of API

```shell

Install:
pip install https://inkdna.jfrog.io/artifactory/dna-ink-pypi/model-fkeywords/0.1.0/model_fkeywords-0.1.0-py3-none-any.whl

```

## Build the libraries

```shell
Install: 
python3 setup.py bdist_wheel
```

## Basic Installation

* Step_1: install the project and create wheels file: comand_line$: python3 setup.py bdist_wheel
* Step_2: Copy file this directory -> ~/dist/api-0.1.0-py3-none-any.whl
* Step_3: Put the wheel file from root of directory or root the project
* Step_4: Install the .whl -> comand_line$: pip install api-0.1.0-py3-none-any.whl
* Step_5: Import the functions -> from api import nlextract
* Step_6: Creating object of functions inside the whl -> extractor = nlextract.NLExtractor()
* Step_7: Call the functions -> extractor.pattern_matcher, extractor.lemmatizer (all of functions stay in ## Usually Functions)

## Usually Functios

* Cleaner
* Remove_special_characters
* Tokenizer
* Filter_stop_words
* Stemmer
* Lemmatizer
* NGrams
* Histogram (Word Frequency)
* Anonymizer
* Pattern Matching
* NER (Named Entity Recognition)
