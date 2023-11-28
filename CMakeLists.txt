cmake_minimum_required(VERSION 3.26)

project(test_act LANGUAGES CXX)

add_executable(test_act
    
    main.cpp
    
)

target_compile_features(test_act PUBLIC cxx_std_23)
