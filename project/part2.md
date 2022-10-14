# CSCI Project, Part 1

In today's class (Friday, 14 October 2022), you will work in a small group to
investigate an algorithm.  In particular, you will step through the algorithm in
detail for a small example.

By the end of the day Tuesday (18 October 2022), please submit a short
writ-eup that includes:

1. Description of the input.
2. Description of the output.
3. Pseudocode for the algorithm.  (Can be either your own or a snippet from a
   paper, book, or website.  If the latter, please fully cite).  Be sure to include line
   numbers.
4. Give an example, and walk through the code.  This part can be hand-written or
   written on a board and then included in your document as a picture.
5. Provide a decrementing function that proves that this terminates. (Proof that
   it is a decrementing function is not necessary).
6. As usual, a list of references used.  Be sure to explain how you used each
   reference.

This should be written as a coherent document, not as a bulleted list of
responses to the items listed above.

I have provided a handwritten example in D2L.  Group assignments can also be
found in D2L (and the email). Apologies if the handwritting is difficult to
decipher. I wrote this on a flight.

Algorithm Choices:

1. Matrix multiplication: Given two, square real-valued matrices, A and B, compute their
   product AB.
    * [Strassen's Algorithm](https://en.wikipedia.org/wiki/Strassen_algorithm).
      Show how this works for multiplying two 4x4 matrices in your example.
      Note that the the "Block matrices" are cretaed by dividing the matrices
      into submatrices.  So, A_{1,1} is the 2x2 matrix at the top-left corner of
      the matrix A.
2. Matching students to advisers at MSU: Given a set of students and faculty at
   MSU.  We're interested in an algorithm to pair them.  Consider one of the
   following:
    * [Gale-Shapely Algorithm](https://www.nrmp.org/intro-to-the-match/how-matching-algorithm-works/) solves the "stable matching problem." Adapt the
      phrasing of this algorithm to be for students/advisers.  Also see the top
      of page 173 of Section 4.3 in our textbook.
3. Line segment intersection: Given a set of n lines in the plane, determine if
   any pair of them intersects. Here, you may assume that you have access to an
   algorithm TestIntersection(seg1,seg2) that returns true if seg1 and
   seg2 intersect and false otherwise.
    * [Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/373/notes/x06-sweepline.pdf); see AnyIntersection.
    * [CMU Notes](https://www.cs.cmu.edu/~15451-f17/lectures/lec21-sweepline.pdf); see Section 2.
