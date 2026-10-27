# P04 --- Module responsibilities

Archit, S24CSEU1049

- **data.py**: Loads the delivery CSV into a table and splits it into training and testing sets.
- **features.py**: Checks and describes a single delivery order, such as its minutes per km, average speed and a readable summary.
- **model.py**: Trains the linear regression model, scores it, and saves and loads it from disk.
- **validate.py**: Decides whether a single order is usable by checking that each value is in its allowed range.
- **__init__.py**: Marks the `delivery` folder as a package and lists the functions it offers for import.
