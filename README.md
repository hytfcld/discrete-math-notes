# Discrete Mathematics Open Notes（离散数学图文自学笔记）

![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)
![Language: 中文](https://img.shields.io/badge/Language-%E4%B8%AD%E6%96%87-blue.svg)
![Format: HTML / PDF](https://img.shields.io/badge/Format-HTML%20%2F%20PDF-teal.svg)

这是一份面向**计算机科学自学者**整理的离散数学开源学习笔记。与偏重枯燥公理堆砌的传统笔记不同，本项目侧重**理论计算机科学（TCS）视角**，通过**原创原理图解、直觉类比、手算套路与考前速查表**，帮助读者快速建立图论、组合计数、离散几何与纠错码的核心思维框架。

---

## 目录与笔记列表

| 专题 | 核心覆盖内容 | 特色亮点 |
| :--- | :--- | :--- |
| **专题一：图论核心知识** | 握手引理、欧拉回路与哈密顿圈、de Bruijn 图建模、邻接矩阵与 Hoffman 界、Prüfer 编码与 Cayley 公式、群作用与 Burnside / Pólya 图计数、Kruskal 最小生成树、度量 TSP 近似、Hall 婚配定理、顶点着色与平面图欧拉公式 | 内嵌 8 幅原理示意图（含序列重建建模对比、Prüfer 编解码演示、边轮换诱导图解、贪心反例与平面图 $K_4 / K_5$ 对比） |
| **专题二：离散几何与二元纠错码** | 凸多边形对角线双射、直线划区递推与双射法、凸包与 Carathéodory 定理、Erdős–Szekeres 幸福结局定理、Fano 射影平面、仿射空间 $\mathbb{F}_2^3$、汉明距离与球填充界、标准 $[7,4,3]$ 汉明码、一阶 Reed–Muller 码 $\mathrm{RM}(1,m)$ | 内嵌 6 幅几何与编码图解（含标准自然二进制列序汉明码伴随式直读流程、RM(1,3) 多数表决译码图解）+ 4 道原创自测快题 |

---

## 笔记特色

- **图文结合，降低门槛**：针对最容易抽象卡壳的概念（如顶点置换诱导边轮换、汉明球完美填充、伴随式定位单错等）均配有矢量示意图，看图即可理解核心直觉。
- **聚焦算法与手算套路**：剥离冗长的底层细节，提炼可直接用于解题和工程直觉的步骤口诀（如 Prüfer 编解码、Pólya 三步计数法、二进制伴随式直读、多数表决译码）。
- **单文件便携排版**：每份笔记均为自包含的 HTML 文件，无需联网或外部依赖，支持浏览器直接阅读，并已针对 A4 纸张打印 / PDF 导出做好样式适配。
- **速查与自测闭环**：文末配有高频公式与避坑速查表，适合考前快速回顾。

---

## 使用方式

1. **克隆或下载仓库**：
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. **本地浏览**：直接用任意现代浏览器（Chrome、Edge、Safari、Firefox 等）双击打开对应的 `.html` 文件即可阅读。
3. **导出 PDF**：在浏览器中按 `Ctrl + P`（macOS 为 `Cmd + P`），选择「另存为 PDF」，勾选「背景图形」并将边距设为「无」，即可获得排版整洁的 A4 学习手册。

---

## 推荐搭配自学资源

如果你希望结合视频或经典参考书深入学习相关主题，推荐以下公开资源：

- **公开课**：MIT 6.042J *Mathematics for Computer Science*、UC Berkeley CS 70 *Discrete Mathematics and Probability Theory*
- **可视化科普**：3Blue1Brown《汉明码（Hamming Codes）》系列动画
- **经典读物**：László Lovász, József Pelikán, Katalin Vesztergombi — *Discrete Mathematics: Elementary and Beyond*

---

## 贡献与反馈

欢迎提交 Issue 或 Pull Request 帮助改进这份笔记：
- 修正公式排版或错别字；
- 补充更直观的例题、反例或思考题；
- 扩展更多离散数学专题（如组合计数、初等数论、离散概率与随机算法等）。

---

## 开源协议

本仓库中的所有原创笔记内容、示例与矢量图解均采用 **[CC BY-SA 4.0（知识共享 署名-相同方式共享 4.0 国际许可协议）](https://creativecommons.org/licenses/by-sa/4.0/deed.zh-hans)** 发布。

你可以自由复制、分发、改编及用于非商业或商业用途，只需保留署名并以相同协议共享衍生作品。
