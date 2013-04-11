CSV2LaTeX
=========

The CSV2LaTeX module converts .csv files so that they can be directly input into the LaTeX tabular environment. It can be used in one of two ways: 

1. Import the module and call the csv2latex function: 

ex. You want to convert the file Table.csv:

	import csv2latex

	csv.csv2latex("Table")

Now, there should be a file called "Table.txt" in your folder ready to be put into LaTeX. 

2. From the command line, call the csv2latex.py script with the desired tables as extra arguments:

ex. You want to convert the file Table1.csv and Table2.csv:

	python csv2latex.py Table1 Table2
	
Now, there should be files of the form "Table1.txt" and "Table2.txt" in your folder ready to be put in LaTeX.	
