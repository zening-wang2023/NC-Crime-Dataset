# North Carolina Crime Dataset

This repository contains the North Carolina Crime Dataset, designed for use with the Hugging Face Datasets library. This dataset provides detailed information about crime statistics across various counties in North Carolina.

## Accessing the Dataset

You can access the dataset through the Hugging Face Datasets library. To do so, use the following code:

```python
from datasets import load_dataset

dataset = load_dataset("zwn22/NC_Crime")
