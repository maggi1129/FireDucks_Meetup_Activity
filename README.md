<a href="https://colab.research.google.com/github/maggi1129/FireDucks_Meetup_Activity/blob/main/FireDucksActivity_withFireDucks.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab - FireDucks Version"/></a>

# 🦆 FireDucks Meetup Notebook Exercises

This repository hosts **two** complementary Jupyter Notebooks that walk you through **five** common data analysis tasks on a large Parquet dataset:

1. **Pandas Version** (`FireDucksActivity_pandas.ipynb`): Complete each exercise using standard **pandas**, observing runtimes and correctness.  
2. **FireDucks Version** (`FireDucksActivity_withFireDucks.ipynb`): Rerun the same questions with **FireDucks**’ line magic to compare performance gains with minimal code changes.

---

## 📓 Notebook Content

- **`FireDucksActivity_pandas.ipynb`** covers:
  1. Loading and inspecting a large Parquet dataset  
  2. Cleaning and transforming time-based data  
  3. Aggregations and grouping operations  
  4. Merging and joining datasets  
  5. Tracking runtime metrics with `time` and `%time`

- **`FireDucksActivity_withFireDucks.ipynb`** mirrors the steps above but starts with:
  ```python
  %load_ext fireducks #required for jupyter notebook
  import fireducks.pandas as pd

to demonstrate how FireDucks accelerates large-data operations out of the box.

## 🚀 Quick Start

- Google Colab: Click the corresponding badge above.

## ✍️ Exercise Workflow
- Run the Pandas version first

- Execute each cell, observe outputs and timing.

- Switch to the FireDucks version

- Make sure you have import fireducks.pandas as pd.

- Rerun the same cells to compare runtimes side by side.

Enhance your understanding of both the classic pandas API and FireDucks’ performance benefits.

## ⚖️ License
This project is licensed under the MIT License. 

