# Exam-2-Program-cpp

Modify arrtemp.cpp by removing the preassignment of the data for each array and by adding five new function templates.

The first new function template should allow the user to enter the array data from the keyboard.

The second new function template should print the second largest value for an array without sorting. You may assume that each array contains distinct data, that is no duplicates.

The third new function template should sort the array data in ascending order.

The fourth new function template should save the array data to a text file.

The fifth new function template should retrieve the array data from the text file.

Output should include the second largest value for each array along with all three arrays being printed out in ascending order twice, once before the text file is saved and once after the array is retrieved from the text file. (Warning - make sure to include the line: template before each function template.)

Each array should be saved to a separate text file.

You will also need to show all three text files which you can do from any text editor when submitting this program. 
----------------------------------------------------------------------------------------------------------------------
Note from Kelvin:

Two ways to import code if you don't know by now. 

1. "Add > New item" create a new .cpp file and then copy/paste the code itself. 
2. Download the .cpp file and then "Add > Existing Item" and choose the file. 
 ---------------------------------------------------------------------------------------------------------------------
Other notes from class:
kill the preassignments of the arrays.

for 1, set up a for loop. function: loadarray() you can specify to user which types to type cout << "enter a value" , cin >> a[i]; 

for 2, how do do w/o sorting? "I dunno". 
you better have three text files. 
cpp to loook at file1, file2, file3

secondbig(a, n1)
secondbig(b, n2)
secondbig(c, n3)
sort(a, n1)
sort(b, n2)
sort(c, n3)
printarra(a, n1)
printarra(b, n2)
printarra(c, n3)
savetext(a, n1)
savetext(b, n2)
savetext(c, n3)
retrievetext (etc)

cout << "after retrieval from text files"
printarray (etc)
