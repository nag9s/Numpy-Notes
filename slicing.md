### **Indexing**

[https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/](https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/)

The iloc indexer syntax is data.iloc\[&lt;row selection&gt;, &lt;column selection&gt;\], which is sure to be a source of confusion for R users. “iloc” in pandas is used to select rows and columns by number, in the order that they appear in the data frame. You can imagine that each row has a row number from 0 to the total rows \(data.shape\[0\]\)  and iloc\[\] allows selections based on these numbers. The same applies for columns \(ranging from 0 to data.shape\[1\] \)

[https://gist.github.com/shanealynn/1efd0555a0a668b5f0e3f5fa5593c673\#file-pandas-index-single-iloc-selections-py](https://gist.github.com/shanealynn/1efd0555a0a668b5f0e3f5fa5593c673#file-pandas-index-single-iloc-selections-py)

![](/assets/import.png)

Multiple columns and rows can be selected together using the .iloc indexer.[https://gist.github.com/shanealynn/3cd4c410ca1514dd9575443ab1b08a06\#file-pandas-index-multi-iloc-selections-py](https://gist.github.com/shanealynn/3cd4c410ca1514dd9575443ab1b08a06#file-pandas-index-multi-iloc-selections-py)

![](/assets/import1.png)

[http://www.pythoninformer.com/python-libraries/numpy/index-and-slice/](http://www.pythoninformer.com/python-libraries/numpy/index-and-slice/)

nice examples for 3d arrays

![](/assets/import3.png)

[https://machinelearningmastery.com/index-slice-reshape-numpy-arrays-machine-learning-python/](https://machinelearningmastery.com/index-slice-reshape-numpy-arrays-machine-learning-python/)

Indexing two-dimensional data is similar to indexing one-dimensional data, except that a comma is used to separate the index for each dimension.

## **Slicing**

[https://machinelearningmastery.com/index-slice-reshape-numpy-arrays-machine-learning-python/](#)

### Two-Dimensional Slicing

Let’s look at the two examples of two-dimensional slicing you are most likely to use in machine learning.

#### Split Input and Output Features

It is common to split your loaded data into input variables \(X\) and the output variable \(y\).

We can do this by slicing all rows and all columns up to, but before the last column, then separately indexing the last column.

For the input features, we can select all rows and all columns except the last one by specifying ‘:’ for in the rows index, and :-1 in the columns index.

### 

[http://structure.usc.edu/numarray/node26.html](http://structure.usc.edu/numarray/node26.html)

### Michael Heydt - Learning Pandas-Packt Publishing \(2015\)

Slicing overloads the normal array \[\] operator to accept what is referred to as a slice

object. A slice object is created using a syntax of start:end:step. Each component

of the slice is optional and, as we will see, this provides convenient means to select

entire rows or columns by omitting the component of the slice.

To the left of the comma is a slice object for the rows, and to the right is one for the

columns. The following code selects columns in position 2 through 3 of the matrix:

![](/assets/import4.png)

## Curtis Miller - Hands-On Data Analysis with NumPy and pandas-Packt Publishing \(2016\)

![](/assets/import5.png)

