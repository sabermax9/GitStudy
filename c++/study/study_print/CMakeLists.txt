cmake_minimum_required(VERSION 3.15)  # 指定 CMake 最低版本
project(YourProject)                  # 项目名称

# 设置 C++ 标准（例如 C++17）
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 添加可执行文件
add_executable(${PROJECT_NAME} src/print.cpp)

