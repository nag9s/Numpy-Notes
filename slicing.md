[https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/](https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/)

The iloc indexer syntax is data.iloc\[&lt;row selection&gt;, &lt;column selection&gt;\], which is sure to be a source of confusion for R users. “iloc” in pandas is used to select rows and columns by number, in the order that they appear in the data frame. You can imagine that each row has a row number from 0 to the total rows \(data.shape\[0\]\)  and iloc\[\] allows selections based on these numbers. The same applies for columns \(ranging from 0 to data.shape\[1\] \)

[https://gist.github.com/shanealynn/1efd0555a0a668b5f0e3f5fa5593c673\#file-pandas-index-single-iloc-selections-py](https://gist.github.com/shanealynn/1efd0555a0a668b5f0e3f5fa5593c673#file-pandas-index-single-iloc-selections-py)

![](/assets/import.png)

Multiple columns and rows can be selected together using the .iloc indexer.[https://gist.github.com/shanealynn/3cd4c410ca1514dd9575443ab1b08a06\#file-pandas-index-multi-iloc-selections-py](https://gist.github.com/shanealynn/3cd4c410ca1514dd9575443ab1b08a06#file-pandas-index-multi-iloc-selections-py)

![](/assets/import1.png)





![](/assets/import3.png)

