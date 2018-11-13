## Last Week's Accomplishments

The script correctly parses multiple changes in a single file, and is more dynamic about telling the user whether the script has finished, no text files were found, or whether it was unable to parse a particular file properly.

## This Week's Plan

Going to modify the script so that it actually is calling the 'git log -p' command on various Git repositories. Going to learn  how to work with GitPython, and implement it such that the script calls the command itself and parses the output line by line, without need for text files as intermediaries.

## Anything Blocking?

The parser has still has issues with white space - might fix that by just adding the --oneline flag to the Git command that is called.

## Notes
