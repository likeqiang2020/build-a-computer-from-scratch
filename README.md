# 🖥️ 从零搭建计算机 — 学习笔记

> 跟 B 站《从零搭建计算机保姆级教程》走，记录从**逻辑门**到**可运行 CPU** 的完整过程。
> 笔记跟着视频节奏来，记一些概念和实际操作。

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
└── 05-bus/                    ← 🚌 总线
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
</table>

---

## 🔗 参考资源

- B 站课程：[从零搭建计算机保姆级教程](https://www.bilibili.com/video/BV1QLT8zuE8F/)
- 参考书籍：《编码：隐匿在计算机软硬件背后的语言》—— 非常有必要读一下
- 模拟器：Logisim（文章的 PNG 电路结构图都是用这个画的）
- 前期上传实物面包片的图片占了很多空间，后面考虑优先使用Tinkercad画图
- 74LS系列芯片手册：https://www.futurlec.com/IC74LS00Series.shtml
- 也可以使用纯软件模拟：[一个8位二进制CPU的设计和实现](https://www.bilibili.com/video/BV1aP4y1s7Vf/?)
---

*笔记持续更新中…… 🚀*
