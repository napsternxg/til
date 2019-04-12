## Libear algebra for co-occurence counts

If A is (n*m) binary matrix with m columns depicting presence in category and n rows as the number of items. 
Then the co-occurence matrix of categories (m*m) can be found by taking the dot product of A.T and A. 

Source: https://stackoverflow.com/questions/20574257/constructing-a-co-occurrence-matrix-in-python-pandas
To do it for pandas dataframs: 

```python
co_occurence_matrix = df[category_cols].astype("int").T.dot(df[category_cols].astype("int"))
```
