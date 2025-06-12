# 设置 CMake 最低版本要求（如果使用低于 3.10 的 CMake，将报错）
cmake_minimum_required(VERSION 3.10)  

# 定义项目名称为 ForStudy（会影响生成的可执行文件和库的默认名称）
project(ForStudy)  

# 设置 C++ 编译标准为 C++17（确保使用现代 C++ 特性）
set(CMAKE_CXX_STANDARD 17)  

# 强制要求使用指定的 C++ 标准，不允许编译器降级
set(CMAKE_CXX_STANDARD_REQUIRED ON)  

# 创建一个名为 ForStudy 的可执行文件，由 main.cpp 源文件编译生成
add_executable(ForStudy main.cpp)  