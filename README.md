# Algorithm-Analysis

Lab 1:
 a recursive function stackystr to generate and print all stacky strings of a given parametern, andalso to return their count. You start with an empty string T, 
 and then recursively keep on adding newsymbols at the end of T. Appending of+is allowed if and only if the current number of plus symbols inTis<n, whereas appending
 of - is allowed if and only if T currently contains more plus symbols than minus symbols. For each allowed appending, make a recursive call on the appended T.
 To compile: gcc -o lab1 lab1.c
 
 Lab 2:
 A series of 4 games that utilize the black box containing 4 secret integers a1,a2,a3, and a4. There are four games that are played in order to figure out the integer values, and each game is allowed to make integer valued guessing queries to the black box to return the values.
 
 Sample output for the blackbox game:
 +++ Game 1
 a1 = 64965365
 Time taken = 0.524319 sec
 ***Yep! Your guess is correct.
 +++Game 2
 a2 = 78161829
 Time taken = 1.295109 sec
 ***Yep! Your guess is correct.
 +++ Game 3
 a3 = 4633204
 Time taken = 0.000002 sec
 ***Yep! Your guess is correct.
 +++ Game 4
 a4 = 81685977
 Time taken = 0.000001 sec
 ***Yep! Your guess is correct.
 
 Lab3: 
 Part1:Indexed Merge Sort
 Part2:Two-Way Indexed QuickSort 
 
 Compile and run with the following commands
 $gcc -no-pie lab3.c blackbox2.o -o lab3
 $./lab3
 Sample output of lab3-   
 +++ Sorting the balls...  
 Number of black-box queries = 18664720
 *** Great!  You cracked it.
 
 +++ Finding the matching boxes: Method 1...          
 Number of black-box queries = 52849826 
 *** Great!  You cracked it.
 
 +++ Finding the matching boxes:  Method 2...        
 Number of black-box queries = 18475732
 *** Great! You cracked it.
