# Azure Data Factory Data Flow Transformations

* [Video: Clean Addresses with Derived Columns](https://www.youtube.com/watch?v=axEYbuU3lmw)

## Derived Column

Use the Derived Column transformation to generate new columns in your data flow or to modify existing incoming data columns. Use the ADF Data Flow Expression Language to describe the column transformations in the Expression Builder: https://aka.ms/dataflowexpressions.

![derive column](../images/dc1.png "Derived Column")

You can perform multiple Derived Column actions in a single Derived Column transformation. Click "Add Column" to transform more than 1 column in the single transformation step.

In the Column field, either select an existing column to overwrite with a new derived value, or click "Create New Column" to generate a new column with the newly derived value.

The Expression text box will open the Expression Builder where you can build the expression for the derived columns using expression functions.
