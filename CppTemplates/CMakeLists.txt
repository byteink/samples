cmake_minimum_required(VERSION 3.7)
project(CppTemplates)

set(CMAKE_CXX_STANDARD 11)

add_executable(2_4 chapter2_函数模板/2_4_重载函数模板.cpp)

add_executable(3_1 chapter3_类模板/3_1_类模板.cpp)
add_executable(3_3 chapter3_类模板/3_3_类模板的特化.cpp)
add_executable(3_4 chapter3_类模板/3_4_局部特化.cpp)
add_executable(3_5 chapter3_类模板/3_5_缺省模板实参.cpp)

add_executable(4_1 chapter4_非类型模板参数/4_1_非类型的类模板参数.cpp)
add_executable(4_2 chapter4_非类型模板参数/4_2_非类型的函数模板参数.cpp)
add_executable(4_3 chapter4_非类型模板参数/4_3_非类型模板参数的限制.cpp)

add_executable(5_1 chapter5_技巧性基础知识/5_1_关键字typename.cpp chapter5_技巧性基础知识/5_6_使用字符串作为函数模板的实参.cpp)
add_executable(5_2 chapter5_技巧性基础知识/5_2_使用this.cpp)
add_executable(5_3 chapter5_技巧性基础知识/5_3_成员模板.cpp)
add_executable(5_4 chapter5_技巧性基础知识/5_4_模板的模板参数.cpp)
add_executable(5_5 chapter5_技巧性基础知识/5_5_零初始化)
add_executable(5_6 chapter5_技巧性基础知识/5_6_使用字符串作为函数模板的实参.cpp)

add_executable(6_2_1
        chapter6_模板实战/6_2_显式实例化/1_显式实例化/myfirst.cpp
        chapter6_模板实战/6_2_显式实例化/1_显式实例化/main.cpp
        )
add_executable(6_2_2_explicit
        chapter6_模板实战/6_2_显式实例化/2_组合包含模型和显式实例化/explicit_main.cpp
        chapter6_模板实战/6_2_显式实例化/2_组合包含模型和显式实例化/explicit_inst.cpp
        )
add_executable(6_2_2_inclusion
        chapter6_模板实战/6_2_显式实例化/2_组合包含模型和显式实例化/inclusion_main.cpp
        )
