# C++ version of Gilded Rose refactoring kata

## Introduction
The C++ version of the Gilded Rose refactoring kata for the 
Googletest](https://github.com/google/googletest) framework.

The `GildedRose.cc` file, i.e. the code under test, is identical in all four variants.

## Prerequisites

* CMake version >= 3.13
* C++ compiler that support C++11

## How to build and run tests in a terminal

### Build tests

$> cmake -S . -B build
$> cmake --build build
$> cd build
$> make test
$> cd ..


### Run all tests

    $ ctest

### Run all tests with verbose output

    $ ctest -VV

### Run a specific test with verbose output

    $ ctest -VV --tests-regex Catch2Approval

