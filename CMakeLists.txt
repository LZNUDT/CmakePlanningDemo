cmake_minimum_required(VERSION 3.29.0)
project(planning
   # VERSION 0.01
   # DESCIPRTION "a demo of cmake planning"
   # HOMEPAGE_URL "https://github.com/LZNUDT/CmakePlanningDemo"
   # LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)

#变量和目录设置
set(CAMKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
set(Process_Dir ${CMAKE_SOURCE_DIR}/src/process)
set(Pns_Map_Dir ${CMAKE_SOURCE_DIR}/src/pnc_map)

#添加子目录
add_subdirectory(src)
#测试github push
