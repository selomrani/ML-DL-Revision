# ML-DL-Revision

Revision project for the Data Science / Machine Learning / Deep Learning track,
built from [`docs/Challenges.pdf`](docs/Challenges.pdf).

All data challenges use a single dataset: **Titanic** (`sns.load_dataset('titanic')`).
One dataset, 7 challenges, each step building on the previous one.

> Course rule: a challenge is only validated when you can explain every line of
> code you wrote.

## Structure

| Folder | Contents |
|---|---|
| `docs/` | Source brief (`Challenges.pdf`) |
| `data/` | Raw and processed datasets, shared by all notebooks |
| `data_challenges/` | Challenges 1-6: NumPy, Pandas, Visualisation, EDA, Cleaning, Transformation |
| `ml_challenges/` | Challenge 7: ML classification |
| `deep_learning/` | Scaffold only - no source material yet |

## Challenges

### Data

- [ ] [1. NumPy](data_challenges/01_numpy/01_numpy_challenge.ipynb)
- [ ] [2. Pandas](data_challenges/02_pandas/02_pandas_challenge.ipynb)
- [ ] [3. Visualisation](data_challenges/03_visualisation/03_visualisation_challenge.ipynb)
- [ ] [4. EDA](data_challenges/04_eda/04_eda_challenge.ipynb)
- [ ] [5. Cleaning](data_challenges/05_cleaning/05_cleaning_challenge.ipynb)
- [ ] [6. Transformation](data_challenges/06_transformation/06_transformation_challenge.ipynb)

### Machine Learning

- [ ] [7. Classification](ml_challenges/07_classification/07_classification_challenge.ipynb)

### Deep Learning

- [ ] Pending material (see `deep_learning/`)

## Conventions

- One notebook per challenge, named `<number>_<topic>_challenge.ipynb`.
- Figures and exports go in that challenge's `outputs/` folder.
- `data/raw/` is read-only: never edit or overwrite the source dataset.
- Cleaned data goes to `data/processed/`.
- No code is stored in this scaffold yet; notebooks are empty placeholders.
