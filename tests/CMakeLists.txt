INCLUDE_DIRECTORIES(${gtest_INCLUDE_DIRS})
ADD_SUBDIRECTORY(src)

IF (ENABLE_ACTIVE_TESTS)
    ADD_SUBDIRECTORY(active_tests)
ENDIF()