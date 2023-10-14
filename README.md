# Data Science Snippets
Data Science Snippets for R | python | SQL | Excel | Bash

## Drop a column
### Python
```python
df = df.drop("col1", axis = 1)
```
### R
```R
df = df |> select(-col1)
df$col1 <- NA
```
