Change Maker
============

A simple program which calculates the number of unique coin combinations to arrive at a given amount, given a list of usable denominations.  Run on its own, the program will print the function's return of every coin-combination, and also the number of cominations.  The function takes three parameters:

amount
------
a `float`, intended to be dollar amount but potentially any currency.  Will be multiplied by 100 and floored before being tested by the list of denominations.

denominations
-------------
a list of `int`s representing coin values one may use in determining combinations of ways to make change for the amount

coins_used
----------
a list of every coin-combination (also lists) so far determined to equal the amount, and which is defaulted as `[]`
