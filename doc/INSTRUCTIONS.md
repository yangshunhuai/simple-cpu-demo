## 指令
| 指令助记符 | 对应机器码 | 操作数 | 操作 |
| -------- | -------- | --- | ------ |
| LDA | 0001 | 4位内存地址 | 将RAM内容载入A寄存器 |
| LDB | 0010 | 4位内存地址 | 将RAM内容载入B寄存器 |
| LDC | 0011 | 4位内存地址 | 将RAM内容载入C寄存器 |
| LDD | 0100 | 4位内存地址 | 将RAM内容载入D寄存器 |
| ADD | 0101 | 2位寄存器编号x2 | 加法，结果存在第一个寄存器 |
| SUB | 0110 | 2位寄存器编号x2 | 减法，结果存在第一个寄存器 |
| STOA | 0111 | 4位内存地址 | 将A寄存器内容载入RAM |
| STOB | 1000 | 4位内存地址 | 将B寄存器内容载入RAM |
| STOC | 1001 | 4位内存地址 | 将C寄存器内容载入RAM |
| STOD | 1010 | 4位内存地址 | 将D寄存器内容载入RAM |
| JMP | 1011 | 4位内存地址 | 从给定地址处开始执行 |
| JZ | 1100 | 4位内存地址 | ALU输出为0时从给定地址处开始执行 |
| JNZ | 1101 | 4位内存地址 | ALU输出不为0时从给定地址处开始执行 |
| HALT | 1110 | 0000 | 停止执行 |