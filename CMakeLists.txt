cmake_minimum_required(VERSION 2.8) 

add_subdirectory(tinyxml) #添加子目录

include_directories(tinyxml)

add_executable(Main main.cpp) 
target_link_libraries(Main tiny_xml)#目标执行文件的lib依赖