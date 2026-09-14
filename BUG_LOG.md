# Bug Log

**Name:** _Brandon Langehennig_

Fill in one row for every bug you find and fix in `Program.cs`. There are
**33 bugs**: 12 syntax, 5 runtime, 16 logic. Keep the rows in line-number order
if you can.

**Kind** must be one of: `Syntax`, `Runtime`, `Logic`.

The first row is a worked example of the level of detail expected (it is **not** one of the 33 bugs).

| # | Section | Line | Kind | What was wrong | How I fixed it |
1 # |Section 1| |Line 32| |Syntax Error| |There was a quotation mark missing at the end of crewName +| |I added a semi colon to the end of crewName +|
2 #|Section 2| |Line 56| |Syntax Error| |Parentheses missing after Console.ReadLine| |I added them in.|
3 #|Section 3| |Line 97| |Syntax Error| |I in int was uppercase| |changed the I in int to a lowercase i|
4 #|Section 3| |Line 106| |Syntax Error| |there was only 1 = sign between the two variables being compared| | i added a equal sign to make it a bool statement|
5 #|Section 5| |Line 184| |Syntax Error| |Typo in totalFuel| | changed totalFule to totalFuel|
6 #|Section 6| |Line 201| |Syntax Error| |int packPrice = 0 was missing a semi colon at the end| |changed it to int packPrice = 0;
7 #|Section 6| |Line 217| |Syntax Error| | equal sign missing between finalTotal and + 5| |added the equal sign to the middle of finalTotal and + 5|
8 #|Section 7| |Line 241| |Syntax Error| |parantheses missing after while statement| added parentheses
9 #|Section 9| |Line 263| |Syntax Error| |commas were used where semi colons were suppose to be| |changed commas to semi colons|
10 #|Section 10| |Line 285| |Syntax Error| |Console.WriteLine statement used single quotes| |changed them to double quotes|
11 #|Section 10| |Line 292| |Syntax Error| |there was only one curly braket and it wasn't enclosing the else Console.WriteLine statements| |deleted the curly braket and then added the right ones enclosing the else result
12 #|Section 12| |Line 329| |Syntax Error| |the l of line in Console.WriteLine was lowercase| I made the l uppercase
13 #|Section 1| |Line 35| |Run Time Error| |crewName in index is [0],[1],[2],[3],[etc.] whereas crewName.Length is [1],[2],[3],[4],[etc.] so they were two different values| |to fix it I entered -1 at the end of crewName.Length in order to make the two values the same
14 #|Section 2| |Line 57| |Run Time Error| |wrong variable in parentheses| |changed variable from crewName to ageInput in order for it to mach up with the string
15 #|Section 4| |Line 143| |Run Time Error| |
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33

## Reflection (a few sentences)

Which bug took you the longest to find, and why?

Which kind of bug (syntax, runtime, logic) do you think is the hardest to catch? Why?
