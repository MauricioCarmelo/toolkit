# Machine Learning
Toolkit of useful algorithms to be used in machine learning applications

## Usage

**Example of how to use loadCSV() within a program**

```python
 sheet, attributes, instances = loadCSV('input.csv')

 print 'Loaded sheet within a dictionary:'
 for key in sheet.keys():
 	print sheet[key]
```

**Example of how to use KNN() within a program**
```python
point = [0.3, 0.7]
kTests = [1, 3, 5, 7] # different tests with different K numbers
results = KNN('input.csv', point, kTests)
print results
```