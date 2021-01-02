cmake_minimum_required(VERSION 3.5.0)
project(ompeval)

add_library(
    ${PROJECT_NAME} SHARED
    CardRange.cpp
    CardRange.h
    CombinedRange.cpp
    CombinedRange.h
    Constants.h
    EquityCalculator.cpp
    EquityCalculator.h
    Hand.h
    HandEvaluator.cpp
    HandEvaluator.h
    OffsetTable.hxx
    Random.h
    Util.h
    )

set_target_properties(${PROJECT_NAME} PROPERTIES CXX_STANDARD 17)