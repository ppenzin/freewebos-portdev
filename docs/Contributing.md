Contributing
============

Below are some possible projects

### Fixing the test infrastructure

Repositories have tests, those but are not runnable: attempt to run CMake with
tests enabled gives an error along the lines of 'gtest is not found in
/usr/local/webos', which implies that the tests (inherited from OpenWebOS or
maybe even the original) rely on a custom version of Google Test. Eventually we
need to find out if that is the case and make it work with stock gtest.

### Set up CI

There is not Continuous Integration at the moment. It is needed for both
x86/AMD64 development and for porting on ARM.

