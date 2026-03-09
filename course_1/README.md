# Course 1

This folder contains a structured set of notebooks for building intuition about language modeling, starting from basic probability and moving toward training a small language model.

## Learning goals

By the end of this sequence, you should be able to:

- understand basic probability distributions used in language modeling
- build intuition for n-gram models
- compare classical language models with transformer-based approaches
- prepare a training dataset for a small language model
- train and inspect a small language model workflow

## Notebook guide

### 1. Create Your Own Probability Distribution

File: `gdm_lab_1_1_create_your_own_probability_distribution.ipynb`

Focus:
- probability distributions
- sampling intuition
- foundational concepts used later in language modeling

### 2. Experiment with N-Gram Models

File: `gdm_lab_1_2_experiment_with_n_gram_models.ipynb`

Focus:
- token sequence modeling with n-grams
- how context length changes predictions
- practical limitations of simple statistical language models

### 3. Compare N-Gram Models and Transformer Language Models

File: `gdm_lab_1_3_compare_n_gram_models_and_transformer_language_models.ipynb`

Focus:
- differences between classical and transformer-based language models
- how model architecture affects context handling and output quality
- building conceptual bridges before training a model

### 4. Prepare the Dataset for Training an SLM

File: `gdm_lab_1_4_prepare_the_dataset_for_training_a_slm.ipynb`

Focus:
- cleaning and structuring text data
- preparing inputs for training
- understanding why data quality strongly affects model behavior

### 5. Train Your Own Small Language Model

File: `gdm_lab_1_5_train_your_own_small_language_model.ipynb`

Focus:
- model training workflow
- use of `tensorflow` and `keras`
- connecting earlier lessons into a practical end-to-end lab

## Suggested order

Run the notebooks in numeric order because each one builds on ideas introduced earlier in the sequence.

## Setup notes

These notebooks appear to use:

- Python
- Jupyter Notebook or Google Colab
- `pandas`
- `tensorflow`
- `keras`
- helper utilities from `ai_foundations`

If a notebook fails on missing packages, install the dependency in the same environment before continuing.

## Good next improvements

- Add a short summary section after completing each notebook.
- Track your questions, mistakes, and follow-up experiments.
- Add screenshots or output samples once you start customizing the labs.
