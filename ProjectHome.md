# What is ACS? #
All Common Subsequence (ACS) is a variation of the classical [Longest common Subsequence (LCS)](http://en.wikipedia.org/wiki/Longest_common_subsequence_problem) problem, where all the common subsequences have to be computed.

[More on Subquences](http://en.wikipedia.org/wiki/Subsequence)
# What our project does #
In this project we implement an efficient C++ implementation of the ACS problem. Both the variations of the problem:
  * compute all the common subsequences
  * compute common subsequences with length ≥ a critical length
Of course the first variation is just a special case of the latter variation, but we have seperated them for the purpose of clarity. Besides we propose different algorithms for each of the variations.