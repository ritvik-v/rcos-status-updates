## Last Week's Accomplishments

The curriculum utility script was having some hiccups when git logs included multiple commits that modified multiple areas of a file - currently working a fix such that the parser is capable of keeping track of these changes. Modified the script so that the directory is a command line argument and that only text files with a name containing "log" are parsed.

## This Week's Plan

Still need to think about making output a more usable format than just sentences in a text file. Need to make the parser more robust, possibly will run git log -p on other repositories on Github to compile a large number of test cases that I can use that have more interesting commit logs.

## Anything Blocking?

The parser has issues with excess white space - if there's a carriage return in the commit message, for instance, the parser will likely fail. Also has bugs in parsing commits that modify multiple areas of a file.

## Notes
