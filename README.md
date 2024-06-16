# 文件说明

## 核心文件
- mini.y mini.l
- tac.h tac.c
- obj.h obj.h

## 测试用例
- mini 语言文件 ***.m
- 编译器 arm64 汇编语言文件 ***.m.s
- 机器语言文件 ***

# 功能说明

## 全部功能
- char 类型变量
- 条件语句
- 寄存器动态分配
- 局部、全局变量存储
- 变量地址作为参数类型
- 数组类型变量
- 数组标识符作为参数类型

## 本人分工
- 变量地址作为参数类型：tac.c 中的 declare_para_address 函数
- 数组类型变量：tac.c 中的 declare_var_array 函数
- 数组标识符作为参数类型：tac.c 中的 declare_para_array 函数



