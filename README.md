# testing-pytest

### Chapter 1
### Installation

$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install pytest

### How to run pytest

- pytest: We can run pytest with no arguments, it will search the local dir and subdir for tests
- pytest <filename>: runs the tests in one file
- pytest <filename> <filename> ... : run the tests in multiple files
- pytest <dirname> : run the tests in the dir

### Test discovery

- Test files should be named "test_*.py" or "*_test".py
- Test methods and functions should be named "test_*"
- Test classes should be named Test*

### Possible outcomes of a test function

- PASSED (.)
- FAILED (F)
- SKIPPED (s)
- XFAIL (x)
- XPASS (X)
- ERROR (E)

### Verbose and Traceback
- -v or --verbose flag for more output
- --tb=no to turn off tracebacks