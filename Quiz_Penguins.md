### Quiz Question:
You are working with the penguin dataset and identified missing values using the following command:

```python
print(penguins.isnull().sum())
```
output will be 
```python 
species              0
island               0
bill_length_mm       2
bill_depth_mm        2
flipper_length_mm    2
body_mass_g          2
sex                 10
dtype: int64
```

You can get new dataset that all the missing is row will be removed 
```python
# Drop rows with missing values
penguins_clean = penguins.dropna()
```

Question: Assume the dataset has 344 rows before cleaning, and a total of 18 missing values have been identified. If you decide to drop all rows with at least one missing value, what is the maximum number of rows that can be removed?
Answer Choices:

    A) 18
    B) 10
    C) 6
    D) 8 

