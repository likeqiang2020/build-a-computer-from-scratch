# 🖥️ 从零搭建计算机 — 学习笔记

> 跟 B 站《从零搭建计算机保姆级教程》走，记录从**逻辑门**到**可运行 CPU** 的完整过程。
> 笔记跟着视频节奏来，记一些概念和实际操作。

---

## 为啥搞这个

傻x企鹅游戏，别人骂我啥事没有，我打俩字友好互动就给我禁言了，已卸载。  
原本打游戏的时间，就用来了解一下 CPU 的基本构成和原理吧。

---

## 📂 目录结构

```
build-a-computer-from-scratch/
├── README.md
├── images/                     ← 📷 电路图 + 面包板实物照片
├── 74-series/                  ← 🔩 74LS 芯片简化图
├── 01-logic-gates/             ← ⚡ 半导体 → 逻辑门
├── 02-adder-principle/         ← 🧮 加法器原理
└── 03-memory/                  ← 💾 存储单元
```

### 章节速览

<table>
  <tr>
    <th>章节</th>
    <th>内容</th>
    <th>进度</th>
  </tr>
  <tr>
    <td><b>⚡ 01-logic-gates</b><br>从半导体到逻辑门</td>
    <td><a href="01-logic-gates/1-semiconductor-and-gates.md">1-semiconductor-and-gates.md</a></td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td rowspan="3"><b>🧮 02-adder-principle</b><br>加法器原理</td>
    <td><a href="02-adder-principle/1-half-adder.md">1-half-adder.md</a></td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td><a href="02-adder-principle/2-full-adder.md">2-full-adder.md</a></td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td><a href="02-adder-principle/3-three-bit-adder.md">3-three-bit-adder.md</a></td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td><b>💾 03-memory</b><br>存储单元</td>
    <td><a href="03-memory/1-sr-latch.md">1-sr-latch.md</a></td>
    <td align="center">✅</td>
  </tr>
</table>

---

## 🔗 参考资源

- B 站课程：[从零搭建计算机保姆级教程](https://www.bilibili.com/video/BV1QLT8zuE8F/)
- 参考书籍：《编码：隐匿在计算机软硬件背后的语言》—— 非常有必要读一下
- 《穿越计算机的迷雾》—— 看了一点，也很好。作者李忠老师还有一本《X86 汇编语言：从实模式到保护模式》，如果有时间的话也很想复刻一下
- 模拟器：Logisim（文章的 PNG 电路结构图都是用这个画的）
- 74LS系列芯片手册：https://www.futurlec.com/IC74LS00Series.shtml

---

*笔记持续更新中…… 🚀*
