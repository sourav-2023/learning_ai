# learning_ai

A curated repository of AI learning notes, hands-on notebooks, and small experiments.

## What this repo contains

This repository currently focuses on a first course sequence about language modeling fundamentals. The notebooks move from simple probability distributions to training a small language model, making the repo useful both as a study log and as a practical reference.

## Repository structure

- `course_1/`: a notebook-based learning path covering probability distributions, n-gram models, dataset preparation, and small language model training.

## Current learning path

### Course 1: Language modeling foundations

Start with the notebooks in order:

1. `gdm_lab_1_1_create_your_own_probability_distribution.ipynb`
2. `gdm_lab_1_2_experiment_with_n_gram_models.ipynb`
3. `gdm_lab_1_3_compare_n_gram_models_and_transformer_language_models.ipynb`
4. `gdm_lab_1_4_prepare_the_dataset_for_training_a_slm.ipynb`
5. `gdm_lab_1_5_train_your_own_small_language_model.ipynb`

See [course_1/README.md](./course_1/README.md) for notebook-by-notebook details.

## Recommended workflow

- Read each notebook in sequence.
- Run cells and keep your own notes on observations, errors, and experiments.
- Use this repo to track what you learned, not just what you copied.
- Add new courses as separate folders with their own README files for consistency.

## Environment notes

The current notebooks use Python and rely on common data and notebook tooling such as `pandas`, `tensorflow`, `keras`, and course-specific helpers from `ai_foundations`.

A Jupyter or Colab workflow is the easiest way to run them.

## Improvement ideas

- Add a `requirements.txt` or environment file once the dependency set stabilizes.
- Add short reflection notes after each notebook.
- Split future courses into separate folders like `course_2/`, `vision/`, or `agents/`.
