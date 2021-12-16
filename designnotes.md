# Design Notes

## Who is this for?

This document contains notes to the author (and possibly authors in the future) on design decisions and strategies.  It contains no content relevant to users of the material (e.g. students taking the course or instructors using the material for their courses).

## Install and setup

- Initial commit is done by creating the repository on github, then creating a docs directory and running `sphinx-quickstart` in that directory.  Choose separating out the source and build directories.
- 'furo' is the current theme of choice
- Append numbering information to 'conf.py' to allow figures to be numbered.
- A requirements.txt file is required in root, even if empty.

## Writing conventions

- Use the following order for headings: =, #, *, -, ^.  That gets five heading types
