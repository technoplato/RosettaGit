+++
title = "SNUSP"
description = ""
date = 2009-07-31T08:50:03Z
aliases = []
[extra]
id = 2678
[taxonomies]
categories = []
tags = []
+++

{{language|SNUSP|
exec=interpreted}}'''SNUSP''' is an esoteric language that is a mix of [[Brainfuck]] and [[Befunge]], with a call stack and optional concurrency thrown in. It uses all of the basic Brainfuck commands except the loop commands ('[' and ']'). There is a code pointer which moves through the two-dimensional code space in one of four directions like in Befunge, and it "bounces off" of two "mirrors" ('/' and '\'). For instance, if the code pointer is moving to the right and hits a '\', it starts to move down starting with the character below the mirror. The two other flow control commands are '?' (skip the next character if the element at the memory pointer is 0), and '!' (unconditional skip).  This is how SNUSP can get away without Brainfuck's loop commands. The optional '$' (start the code pointer here) rounds out '''Core SNUSP'''. There are two additional language layers: '''Modular SNUSP''' adds '@', and '#' for call and return from subroutine. '''Bloated SNUSP''' adds '&' for thread-split, a two-dimensional memory space (':' and ';'), and random numbers ('%').

==See also==
* [[eso:SNUSP|Esolangs]]
* http://c2.com/cgi/wiki?SnuspLanguage
* http://www.quirkster.com/iano/snusp/

[[Category:Esoteric Languages]]
