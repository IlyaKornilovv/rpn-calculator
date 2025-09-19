include(FetchContent)
FetchContent_Declare(
  googletest
  URL https://github.com/google/googletest/archive/03597a01ee50ed33e9fd71859932eb21d90d73f5.zip
)
FetchContent_MakeAvailable(googletest)


# include(FetchContent)
# FetchContent_Declare(
#  googletest
#  GIT_REPOSITORY https://github.com/google/googletest.git
#  GIT_TAG release-1.12.1
# )

# FetchContent_MakeAvailable(googletest)

# add_executable(rpn_tests
#     test_rpn.cpp
#     ${CMAKE_SOURCE_DIR}/src/rpn.cpp
# )

# target_link_libraries(rpn_tests PRIVATE gtest_main)

# target_include_directories(rpn_tests PRIVATE ${CMAKE_SOURCE_DIR}/include)

# add_test(NAME rpn_tests COMMAND rpn_tests)

