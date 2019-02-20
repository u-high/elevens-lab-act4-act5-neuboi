# Elevens-Lab-Act4-Act5

<H2> Activity 4 Questions </H2>

1. Write a static method named `flip` that simulates a flip of a weighted coin by returning either
"`heads`" or "`tails`" each time it is called. The coin is twice as likely to turn up heads as tails.
Thus, `flip` should return "`heads`" about twice as often as it returns "`tails.`"






1. Write a static method named `arePermutations` that, given two `int` arrays of the same length
but with no duplicate elements, returns `true` if one array is a permutation of the other (i.e., the
arrays differ only in how their contents are arranged). Otherwise, it should return `false`.






1. Suppose that the initial contents of the `values` array in `Shuffler.java` are {1, 2, 3,
4}. For what sequence of random integers would the efficient selection shuffle change `values` to
contain {4, 3, 2, 1}?





1. How many shuffles of the perfect shuffle algorithm does it take for the deck to be as it started again (in the original order)?  Does this work for any size deck?  Does the number of shuffles needed for different sized decks change?



<H2> Activity 5 Questions </H2>

_*Buggy1:*_  

* Constructor or Method (write method name):
* Describe a Possible Code Error:

Method - isEmpty()
It is possible that the method swaps boolean values for the detection (method returns 
False for an empty deck instead of true and vice versa)

_*Buggy2:*_
  * Constructor or Method (write method name):
  * Describe a Possible Code Error:

Method - size()
Programmer most likely failed to create a proper sized deck.

_*Buggy3:*_

* Constructor or Method (write method name):
* Describe a Possible Code Error:

Method-matches()
Matches most likely has reversed boolean expressions. for matches, with the error, if the 
Cards don't match, it is true; this contradicts !allMatch


_*Buggy4:*_

* Constructor or Method (write method name):
* Describe a Possible Code Error:

Method - deal()
There is something wrong with the deal method. It probably does not deal the card in the correct array index or deals a reference variable deck in the method without altering the user's deck
