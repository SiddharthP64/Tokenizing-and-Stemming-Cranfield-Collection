//IR Assignment 1 Feb 23 2015
//Siddharth Perumal
//sxp132830

The command to run the program on CS2 linux server :
javac IRassignment.java
java IRassignment

Please find attached the screen shot of the run on CS2 server attached. This is without storing the ouput in a file. The submitted code now outputs the data into a file named "Output.txt" in the same path as the source code.
The runtime of the program is displayed at the end of the program.
As for handling of cases, all the words have been converted to lower case before storing them in the hash map.
Words with dashes have been split into two and stored as separate words.
Words which have possessives are trimmed to remove the "'s" and then stored.
The acronyms are stored without any punctuation as a single word.

The main data structure used for the program is Hash map for storing the words. The words are stored as key while the frequency/occurrence are stored as values.
To find the top thirty values, tree map was used with a custom comparator to sort the map based on values.

The path to the Cranfield files in University server is hard coded as per the given project document. The user can also give it at runtime as an argument to change the path if need be.

The command to run the program with path as argument is :
javac IRassignment.java
java IRassignment path_to_files