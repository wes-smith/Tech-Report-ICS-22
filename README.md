This document contains the technical report corresponding to the ICS '22 publication "Beyond Time Complexity: Data Movement Complexity Analysis for Matrix Multiplication" (DOI 10.1145/3524059.3532395).

The tech report is in the same format as the paper, with sections 4 and 5, the derivations of RMM's reuse distance distribution and the paper's data movement complexity results, substantially lengthened. Much of the mathematial derivations were omitted in the original paper for space reasons - this report contains them in their entirety.

PAPER ERRATA: Page 4, RMM pseudocode line 9: C21 = rmm(A21, B11) + rmm(A22, B12) -> C21 = rmm(A21, B11) + rmm(A22, B21)
