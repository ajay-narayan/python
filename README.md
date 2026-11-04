# Python Foundations — Learning Archive

A structured archive of the Python and data-library notebooks I worked through while building my foundations (2021–2022).
It's kept public as a record of the learning path; my current, production-style work lives in my [pinned repositories](https://github.com/ajay-narayan).

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)

## Contents

| # | Topic | Notebooks | What's covered |
|---|-------|-----------|----------------|
| 01 | [Basics](01-basics) | 3 | Printing, arithmetic, `input()`, comparison operators, `if/else` (even/odd, positive/negative) |
| 02 | [Strings](02-strings) | 3 | `find` vs `index`, `is*` checks, case methods, `split`/`join`/`partition`/`replace`, factorial |
| 03 | [Lists](03-lists) | 5 | Mutating methods, references vs `copy()`, sorting, `any`/`all`, swap/sum/largest-element programs, sum of squares, prime check |
| 04 | [Tuples](04-tuples) | 2 | Indexing nested tuples, immutability, unpacking, list ↔ tuple conversion |
| 05 | [Sets](05-sets) | 1 | `add`/`update`, subset/superset, union, intersection, difference |
| 06 | [Dictionaries](06-dictionaries) | 1 | Creating, reading, updating and deleting keys |
| 07 | [Bytes](07-bytes) | 1 | `bytes` vs `bytearray`, escaping in string literals |
| 08 | [Patterns](08-patterns) | 1 | Nested loops for pyramid / right-triangle patterns |
| 09 | [NumPy](09-numpy) | 1 | Array creation, slicing, `shape`/`dtype`, reshape, copies, conversion |
| 10 | [pandas](10-pandas) | 1 | `Series`/`DataFrame` creation, datetime indexes, selection, missing values, summary stats |

## Running locally

```bash
git clone https://github.com/ajay-narayan/python.git
cd python
python -m venv .venv && source .venv/bin/activate
pip install jupyter numpy pandas
jupyter notebook
```

> Some cells intentionally demonstrate errors (e.g. `index()` on a missing substring, modifying a tuple) to show how Python behaves.
