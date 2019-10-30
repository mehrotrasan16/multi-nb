# multi-nb
A document editor which can be given one line instructions to build complex documents calling multiple language compilers.

the idea is mainly for comparitive or complex tutorial makers, to build a jupyter notebook like environment with multiple language code-blocks supported.

The different language code blocks may be indicated with a #!Py3.7/ #!RWBY / #!R line at the beginning, like a HTML document.
The system will scan the doc for these lines, be fitted with the default paths for the compilers for each lang(or will read the path variable and just pull out the current ones.), and when a code block is executed, will call the compiler on that lil block of code - pulling out the code as a different file and running it, printing out the console output after its execution back into the notebook file.

