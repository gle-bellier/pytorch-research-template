# Pytorch research template

This repo aims at providing a default configuration for research repositories using Pytorch.
It will include the following tools:

- Pytorch Lightning (for fast training routines prototyping)
- Pytorch Lightning CLI (for config files)
- Weights and biaises (for logging)

## Project structure

```
_
|_ configs (include all config files)
|_ dataset (include all raw and processed data files)
|_ logs
|_ src
  |_ data (scripts for data pre/post processing and data handlers)
    |_ datamodules (include pytorch datamodule)
    |_ dataprocessors (include pytorch dataprocessors)
    |_ transforms (include all data transforms)
    |_ visualization (inlude tools for data analysis)
  |_ eval
  |_ models
    |_ blocks (all elementary neural network blocks)
    |_ nn (all models)
  |_ train
  |_ utils
|_ tests

```
