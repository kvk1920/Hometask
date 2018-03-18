cmake_minimum_required(VERSION 2.8)

project(Hometask)

include_directories(A)

execute_process(
	COMMAND python3 A/script.py
)

add_executable(Main main.cpp A/index.h)
