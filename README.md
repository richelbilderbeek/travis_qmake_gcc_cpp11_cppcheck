# travis_qmake_gcc_cpp11_cppcheck

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_cppcheck.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_cppcheck)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_cppcheck.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/)

This GitHub is part of:

 * [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial)
 
The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` only
 * Code coverage: none
 * Static code analysis: `cppcheck`
 * Source: one single file, `main.cpp`

More complex builds:

 * Use C++14: [travis_qmake_gcc_cpp14_cppcheck](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_cppcheck)
 * Use C++17: [travis_qmake_gcc_cpp17_cppcheck](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_cppcheck)

Builds of similar complexity:

 * [none]

Less complex builds:

 * Use C++98: [travis_qmake_gcc_cpp98_cppcheck](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_cppcheck)
 * No `cppcheck`: [travis_qmake_gcc_cpp11](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11)

