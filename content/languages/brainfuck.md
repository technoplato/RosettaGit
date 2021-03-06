+++
title = "Brainfuck"
description = ""
date = 2014-11-21T14:16:22Z
aliases = []
[extra]
id = 2022
[taxonomies]
categories = []
tags = []
+++

{{language|Brainfuck|bnf=http://ninh.nl/blog/2008/10/25/brainfck-birds-of-a-feather-session-take-2/}}
Also known as '''Brainfuck''', but identified as '''Brainfuck''' for reasons described [[Rosetta Code:Brainfuck|here]].

Created by Urban Müller in 1993 in an attempt to create the world's smallest Turing-complete compiler.
It is noted as an [[:Category:Esoteric_Languages|esoteric programming language]],
as it is not ordinarily used for applications development,
but it also noted as being a minimalist language.

The construction of the language is similar to a [[wp:Turing Machine|Turing Machine]].

As with the Turing Machine, Brainfuck is built from a finite state machine and an infinite tape of cells.
Each cell can be any size, including unbounded, but is frequently an eight bit byte.
The finite state machine is the program code with the program counter pointing at the current state.

The strong similarity is one reason that a Brainfuck equivalent named ''Ρʺ''
was suitable for use by Corrado Böhm in 1964
to prove that structured programming using only ''while loops''
was just a powerful as ''goto spagetti'' programming.

The complete specification for the language
(the available state transitions of the Turing machine)
can be summed up with the following eight symbols:

{| class="wikitable"
!align="center"|Character
!align="left" |Meaning
|-
|style="text-align:center"|<tt>></tt>
||increment the pointer (to point to the next cell to the right).
|-
|style="text-align:center"|<tt><</tt>
||decrement the pointer (to point to the next cell to the left).
|-
|style="text-align:center"|<tt>+</tt>
||increment (increase by one) the cell at the pointer.
|-
|style="text-align:center"|<tt>-</tt>
||decrement (decrease by one) the cell at the pointer.
|-
|style="text-align:center"|<tt>[</tt>
||jump forward to the command after the corresponding <tt>]</tt> if the cell at the pointer is zero.
|-
|style="text-align:center"|<tt>]</tt>
||jump back to the command after the corresponding <tt>[</tt> if the cell at the pointer is nonzero.
|-
|style="text-align:center"|<tt>.</tt>
||output the value of the cell at the pointer as a character.
|-
|style="text-align:center"|<tt>,</tt>
||accept one character of input, storing its value in the cell at the pointer.
|}

Alternatively, the <tt>]</tt> command may instead be translated as an unconditional jump '''to''' the corresponding <tt>[</tt> command, or vice versa; programs will behave the same but may run more slowly.

All other symbols, including traditional whitespace characters, are interpreted as comments.

The definition of the <tt>.</tt> and <tt>,</tt> in the above table still has some ambiguities due to the many ways of converting 'numbers' to 'characters'.
Urban Müller's ''smallest compiler'' converted between characters and numbers using the ASCII character set.
The newline character is number ''10'' and a end of file on input is signalled by the cell value being unchanged when the <tt>,</tt> command completes.
The <tt>,</tt> command uses line editing and waits for for the return key to be pressed.

Due to this minimal instruction set, Brainfuck is used as an introduction to compilers and has even been successfully implemented as a microprocessor core and the foundation to an operating system using a slightly extended syntax for output.
BUT due to vehement opposition to the name [http://esolangs.org/wiki/Cupid various] [http://esolangs.org/wiki/Category:Brainfuck_equivalents equivalents] are frequently used.


==See also==
* [[Rosetta Code:Brainfuck]]  ( why some people call it BF :)
* [[RCBF]] - BF interpreters as a Rosetta Code task

==Citations==

* [[eso:Brainfuck|Esoteric languages wiki entry]]
*[[wp:Brainfuck|Wikipedia entry on Brainfuck]]
* [http://dmoz.org/Computers/Programming/Languages/Brainfuck/ DMOZ Brainfuck category]
* [http://www.iwriteiam.nl/Ha_BF.html Brainfuck tutorial]


[[Category:Esoteric_Languages]]
