cmake_minimum_required(VERSION 3.10)
project (test-allumage)
add_executable(test-allumage test_allumage.c)
install(TARGETS test-allumage RUNTIME DESTINATION /usr/bin)

