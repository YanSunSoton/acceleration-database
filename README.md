# acceleration-database

This is a databases for acceleration algorithm evaluation. See our paper: Sun, Yan, Hare, Jonathon and Nixon, Mark (2017) Analysing acceleration for motion analysis. In The 13th International Conference on Signal Image Technology &amp; Internet Based Systems.


Middlebury data and ground truth part 1 and part 2
Some datasets from Middlebury optical flow databases and Pseudo-ground truth (obtained by MDP-Flow2 L. Xu, J. Jia, and Y. Matsushita. Motion detail preserving optical flow estimation. PAMI 34(9):1744-1757, 2012.) Estimating pseudo-ground truth due to they only offer one single optical flow ground truth between two frames and evaluating acceleration algorithms need at least three frames.
Choosing MDP-Flow2 to estimating ground truth due to its accuracy and the code is available. 

"frame09_mdpof.flo" is the ground truth optical flow from frame10 to frame09
"frame10_mdpof.flo" is the ground truth optical flow from frame10 to frame11 


High speed cradle, video is from: https://www.youtube.com/watch?v=7qPvmYbfM6I

Pool break overhead view, video is from: https://www.youtube.com/watch?v=XpPbrLiSMCY
