# Pandas-Query-Research
Exploring the query modules in pandas



Pandas library in Python is one of the most common and effective way of filtering data. A big advantage would be that the codes are short, readable and easily understood.

query() is a function in Pandas that is used when we have a condition to apply on a dataset.

If you want a certain set of values that meet a condition, we use query(). If you want to apply a condition only after selecting certain values, you can still use only query().

In query() method, we can directly make selection even by specifying indices. If you want to select those indices (say) lesser than value in column. 
There is no need to reset the index in the dataset as a column for the condition to be applied. We use query().

For a regular pandas user, perfecting a query module has the advantage that one could use it as a replacement for other filtering and thresholding functions where the syntactic complexity and variation is higher.
I try to explore and demonstrate some of this in the enclosed Jupyter notebook.   