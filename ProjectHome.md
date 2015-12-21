C++ and STL class implementation of the Hungarian algorithm by David Schwarz, 2012

This implementation uses C++ and STL and the O(n^3) variation of the Hungarian implementation. Most of the code is derived from the C implementation, libhungarian by Cyrill Stachniss, 2004. You can find that here http://www.informatik.uni-freiburg.de/~stachnis/misc.html

You can find a tutorial for the implementation here. http://community.topcoder.com/tc?module=Static&d1=tutorials&d2=hungarianAlgorithm

You can also find a more top-level description of the algorithm here:
http://en.wikipedia.org/wiki/Hungarian_algorithm

Notes:

I wrote this class because I couldn't find a C++ style implementation (class, accessible interface, STL) that didn't suffer from an endless loop problem (step 4 to step 6) when cost assignments were equal, and didn't care to debug other people's code. This C implementation is really good but slightly obfuscated and hard to read, so I re-wrote it into proper C++.