Pandas is an open-source Python library used for data manipulation, analysis and cleaning. 

It provides fast and flexible tools to work with tabular data, similar to spreadsheets or SQL tables.



A Series is a one-dimensional labeled array that can hold any data type.

When to use pd.DataFrame()?

Case 1: Creating data manually from scratch
```python
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['NYC', 'London', 'Tokyo']
}
df = pd.DataFrame(data)    # Create from dictionary
```
