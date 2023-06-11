# Football-Prediction
AISC2011-Data Science Project Management And Requirement Gathering

* A reference table was then built converting loacation (x, y) to actual position in court. The Wikipedia article "Association football positions" was applied as reference.

![football](https://i.pinimg.com/236x/3b/6a/5b/3b6a5ba3b4cf4cb57c149374b341b54f--u-soccer-drills-soccer-tips.jpg)

# Note

* when you try to push large file make sure to command git LFS otherwise it wont work

# How to Read .pkl file in pandas (Exapmle)

```python

import pandas as pd

df = pd.read_pickle("./merged_all_table.csv.pkl", compression='bz2')

df


```