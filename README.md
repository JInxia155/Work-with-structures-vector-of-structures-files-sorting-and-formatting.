# Work-with-structures-vector-of-structures-files-sorting-and-formatting.
Work with structures, vector of structures, files, sorting, and formatting.



Download Link : https://programming.engineering/product/work-with-structures-vector-of-structures-files-sorting-and-formatting/

A company keeps its employee records in a file. Each line in the file includes a single employee record (id, first name, last name, & salary). Write a C++ program that prints a report of employee data. You are asked to process the data in the file by storing the records in a vector of structures. Your program must print the following report.

    All employee records sorted by last name.

    Find and print the total payroll.

Start by creating a directory called Lab12 inside your 2400/Labs directory.

Hints:

    Write a function to load the vector of structures (make sure the name is in the right format).

    Write a function to sort the vector by last name. This function can be the selection sort function given in the notes. What do you compare? What do you swap?

    Write a function to print the report. Consider using setw.

    Write a function to calculate and return the total payroll.

Sample input:

1000 George Washington 10000

2000 John Adams 15000

1212 Thomas Jefferson 34000

1313 Abraham Lincoln 45000

1515 Jimmy Carter 78000

1717 George Bush 80000

CS2400
		

Lab 12 (Structures)
		

100 Points

Sample output:
	

Sorted by name
	

ID
	

Name
	

Salary

————————————

2000
	

John Adams
	

$15000.00

1717
	

George Bush
	

$80000.00

1515
	

Jimmy Carter
	

$78000.00

1212
	

Thomas Jefferson
	

$34000.00

1313
	

Abraham Lincoln
	

$45000.00

1000
	

George Washington
	

$10000.00

Total Payroll: $262000.00

Grading:

    10 points, load the vector function

    30 points, sort by name function

    20 points, total payroll function

    20 points, output is displayed as indicated

    20 points, documentations and style

