# Spark Optimization Mini Project

This exercise gives you hands-on experience optimizing PySpark code. You’ll look at the
physical plan for the query execution and then modify the query to improve performance.<br/>
<br/>
1. Download the code and the data from here
2. Extract the archive into a folder on your local computer with PySpark setup
3. The file named ‘optimize.py’ contains the code that you need to optimize
For example, we want to compose a query in which we get for each question also the
number of answers to this question for each month. A version of this query exists in the .py
file, but does so in a suboptimal way. Your task is to try to rewrite it and achieve more
optimal performance.
<br/>
<br/>
As you might remember from our spark subunit, there are several ways one can improve
performance of a Spark job:<br/>
<br/>
1. By picking the right operators <br/>
2. Reduce the number of shuffles and the amount of data shuffled <br/>
3. Tuning Resource Allocation<br/><br/>
4. Tuning the Number of Partitions<br/>
5. Reducing the Size of Data Structures<br/>
6. Choosing Data Formats
