
# Parallel Python programming
By default, Python uses a single CPU with one thread to execute your task, 
which fails to take much advantage over modern multi-processor and multi-threading-enabled computers.
This tutorial will guide you through several ways to more effectively utilize your laptop, 
workstation, or even computer clusters for parallel Python tasks.

## What is multiprocessing
First of all, you should understand the basic concept of 
[multiprocessing](https://www.geeksforgeeks.org/multiprocessing-python-set-1/).
It might also be helpful to know a bit about 
[multithreading](https://www.geeksforgeeks.org/multithreading-python-set-1/)
and their 
[differences](https://www.geeksforgeeks.org/difference-between-multiprocessing-and-multithreading/) 
in case of confusion.
Video tutorials can be found here in 
[link1](https://www.youtube.com/watch?v=fKl2JW_qrso)
and
[link1](https://www.youtube.com/watch?v=IEEhzQoKtQU).
This guide will be focused on multiprocessing.

## Native multiprocessing package
Python provides a native [package](https://docs.python.org/3/library/multiprocessing.html)
for multiprocessing.
For beginners, it is highly recommended to start from using the `Pool` class.
Particularly, if you want to parallelize your
pandas workflow for data processing,
[this tutorial](http://www.racketracer.com/2016/07/06/pandas-in-parallel/) 
would be helpful.
Other useful resources can be found here at
[link1](https://data-flair.training/blogs/python-multiprocessing/),
[link2](https://sebastianraschka.com/Articles/2014_multiprocessing.html),
and [link3](https://stackoverflow.com/questions/7207309/python-how-can-i-run-python-functions-in-parallel).


## MPI for Python
If you are familiar with parallel programming using compiled languages (e.g. C++, Fortran, etc.),
take a look at [MPI for Python](https://mpi4py.readthedocs.io/en/stable/overview.html)
a powerful package to deploy your Python program to a computer cluster (e.g. NU Quest).
Relevant tutorials can be found through
[link1](https://rabernat.github.io/research_computing/parallel-programming-with-mpi-for-python.html)
and
[link2](https://research.computing.yale.edu/sites/default/files/files/mpi4py.pdf).


## Scale-up data analytics using Apache Spark
Python is a popular language for big data-processing tasks 
(e.g. [pandas](https://pandas.pydata.org/)),
however, these analytical packages are not design to scale beyond a single machine.
[Apache Spark](https://spark.apache.org/)
could come to rescue.
Spark would allow you to make some minor changes to your existing 
Python workflow yet significantly speed up the processing time.
More hands-on information can be found at
[link1](https://www.datacamp.com/community/tutorials/apache-spark-python)
and
[link2](https://www.dezyre.com/apache-spark-tutorial/pyspark-tutorial).


## Using Dask
A light-weighted distributed Python computing package
[Dask](https://docs.dask.org/en/latest/)
is also a great choice if your Python program has its own 
ecosystem, Dask would easily adapt itself to your environment.
The difference between Dask and Spark can be found
[here](https://docs.dask.org/en/latest/spark.html).
A nice tutorials is available at this
[link](https://medium.com/@gongsta/dask-an-introduction-and-tutorial-b42f901bcff5).


## Stuck?
If you have a parallel Python question, 
don’t know what resource to start with, or need to learn something not covered above, 
remember you can always request a free consultation with our data science consultants. 
We’re more than happy to answer questions and point you in the right direction.


