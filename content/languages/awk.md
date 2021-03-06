+++
title = "AWK"
description = ""
date = 2018-04-09T03:11:19Z
aliases = []
[extra]
id = 1819
[taxonomies]
categories = []
tags = []
+++

{{language
|exec=interpreted
|tag=awk
}}{{CompileOnline}}
AWK is a small but powerful programming language that can process and convert text files. AWK is part of every [[Unix]]-derived system.

Each AWK program consists of pattern-action statements.
The program reads each input line, checks lines against patterns, and runs matching actions.
For programs that never read input lines, the entire program can be one <code>BEGIN { ... }</code> block.

* ''List users who have /bin/ksh as a shell.''
```awk
$ awk -F: '$7 == "/bin/ksh" { print $1 }' /etc/passwd
```


AWK has only three types of variables: they are strings, floating-point numbers, and associative arrays (where every array index is a string).
Conversion between strings and numbers is automatic. AWK also has regular expressions, which appear in many AWK programs.
There are a few built-in functions, like cos() and sprintf().

* ''Find average line length.''
```awk
$ awk '{ cnt += length($0) } END { print cnt / NR }' /etc/rc
```


The name "AWK" comes from the initials of Alfred Aho, Peter Weinberger and Brian Kernighan: they invented AWK during the 1970s.
A few decades later, Kernighan continues to maintain the [[nawk|reference implementation]] of AWK.

==Links==
*[http://leaf.dragonflybsd.org/cgi/web-man?command=awk&section=1 awk(1) manual page], short and brief
*[https://www.gnu.org/software/gawk/ gawk] GNU awk [https://www.gnu.org/software/gawk/manual/ manual]
*[[wp:AWK (programming language)|AWK in Wikipedia]]
*[http://awk.info AWK Community Portal]

==Online-Execution==
* [http://ideone.com ideone.com] - gawk, mawk (both are kept up to date)

==Todo==
[[Reports:Tasks_not_implemented_in_AWK]]
