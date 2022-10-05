cmake_minimum_required(VERSION 3.12)

project(cursocepel VERSION 0.1)

enable_testing()

include(Dart)

cmake_policy(SET CMP0076 NEW)



add_executable(hello

    hello.c

)



add_executable(myTest
    test.c
)
add_test(myTest myTest)
