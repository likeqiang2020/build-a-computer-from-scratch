# 🖥️ 从零搭建计算机 — 学习笔记

> 记录从**逻辑门**到**可运行 CPU** 的完整过程。

---

## 📂 目录结构

```
build-a-computer-from-scratch/
├── README.md
├── images/                     ← 📷 电路图 + 面包板实物照片
├── 74-series/                  ← 🔩 74LS 芯片简化图
├── 01-logic-gates/             ← ⚡ 半导体 → 逻辑门
├── 02-adder-principle/         ← 🧮 加法器原理
├── 03-memory/                  ← 💾 存储单元
├── 04-clock/                   ← ⏰ 时钟原理
├── 05-bus/                    ← 🚌 总线
├── 06-register/               ← 📝 寄存器
├── 07-alu/                    ← 🔢 运算器
└── 08-programming/            ← 💻 编程的本质
```

### 章节速览

<table>
  <tr>
    <th>章节</th>
    <th>内容</th>
  </tr>
  <tr>
    <td><b>⚡ 01-logic-gates</b><br>从半导体到逻辑门</td>
    <td><a href="01-logic-gates/1-semiconductor-and-gates.md">1-semiconductor-and-gates.md</a></td>
  </tr>
  <tr>
    <td rowspan="3"><b>🧮 02-adder-principle</b><br>加法器原理</td>
    <td><a href="02-adder-principle/1-half-adder.md">1-half-adder.md</a></td>
  </tr>
  <tr>
    <td><a href="02-adder-principle/2-full-adder.md">2-full-adder.md</a></td>
  </tr>
  <tr>
    <td><a href="02-adder-principle/3-three-bit-adder.md">3-three-bit-adder.md</a></td>
  </tr>
  <tr>
    <td rowspan="5"><b>💾 03-memory</b><br>存储单元</td>
    <td><a href="03-memory/1-sr-latch.md">1-sr-latch.md</a></td>
  </tr>
  <tr>
    <td><a href="03-memory/2-d-latch.md">2-d-latch.md</a></td>
  </tr>
  <tr>
    <td><a href="03-memory/3-capacitor.md">3-capacitor.md</a></td>
  </tr>
  <tr>
    <td><a href="03-memory/4-d-flip-flop.md">4-d-flip-flop.md</a></td>
  </tr>
  <tr>
    <td><a href="03-memory/5-accumulator.md">5-accumulator.md</a></td>
  </tr>
  <tr>
    <td rowspan="1"><b>⏰ 04-clock</b><br>时钟原理</td>
    <td><a href="04-clock/555timer.md">555timer.md</a></td>
  </tr>
  <tr>
    <td rowspan="1"><b>🚌 05-总线</b><br>总线</td>
    <td><a href="05-bus/1-bus.md">1-bus.md</a></td>
  </tr>
  <tr>
    <td rowspan="1"><b>📝 06-register</b><br>寄存器</td>
    <td><a href="06-register/1-register.md">1-register.md</a></td>
  </tr>
  <tr>
    <td rowspan="2"><b>🔢 07-alu</b><br>运算器</td>
    <td><a href="07-alu/1-binary-subtraction.md">1-binary-subtraction.md</a></td>
  </tr>
  <tr>
    <td><a href="07-alu/2-alu.md">2-alu.md</a></td>
  </tr>
  <tr>
    <td rowspan="1"><b>💻 08-programming</b><br>编程的本质</td>
    <td><a href="08-programming/1-programming.md">1-programming.md</a></td>
  </tr>
</table>

---

## 🔗 参考资源

### B 站课程
- [从零搭建计算机保姆级教程](https://www.bilibili.com/video/BV1QLT8zuE8F/)
- [一个8位二进制CPU的设计和实现](https://www.bilibili.com/video/BV1aP4y1s7Vf/?)

### 参考书籍
- 《编码：隐匿在计算机软硬件背后的语言》

### 软件工具
- Logisim / Logisim-evolution
- Tinkercad
- **Digital**（从 ALU 章节开始使用，仿真效果更好）

### 74LS 系列芯片资料
- [74LS00 系列手册](https://www.futurlec.com/IC74LS00Series.shtml)
- [74LS245 数据手册](https://www.alldatasheet.com/datasheet-pdf/view/12640/ONSEMI/74LS245.html)


*笔记持续更新中…… 🚀*
