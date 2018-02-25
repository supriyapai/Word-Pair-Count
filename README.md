# Word-Pair-Count-MapReduce
MapReduce 
Hadoop MapReduce to count pair of words in lines.

In this project, the required output is the count of word pairs in the file. 
NOTE:

Punctuation is NOT considered, so the words "(1991)" and ‘1991’ are the same. Similarly, ‘first-second’ and ‘first second’ are counted as the same pair.
If the line contains a single word, then that becomes the key.
Every word is converted to lowercase i.e. "Every" and "every" are essentially the same word.

e.g. line:

Input:(k,v) = (1,“the cat in the hat is the best cat in the hat”)

Output:(k2,v2) = (“the cat”, 1), (“cat in”,2),(‘in the’,2),(‘the hat’,2’),(‘hat is’,1), etc
