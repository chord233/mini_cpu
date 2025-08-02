# mini_cpu
使用 Verilog 硬件描述语言，基于 RV32I 指令集，设计的 32 位的经典五级流水线的处理器核。
学习极客时间课程后尝试自己完成的基于RISC-V的32位五级流水线CPU的实现。

## 项目特性
- 基于 RISC-V RV32I 指令集
- 经典五级流水线架构
- 使用 Verilog HDL 实现
- 支持仿真测试

## 构建和运行

### 编译汇编测试程序
```bash
make asm
```

### 运行CPU仿真
```bash
make cpu
```

### 查看仿真波形
```bash
make wave
```

### 清理临时文件
```bash
make clean
```

## 项目结构
- `rtl/` - Verilog源代码（CPU核心模块）
- `sim/` - 仿真相关文件
- `tb/` - 测试平台
- `tmp/` - 临时文件目录

## 依赖工具
- RISC-V工具链 (riscv64-linux-gnu)
- Icarus Verilog (iverilog)
- GTKWave (波形查看器)
- Python3

参考链接：[计算机基础实战课](https://time.geekbang.org/column/intro/100117801?utm_campaign=geektime_search&utm_content=geektime_search&utm_medium=geektime_search&utm_source=geektime_search&utm_term=geektime_search)