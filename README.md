# Songs-Generator-Using-Probabilistic-models



## Modified N-gram Markov Chain Model

### Introduction
Using probabilistic models as Markov Chains, Bayesian &amp; Seq2Seq probabilistic models to generate new songs.
The modified n-gram Markov chain model is designed to generate text based on observed sequences of n-grams.

### Overview
The project consists of Python code that implements a modified version of a Markov chain model utilizing n-grams. The modified model includes considerations for word selection based on observed frequencies.

### Code Structure
The project comprises the following main components:
- `generate_word_progression` function: Generates text using a modified Markov chain approach.
- `build_markov_chain` function: Constructs the Markov chain based on input text and n-gram order.

### Usage
The code can be utilized by following these steps:
1. Initialize the n-gram order and provide a dataset.
2. Build the Markov chain using the `build_markov_chain` function.
3. Generate text using the `generate_word_progression` function, considering modifications for word selection.

### Modification Details
- Utilizes a modification in the word selection process to consider observed frequencies for better text generation.
- Introduces weighted probability-based word selection compared to the original uniform random selection.

## Bayesian Text Generator

### Introduction
The Bayesian Text Generator uses a probabilistic approach based on observed frequencies of n-grams to generate text.

### Overview
This project implements a Python-based Bayesian approach for text generation using n-grams and frequency-based probabilities.

### Code Structure
The primary components of the project include:
- `BayesianTextGenerator` class: Responsible for training and generating text using Bayesian inference.
- `train` method: Trains the generator based on observed n-grams and their frequencies.
- `generate_text` method: Generates text using the trained model and Bayesian probabilities.

### Usage
To use the Bayesian Text Generator:
1. Instantiate the `BayesianTextGenerator` with a specified order.
2. Train the generator using a dataset.
3. Generate text by specifying a seed n-gram or word.

### Key Features
- Utilizes Bayesian inference to model the probability of next words based on observed n-grams and their frequencies.
- Allows for generation of text reflecting the observed patterns and frequencies in the training data.

## Conclusion
Both models offer unique approaches to text generation, with the modified n-gram Markov chain focusing on weighted probabilities for word selection and the Bayesian Text Generator utilizing Bayesian inference for probabilistic text generation.

