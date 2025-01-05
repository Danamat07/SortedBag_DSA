cmake_minimum_required(VERSION 3.27)
project(sortedBag_fr)

set(CMAKE_CXX_STANDARD 17)

add_executable(sortedBag_fr
        App.cpp
        ExtendedTest.cpp
        ExtendedTest.h
        ShortTest.cpp
        ShortTest.h
        SortedBag.cpp
        SortedBag.h
        SortedBagIterator.cpp
        SortedBagIterator.h)
