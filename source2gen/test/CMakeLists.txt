project(${CMAKE_PROJECT_NAME}-test)

add_executable(${PROJECT_NAME}
  "src/codegen/test.c.cpp"
  "src/codegen/test.cpp.cpp"
)

target_link_libraries(${PROJECT_NAME}
  GTest::gtest_main
  lib${CMAKE_PROJECT_NAME}
)
