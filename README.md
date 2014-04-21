CSV2LaTeX
=========

The CSV2LaTeX script converts .csv files to a format that is directly readable by the LaTeX tabular environment. It can be used in two ways: 

1. Import the module and call the csv2latex function: 

ex. You want to convert the file Table.csv:

	import csv2latex

	csv.csv2latex("Table")

There will now be a file "Table.txt" in your current directory ready to be included in LaTeX. 

2. From the command line, call the csv2latex script with the desired tables as extra arguments:

ex. You want to convert the file Table1.csv and Table2.csv:

	./csv2latex Table1 Table2
	
Now, there should be files of the form "Table1.txt" and "Table2.txt" in your folder ready to be put in LaTeX.	
