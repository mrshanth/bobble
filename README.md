# scrabbler

###Clarification
In the given README file, sample output given for the first question had letter ```h``` ,  even though the input, ```abcdefg``` did not have it:
+ ache
+ chafed

###Assumption
I concluded that, this might be a typo and proceeded with the following assumptions:

1. Output words should not have letters, which were not part of the input string
2. Output words should not have a letter more than the number of times specified in the input string. For example:
   Input ```abcdef``` cannot have ```bee``` as one of the output

###Documents
The following files are part of the solution. 

+ scrabbler.py
+ scrabbler_for_test.py
+ unit_test_scrabbler.py

###How to
1. Please use ```scrabbler.py``` to get the outputs as described in the problem statement README file.  
2. ```scrabbler_for_test.py``` was created, so that the functions can return values to do unit testing. In ```scrabbler.py```, few functions print the output directly instead of storing.
3. ```unit_test_scrabbler.py``` can be run from the command line as: ``` python3 unit_test_scrabbler.py```

Note:
If assumption 2 is wrong, I have prepared a solution for that scenario as well and I can share it if required.

Thanks for the opportunity

. 



