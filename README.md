This is the full implementation of a recursive assembly program. To run assembly, I am using the Harvey Mudd Miniature Machine (hmmm). I have included both .hmmm extensions \
to run the program through your command line, and .txt extension to simply view the file. The problem goes as follows:

You start with n teddy bears (these will be given as an input from the user).
#At each step of the game, a number of bears may be given away based on the the following rules...

1) If n is even, exactly n/2 bears may be given away
2) If n is divisible by 3 or 4, then the number of bears from multiplying the last two digits may be given away...
exactly (n%10) * ((n%100)/10) bears may be given away (there is an edge case here where we skip the rule if the number to be given away is 0)
3) If n is divisible by 5, then exactly 42 bears may be given away

By following these rules, can you end with exactly 42 bears?
