cmake_minimum_required(VERSION 2.8)
project(CollieHelper)

find_package(collie REQUIRED)

add_executable(collie_io programs/collie_io.cxx)
add_executable(collie_sigma_calc programs/collie_sigma_calc.cxx)
