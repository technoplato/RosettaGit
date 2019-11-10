+++
title = "15 puzzle solver/Optimal solution"
description = ""
date = 2017-10-24T09:51:59Z
aliases = []
[extra]
id = 21628
[taxonomies]
categories = []
tags = []
+++

=Optimal solution in 52 single moves:=

 15 14  1  6
  9 11  4 12
  0 10  7  3
 13  8  5  2

 15 14  1  6
  9 11  4 12
 10  0  7  3
 13  8  5  2

 15 14  1  6
  9 11  4 12
 10  7  0  3
 13  8  5  2

 15 14  1  6
  9 11  4 12
 10  7  3  0
 13  8  5  2

 15 14  1  6
  9 11  4  0
 10  7  3 12
 13  8  5  2

 15 14  1  6
  9 11  0  4
 10  7  3 12
 13  8  5  2

 15 14  1  6
  9 11  3  4
 10  7  0 12
 13  8  5  2

 15 14  1  6
  9 11  3  4
 10  7  5 12
 13  8  0  2

 15 14  1  6
  9 11  3  4
 10  7  5 12
 13  0  8  2

 15 14  1  6
  9 11  3  4
 10  0  5 12
 13  7  8  2

 15 14  1  6
  9  0  3  4
 10 11  5 12
 13  7  8  2

 15  0  1  6
  9 14  3  4
 10 11  5 12
 13  7  8  2

  0 15  1  6
  9 14  3  4
 10 11  5 12
 13  7  8  2

  9 15  1  6
  0 14  3  4
 10 11  5 12
 13  7  8  2

  9 15  1  6
 14  0  3  4
 10 11  5 12
 13  7  8  2

  9  0  1  6
 14 15  3  4
 10 11  5 12
 13  7  8  2

  9  1  0  6
 14 15  3  4
 10 11  5 12
 13  7  8  2

  9  1  3  6
 14 15  0  4
 10 11  5 12
 13  7  8  2

  9  1  3  6
 14 15  5  4
 10 11  0 12
 13  7  8  2

  9  1  3  6
 14 15  5  4
 10 11  8 12
 13  7  0  2

  9  1  3  6
 14 15  5  4
 10 11  8 12
 13  7  2  0

  9  1  3  6
 14 15  5  4
 10 11  8  0
 13  7  2 12

  9  1  3  6
 14 15  5  4
 10 11  0  8
 13  7  2 12

  9  1  3  6
 14 15  5  4
 10  0 11  8
 13  7  2 12

  9  1  3  6
 14  0  5  4
 10 15 11  8
 13  7  2 12

  9  1  3  6
  0 14  5  4
 10 15 11  8
 13  7  2 12

  0  1  3  6
  9 14  5  4
 10 15 11  8
 13  7  2 12

  1  0  3  6
  9 14  5  4
 10 15 11  8
 13  7  2 12

  1  3  0  6
  9 14  5  4
 10 15 11  8
 13  7  2 12

  1  3  6  0
  9 14  5  4
 10 15 11  8
 13  7  2 12

  1  3  6  4
  9 14  5  0
 10 15 11  8
 13  7  2 12

  1  3  6  4
  9 14  5  8
 10 15 11  0
 13  7  2 12

  1  3  6  4
  9 14  5  8
 10 15  0 11
 13  7  2 12

  1  3  6  4
  9 14  5  8
 10 15  2 11
 13  7  0 12

  1  3  6  4
  9 14  5  8
 10 15  2 11
 13  0  7 12

  1  3  6  4
  9 14  5  8
 10  0  2 11
 13 15  7 12

  1  3  6  4
  9  0  5  8
 10 14  2 11
 13 15  7 12

  1  3  6  4
  9  5  0  8
 10 14  2 11
 13 15  7 12

  1  3  6  4
  9  5  2  8
 10 14  0 11
 13 15  7 12

  1  3  6  4
  9  5  2  8
 10 14  7 11
 13 15  0 12

  1  3  6  4
  9  5  2  8
 10 14  7 11
 13  0 15 12

  1  3  6  4
  9  5  2  8
 10  0  7 11
 13 14 15 12

  1  3  6  4
  9  5  2  8
  0 10  7 11
 13 14 15 12

  1  3  6  4
  0  5  2  8
  9 10  7 11
 13 14 15 12

  1  3  6  4
  5  0  2  8
  9 10  7 11
 13 14 15 12

  1  3  6  4
  5  2  0  8
  9 10  7 11
 13 14 15 12

  1  3  0  4
  5  2  6  8
  9 10  7 11
 13 14 15 12

  1  0  3  4
  5  2  6  8
  9 10  7 11
 13 14 15 12

  1  2  3  4
  5  0  6  8
  9 10  7 11
 13 14 15 12

  1  2  3  4
  5  6  0  8
  9 10  7 11
 13 14 15 12

  1  2  3  4
  5  6  7  8
  9 10  0 11
 13 14 15 12

  1  2  3  4
  5  6  7  8
  9 10 11  0
 13 14 15 12

  1  2  3  4
  5  6  7  8
  9 10 11 12
 13 14 15  0
