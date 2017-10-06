cmake_minimum_required(VERSION 2.8)
project(MyApp)

file(GLOB_RECURSE src/*.cpp)

set( SRC
	src/main.cpp
)

add_executable(MyAPP ${SRC})

#target_link_libraries(MyApp pthread)
#install(TARGETS MyApp DESTINATION bin)
