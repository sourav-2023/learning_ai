# learning_ai

A curated repository of AI learning notes, hands-on notebooks, and small experiments.

## What this repo contains

This repository currently focuses on a first course sequence about language modeling fundamentals. The notebooks move from simple probability distributions to n-gram models, dataset preparation, and training a small language model.

## Repository structure

- `course_1/`: a notebook-based learning path covering probability distributions, n-gram models, dataset preparation, and small language model training.
- `requirements.txt`: common local dependencies for the current notebook set.
- `.gitignore`: keeps notebook checkpoints and local environment files out of version control.

## Current learning path

### Course 1: Language modeling foundations

Start with the notebooks in order:

1. `gdm_lab_1_1_create_your_own_probability_distribution.ipynb`
2. `gdm_lab_1_2_experiment_with_n_gram_models.ipynb`
3. `gdm_lab_1_3_compare_n_gram_models_and_transformer_language_models.ipynb`
4. `gdm_lab_1_4_prepare_the_dataset_for_training_a_slm.ipynb`
5. `gdm_lab_1_5_train_your_own_small_language_model.ipynb`

See [course_1/README.md](./course_1/README.md) for notebook-by-notebook details.

## Setup

### Option 1: Google Colab

This is the easiest path for the current notebooks, especially because some notebooks install extra dependencies directly inside the notebook.

### Option 2: Local Jupyter environment

1. Create and activate a virtual environment.
2. Install the shared dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter.
4. Leave the notebook install cells enabled, because they install the `ai_foundations` package and a few notebook-specific extras.

## Environment notes

The notebooks use Python 3 and rely on packages such as:

- `pandas`
- `ipython`
- `tensorflow`
- `keras`
- `ai_foundations`

Notebook `1_3` also installs extra JAX and checkpointing dependencies inside the notebook itself. Notebook `1_5` uses Keras with a JAX backend, so Colab is likely to be the smoothest way to run the full sequence.

## Recommended workflow

- Read each notebook in sequence.
- Run cells and keep your own notes on observations, errors, and experiments.
- Use this repo to track what you learned, not just what you copied.
- Add new courses as separate folders with their own README files for consistency.

## Improvement ideas

- Add short reflection notes after each notebook.
- Add screenshots or output samples once you start customizing the labs.
- Split future courses into separate folders like `course_2/`, `vision/`, or `agents/`.
- Add a progress tracker if you want this repo to become your public learning log.
