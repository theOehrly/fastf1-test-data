# fastf1-test-data

Frozen HTTP responses and static test files used to run the
[FastF1](https://github.com/theOehrly/Fast-F1) test suite fully offline.

This repository is consumed as a git submodule at `fastf1/testing/data/` in the
FastF1 repository. It is not useful on its own.

The submodule commit recorded in each FastF1 commit pins the exact data that
version of the test suite was written against, so `git checkout <tag> &&
git submodule update --init` reproduces a historic test run.

## Adding data

Do not hand-edit these files. Record them using the tooling that the FastF1
tests provide for this. Detail instructions on how to update the test files 
in this repository can be found in the contributor documentation at  
https://docs.fastf1.dev.
