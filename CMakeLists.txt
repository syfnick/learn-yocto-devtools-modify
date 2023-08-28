project(learn-yocto-devtools-modify C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (learn-yocto-devtools-modify main.c)

install(TARGETS learn-yocto-devtools-modify DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)
