# Football-Prediction
AISC2011-Data Science Project Management And Requirement Gathering

# Note

* when you try to push large file make sure to command git LFS otherwise it wont work

# How to Read .pkl file in pandas (Exapmle)

```python

import pandas as pd

df = pd.read_pickle("./merged_all_table.csv.pkl", compression='bz2')

df


```