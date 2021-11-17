To compile the C++ file

g++ -std=c++11 -O2 -Wall test.cpp -o test


##Tricks 

<----------- To make fast Input and output in C++ ----------------------->

Input and output is sometimes a bottleneck in the program. The following lines at the
code make input and output more efficient.

ios::sync_with_stdio(0);
cin.tie(0);


<--------------------------------------------------------------------------->

<-------------- Reading string with spaces in C++ ------------------------->

Sometime the program should read a whole line from the input, possibly containg spaces
. This can be accomplished by using the getline function.

string s;
getline(cin, s);

<-------------------------------------------------------------------------->