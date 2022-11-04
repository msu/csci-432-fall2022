# CSCI Project, Part 3

In today's class (Friday, 4 November 2022), you will work in a small group to
discuss potential project ideas.  In the project, you will select an algorithm
and create a video that presents some aspect of the algorithm (e.g., an
implementation, a proof, a variant of the algorithm, an application to an
interesting data set).

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
4. Another algorithm of your choice.  This must be an algorithm, and not a
   procedure or method that does not have a provable connection between the
   input and output.

By the end of next week (Friday, 11 November 2022), please submit a short
writ-eup that describes what will be in your proposed video. It is ok to propose
multiple options to open a discussion with Dr. Fasy.
