cmake_minimum_required(VERSION 3.16.3)
project(lab4_csv_parser)

set(CMAKE_CXX_STANDARD 20)

add_executable(lab4_csv_parser main.cpp  CSV_parser.h  Exceptions.h Tuple_print.h)
