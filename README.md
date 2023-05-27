# NHL Time Series Transformer

Author: Scott Kinder

This repo contains a notebook which demonstrates a simple proof of concept for taking
raw NHL data from moneypuck.com, extracting it and performing transformations before
feeding it to a custom time series Transformer, based off the PyTorch seq-to-seq transformer,
but instead of taking an input token at time steps it takes the n-dimensional data, and outputs
desired variables for next time steps.

Please see the train scripts for further details on implementation, benchmarks, and graphed results.