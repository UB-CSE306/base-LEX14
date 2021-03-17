# LEX14 INSTRUCTIONS

## Introduction

This exercise revisits the SchemeValidator exercise we worked on earlier this semester.
The code you are being provided with includes code written by students.  No claim is made
that the code is correct.


## Main task

Your task is to do your best to identify bugs in the behavior of the code, for each bug identified write tests
to reveal the presence of each such bug, implement fixes, and try to achieve 100% code coverage of whitebox testing, once you have an implementation that passes the existing tests.

The functionality you are aiming to build is described here:  https://tools.ietf.org/html/rfc3986#section-3.1

## Process

Remember to follow the process we have discussed:

- Understand the requirements.

- Follow a Test-Driven Development approach, first writing black-box
tests (and any supporting functions needed) using a testing framework
(CUnit).  There may be existing blackbox tests, but these are not
guaranteed to be either correct or comprehensive.  Modify and/or add
tests as needed to address all specifications properly.

- Next, work incrementally to develop an implementation that passes all
the black-box tests you wrote.

- Once the implementation compiles (gcc) and passes the black-box tests,
incrementally write white-box tests to get full test coverage (gcov).

- Use the debugger (gdb) as needed to track down bugs.  Document your work
by including gbd output in your commit comments, both before and after a 
bug is fixed (showing cause of failure prior to fix, and correct behavior
after fix).

- Write an appropriate makefile for use with your build tool (make).  Apply
lessons from make LEXes.

- Make sure the use your git repo diligently, branching and merging
as appropriate, committing and pushing to the remote repo
frequently, and always using meaningful commit messages.

You may refer to any of your previous work in this class (i.e. LEX01
to LEX13, PRE, and EXP01) as well as documenation for any tools we
have discussed so far.

## Finishing up

Make sure you remember to **add/commit/push to your repo on GitHub** - if you don't we can't grade your work!

After lab is finished fill in [the LEX 14 reflection form](https://docs.google.com/forms/d/e/1FAIpQLScIsNPNmunOkHoxvLTzir1K-hz-0DwBHLF-KKYYYUP2739Fjg/viewform?usp=sf_link).