=Optimal solution in 31 multi moves: u2r2d3ru2ld2ru3ld3l2u3r2d2l2dru3rd3l2u2r3dl3dru2r2d2=

```txt

 original:         move 1:u2         move 2:r2         move 3:d3         move 4:r          move 5:u2         move 6:l          move 7:d2
 15 14  1  6          14  1  6       14  1     6       14  1  4  6       14  1  4  6       14  1  4  6       14  1  4  6       14  1  4  6
  9 11  4 12       15 11  4 12       15 11  4 12       15 11  7 12       15 11  7 12       15 11  7          15 11     7       15 11  5  7
    10  7  3        9 10  7  3        9 10  7  3        9 10  5  3        9 10  5  3        9 10  5 12        9 10  5 12        9 10  2 12
 13  8  5  2       13  8  5  2       13  8  5  2       13  8     2       13  8  2          13  8  2  3       13  8  2  3       13  8     3

 move 8:r          move 9:u3         move 10:l         move 11:d3        move 12:l2        move 13:u3        move 14:r2        move 15:d2
 14  1  4  6       14  1  4          14  1     4       14  1  5  4       14  1  5  4           1  5  4        1  5     4        1  5  2  4
 15 11  5  7       15 11  5  6       15 11  5  6       15 11  2  6       15 11  2  6       14 11  2  6       14 11  2  6       14 11  3  6
  9 10  2 12        9 10  2  7        9 10  2  7        9 10  3  7        9 10  3  7       15 10  3  7       15 10  3  7       15 10     7
 13  8  3          13  8  3 12       13  8  3 12       13  8    12          13  8 12        9 13  8 12        9 13  8 12        9 13  8 12

 move 16:l2        move 17:d         move 18:r         move 19:u3        move 20:r         move 21:d3        move 22:l2        move 23:u2
  1  5  2  4        1  5  2  4        1  5  2  4        1     2  4        1  2     4        1  2  3  4        1  2  3  4        1  2  3  4
 14 11  3  6       14 11  3  6       14 11  3  6       14  5  3  6       14  5  3  6       14  5 10  6       14  5 10  6           5 10  6
    15 10  7        9 15 10  7        9 15 10  7        9 11 10  7        9 11 10  7        9 11  8  7        9 11  8  7       14 11  8  7
  9 13  8 12          13  8 12       13     8 12       13 15  8 12       13 15  8 12       13 15    12          13 15 12        9 13 15 12

 move 24:r3        move 25:d         move 26:l3        move 27:d         move 28:r         move 29:u2        move 30:r2        move 31:d2
  1  2  3  4        1  2  3  4        1  2  3  4        1  2  3  4        1  2  3  4        1  2  3  4        1  2  3  4        1  2  3  4
  5 10  6           5 10  6  7        5 10  6  7        5 10  6  7        5 10  6  7        5     6  7        5  6  7           5  6  7  8
 14 11  8  7       14 11  8             14 11  8        9 14 11  8        9 14 11  8        9 10 11  8        9 10 11  8        9 10 11 12
  9 13 15 12        9 13 15 12        9 13 15 12          13 15 12       13    15 12       13 14 15 12       13 14 15 12       13 14 15

```
