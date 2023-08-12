cmake_minimum_required(VERSION 3.22)
project(rapidjson)

add_library(rapidjson INTERFACE)
target_include_directories(rapidjson INTERFACE ../include)
add_library(RapidJSON::rapidjson ALIAS rapidjson)
