Challenge: FooBarBaz

Objective: Write a program that prints numbers from 1 to 100 (inclusive) with the following modifications:

For numbers divisible by 2: Instead of the number, print "Foo".
For numbers divisible by 3: Instead of the number, print "Bar".

For numbers divisible by 5: Instead of the number, print "Baz".

For numbers divisible by more than one of these: Print a concatenation of the appropriate words in the following order:

Divisible by 2 and 3: Print "FooBar".

Divisible by 2 and 5: Print "FooBaz".

Divisible by 3 and 5: Print "BarBaz".

Divisible by 2, 3, and 5: Print "FooBarBaz".

For numbers that don’t meet any of these conditions: Simply print the number.
Example output:
1
Foo
Bar
Foo
Baz
FooBar
7
Foo
Bar
FooBaz
11
FooBar
13
Foo
BarBaz
Foo
17
...
Extra Challenge: After you complete the basic version:

Modify your program so that it takes an upper limit (e.g., 1 to N) from the user instead of always 100.

Experiment with different divisibility rules (e.g., add a check for numbers divisible by 7).
