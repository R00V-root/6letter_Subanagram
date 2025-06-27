# 6letter_Subanagram

This repository contains a small Python program that enumerates every English word of length two to six that can be assembled from any six-letter input without re-using letters beyond their supplied counts. 
It is inspired by classic Scrabble “rack-solver” utilities and relies on the canonical Linux word-list shipped at  /usr/share/dict/words

The word list used was found at: https://users.cs.duke.edu/~ola/ap/linuxwords

Reliability is up for debate, for an official word list apply for Scrabbles software license at https://scrabbleplayers.org/w/Software

No external libraries are required; the script uses the standard-library modules itertools, pathlib, and sys.
