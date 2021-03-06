+++
title = "Commodore BASIC"
description = ""
date = 2019-10-01T20:50:13Z
aliases = []
[extra]
id = 6982
[taxonomies]
categories = []
tags = []
+++

{{language|Commodore BASIC
          |exec=interpreted
          |tags=basic,commodorebasic
          |gc=yes
          }}
{{Implementation|BASIC}}
'''Commodore BASIC''' is the collective name for the various versions of [[:Category:BASIC|BASIC]] developed by [[Microsoft]] for [[Commodore]] 8-bit computers, starting with the [[wp:Commodore PET|PET]] in 1977. There were several versions; see [[wp:Commodore BASIC|Wikipedia's Commodore BASIC page]] for details.

Commodore BASIC is notable for its lack of integer arithmetic; all operations were carried out in floating-point, which made the interpreter slower than some of its peers.

Programs were tokenized into [[wp:bytecode|bytecode]], although many characters were left intact to facilitate printing the source code back out in original form; it's one of the few BASICs of the time that preserved whitespace (though not leading whitespace). Unlike some contemporary BASICs, it supported arrays of strings, and arrays could have thousands of elements as long as there was sufficient memory for them (but strings were limited to 255 bytes).

The most well-known version is 2.0, which came with the [[wp:Commodore VIC-20|VIC-20]] and [[wp:Commodore 64|Commodore 64]]. Despite the impressive sound and graphics capabilities of the machines, the language had no unique commands for them. Instead, programmers had to directly manipulate or read the hardware registers with POKE and PEEK commands to take advantage of those features. Later BASIC versions added support, but the later machines that came with those versions never came close to the popularity of the 64.

In addition to the sound and graphic statements, the later versions also introduced structured programming constructs: <code>DO...LOOP</code>, which supported both pre- and post-evaluated conditions (<code>DO WHILE/UNTIL ... LOOP</code> and <code>DO ... LOOP WHILE/UNTIL</code>) as well as unconditional loop exit (<code>EXIT</code>) and <code>BEGIN...BEND</code> code blocks, which allowed multi-line conditional clauses. However, other limitations remained: variables were still all global and limited to 2-letter names, user-defined functions were restricted to a single expression with a single argument, etc.
