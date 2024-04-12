# North Carolina Crime Dataset

This repository contains the North Carolina Crime Dataset, designed for use with the Hugging Face Datasets library. This dataset provides detailed information about crime statistics across various counties in North Carolina.

## Dataset Description

The North Carolina Crime Dataset includes data on different types of crimes reported in various counties throughout the state. The data spans several years and includes information such as the type of crime, date and time of occurrence, and geographical details.

### Columns

The dataset includes the following columns:
- `Crime_Type`: The type of crime (e.g., Theft, Assault).
- `Date`: The date on which the crime occurred.
- `Time`: The time at which the crime occurred.
- `County`: The county in which the crime was reported.
- `Latitude`: The latitude coordinate of the crime scene.
- `Longitude`: The longitude coordinate of the crime scene.

## Accessing the Dataset

You can access the dataset through the Hugging Face Datasets library. To do so, use the following code:

```python
from datasets import load_dataset

dataset = load_dataset("zwn22/NC_Crime")
