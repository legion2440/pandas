# Pandas

Minimal audit-oriented solution for the 01-edu `pandas` subject.

Structure:

- `requirements.txt` for the environment from `ex00`
- `ex00/ex00.ipynb` environment and import checks
- `ex01/ex01.ipynb` DataFrame creation from NumPy array and Pandas Series
- `ex02/ex02.ipynb` electric power consumption manipulations
- `ex03/ex03.ipynb` e-commerce purchases answers
- `ex04/ex04.ipynb` missing-values handling

Notes:

- The notebooks are written with Pandas-first solutions.
- Each notebook prefers local files from `data/` when they are present.
- If `data/` is empty, the notebooks fall back to the original subject sources.

Run locally:

```bash
python -m pip install -r requirements.txt
python -m jupyter nbconvert --execute --inplace ex00/ex00.ipynb
python -m jupyter nbconvert --execute --inplace ex01/ex01.ipynb
python -m jupyter nbconvert --execute --inplace ex02/ex02.ipynb
python -m jupyter nbconvert --execute --inplace ex03/ex03.ipynb
python -m jupyter nbconvert --execute --inplace ex04/ex04.ipynb
```
