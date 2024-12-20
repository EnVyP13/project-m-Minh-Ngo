cmake_minimum_required(VERSION 3.29)

project(MinhNgo)

find_package(fmt CONFIG REQUIRED)

add_executable(FooBar Foo.cpp Bar.cpp)

target_link_libraries(FooBar PRIVATE fmt::fmt)