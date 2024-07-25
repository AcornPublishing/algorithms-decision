# Algorithms for Decision Making
*Ancillaries for the textbook*

This repository contains resources related to [Algorithms for Decision Making](https://algorithmsbook.com/decisionmaking) by Mykel J. Kochenderfer, Tim A. Wheeler, and Kyle H. Wray (MIT Press, 2022).

## Problem definitions

The problem environments used in the book (summarized in Appendix F) have been implemented in the Julia package [DecisionMakingProblems.jl](https://github.com/algorithmsbooks/DecisionMakingProblems.jl).

## Code

All textbook typeset code blocks can be found in this [repository](https://github.com/algorithmsbooks/decisionmaking-code).

## Figures

All figures can be downloaded [here](https://github.com/algorithmsbooks/decisionmaking-figures). Feel free to use these figures in presentations.

## Syllabi

As more universities begin offering courses based on the textbook, we will link to their public syllabi.

1. Stanford University, [CS238: Decision Making under Uncertainty](https://cs238.stanford.edu/)
2. University of Colorado, [ASEN 5519-003: Decision Making under Uncertainty](https://www.colorado.edu/aerospace/sites/default/files/attached-files/asen_5519-003_dmu.pdf)
3. Brown University, [CSCI 2951-F: Learning and Sequential Decision Making](http://cs.brown.edu/courses/cs2951f/)

Feel free to file a pull request or issue to add additional courses that use the textbook.

## Errata

Errata to the print version can be found [here](https://github.com/algorithmsbooks/decisionmaking). You may also file issue reports there.

------

### 한국어판 참고 사항

번역서에는 2024년 7월 12일까지의 정오표를 반영했으며, 아래에서 반영한 내용을 확인하실 수 있습니다.

- [p. 108] Ex 5.4: Make edge E->D in the PDAG directed (thanks to Nikhil Raghuraman)
- [p. 121] Alg 6.2: Caption updated to reflect that algorithm returns the value of information (thanks to Griffin Holt) 
- [p. 157] Ex 7.9: Change solution to "then both policies are optimal" (thanks to Liam Kruse)
- [p. 174] Fig 8.13: Changed "polynomial" to "quadratic" (thanks to Balduin)
- [p. 192] Ex 9.5: Change N(s0) to 1, as count is not incremented until after exploration (thanks to Paul Diederichs)
- [p. 196] Ex 9.8: Change line plot colors to improve readability wrt color blindness (thanks to Zhen Wu)
- [p. 199] Alg 9.9: P.S should be prepended with "π." (thanks to Griffin Holt)
- [p. 226] Fix intermediate derivation in equation in solution of Ex 10.1 (thanks to Paul Diederichs)
- [p. 246] Ex 11.2 solution: "theh" should be "the" (thanks to Marc Schlicting)
- [p. 304] Ex 15.2 pinned the RNG to produce the output expected in the example description (thanks to Appoorva Dixit)
- [p. 307] Ex 15.3 curve was not plotted with the correct demoninator, causing the curve to be too low (thanks to Hugo Buurmeijer)
- [p. 314] Ex 15.7 values for arm 1 were fixed (thanks to Mykel)
- [p. 317] Mention that when N(s,a) = 0, we can use a uniform distribution or set T(s,a) to zero (thanks to Mykel and Dylan Asmar)
- [p. 329] Eq 16.8: b in second P(s'|s,b,a) should be theta (thanks to Griffin Holt)
- [p. 330] Change the reference to Chapter 16 to be to Part 4 instead (thanks to Michael Sheehan)
- [p. 436] Update Sec. 21.6 and implementation of utility() in Alg. 21.9 (thanks to Shengtong Zhang)
- [p. 461] Ex 22.5: change O(o2 | a3, s2) to O(o2 | a3, s1) (thanks to Dylan Asmar)
- [p. 468] Prob 22.3: update to reflect use of successor state in observation func (thanks to Dylan Asmar)
- [p. 479] Alg 23.4: change comment "prune identical from previous nodes" to "prune identical from new nodes" (thanks to Emma Passmore)
- [p. 585] Eq. D.6: change - to + (thanks to Jonathan Larkin)
- [p. 644] Sec. G.3.2: "x" in text should be "X" to be consistent with code (thanks to Ziyu Wang)