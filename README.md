<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/tbanner-light.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/tbanner-dark.svg">
    <img alt="Quarkdown 横幅" src="https://github.com/user-attachments/assets/68dfb3bf-9466-44f3-b220-7067322c4887">
  </picture>
  <br>
  <a href="https://quarkdown.com/wiki"><img alt="Wiki" src="https://img.shields.io/badge/wiki-阅读-darkcyan"></a>
  <a href="https://quarkdown.com/docs"><img alt="Docs" src="https://img.shields.io/badge/docs-阅读-blue"></a>
  <a href="https://github.com/iamgio/quarkdown/releases/latest"><img alt="Release" src="https://img.shields.io/github/v/release/iamgio/quarkdown?color=mediumseagreen"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=quarkdown.quarkdown-vscode"><img alt="Visual Studio Code 扩展版本" src="https://img.shields.io/github/v/release/quarkdown-labs/quarkdown-vscode?color=blue&label=vscode"></a>
  <a href="https://pinterest.github.io/ktlint"><img alt="FMT: Ktlint" src="https://img.shields.io/badge/fmt-ktlint-7f52ff?logo=kotlin&logoColor=f5f5f5"></a>
  <a href="https://www.codefactor.io/repository/github/iamgio/quarkdown"><img alt="CodeFactor" src="https://www.codefactor.io/repository/github/iamgio/quarkdown/badge/main"></a>
  <br><br>
  <a href="https://trendshift.io/repositories/13945" target="_blank"><img src="https://trendshift.io/api/badge/repositories/13945" alt="iamgio%2Fquarkdown | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
  <br>
  <a href="https://www.producthunt.com/products/quarkdown?embed=true&amp;utm_source=badge-featured&amp;utm_medium=badge&amp;utm_campaign=badge-quarkdown" target="_blank" rel="noopener noreferrer"><img alt="Quarkdown - 拥有超能力的 Markdown：从灵感到精美文档。 | Product Hunt" width="250" height="54" src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1130470&amp;theme=light&amp;t=1777150043744"></a>
  <br>
</p>

  <p align="center">
  <strong>发行版</strong>
  <br>
  <a href="https://github.com/iamgio/quarkdown/releases/tag/latest">最新预览版</a>
  &nbsp; | &nbsp;
  <strong><a href="https://github.com/iamgio/quarkdown/releases/latest">稳定版</a></strong>&nbsp;
  <br>
  <hr>
</p>

# 目录

- [目录](#目录)
- [关于](#关于)
  - [如你所期望般简单...](#如你所期望般简单)
- [输出目标](#输出目标)
- [对比](#对比)
- [快速上手](#快速上手)
  - [安装](#安装)
    - [安装脚本 (Linux/macOS)](#安装脚本-linuxmacos)
    - [Homebrew (Linux/macOS)](#homebrew-linuxmacos)
    - [安装脚本 (Windows)](#安装脚本-windows)
    - [Scoop (Windows)](#scoop-windows)
    - [GitHub Actions](#github-actions)
    - [手动安装](#手动安装)
  - [快速入门 🆕](#快速入门-)
  - [创建项目](#创建项目)
  - [编译](#编译)
      - [选项](#选项)
  - [示例文档](#示例文档)
  - [贡献](#贡献)
  - [赞助者](#赞助者)
  - [理念](#理念)
  - [许可证](#许可证)
  - [脚注](#脚注)

&nbsp;

# 关于

Quarkdown 是一个基于 Markdown 的现代排版系统，专为**多用途**而设计。它允许单个项目无缝编译为印刷级书籍、学术论文、知识库或交互式演示文稿。
这一切都归功于对 Markdown 极其强大的图灵完备扩展，确保你的想法能自动化为文档。

&nbsp;

<p align="center">
  <img src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/paged-demo.png" alt="论文演示">
  <p align="center"><em>原始出处：<a href="https://arxiv.org/abs/1706.03762v7">Attention Is All You Need</a></em></p>
</p>

<br>

作为 CommonMark 和 GFM 的扩展，Quarkdown Flavor 为 Markdown 引入了**函数**，以及许多其他语法扩展。

<br>

> 这是一个函数调用：
> ```
> .somefunction {arg1} {arg2}
>     Body argument
> ```

<br>

**可能性是无限的**，这得益于不断扩展的[标准库](https://github.com/iamgio/quarkdown/blob/main/quarkdown-stdlib/src/main/kotlin/com/quarkdown/stdlib)，
它提供了布局构建器、I/O、数学运算、条件语句和循环。

**还不够？** 你仍然可以在 Markdown 中定义自己的函数和变量。
你甚至可以为所有人创建出色的库。

<br>

> ```
> .function {greet}
>     to from:
>     **Hello, .to** from .from!
>
> .greet {world} from:{iamgio}
> ```
> 结果：**Hello, world** from iamgio!

<br>

这种开箱即用的脚本支持，为复杂和动态的内容打开了大门，而这些是纯 Markdown 无法实现的。

结合实时预览、:zap: 快速的编译速度和强大的 [VS Code 扩展](https://marketplace.visualstudio.com/items?itemName=quarkdown.quarkdown-vscode)，无论是学术论文、书籍、知识库还是交互式演示文稿，Quarkdown 都能轻松胜任。

&nbsp;

<p align="center">
<img src="https://raw.githubusercontent.com/quarkdown-labs/quarkdown-vscode/refs/heads/project-files/live-preview.gif" alt="实时预览" />
</p>

&nbsp;

---

<h2 align="center">在找什么？</h2>
<p align="center">
  <strong>
    查看 <a href="https://quarkdown.com/wiki" target="_blank">Wiki</a>
  </strong>
  开始使用并了解更多关于该语言及其功能的信息！
</p>

---

&nbsp;

## 如你所期望般简单...

<p align="center">
  <img src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/code-paper.png" alt="论文代码演示">
  <p align="center"><em>灵感来源：<a href="https://news.mit.edu/2025/x-ray-flashes-nearby-supermassive-black-hole-accelerate-mysteriously-0113">附近超大质量黑洞的 X 射线闪光神秘加速</a></em></p>
</p>

&nbsp;

<h2 align="right">...如你所需要般强大。</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/code-chart.png" alt="图表代码演示">
</p>

# 输出目标

- **HTML**
  - [X] **普通模式**
    类似 Notion/Obsidian 的连续流式排版，非常适合静态网站和知识管理 - 查看作者的[个人网站](https://iamgio.eu/)。

  - [X] **分页模式** <sup>通过 [paged.js](https://pagedjs.org)</sup>
    非常适合论文、文章和书籍 - 查看[演示文档](https://github.com/quarkdown-labs/generated/blob/main/mock/paperwhite_latex.pdf)。

  - [X] **幻灯片模式** <sup>通过 [reveal.js](https://revealjs.com)</sup>
    非常适合交互式演示文稿。

  - [X] **文档模式**
    非常适合 Wiki、技术文档和大型知识库 - 查看 [Quarkdown 的 Wiki](https://quarkdown.com/wiki)。

- **PDF**
  - [X] HTML 支持的所有文档类型和功能在导出为 PDF 时同样受支持。

- **纯文本**

所需的文档类型可以通过在源文件中调用 [`.doctype` 函数](https://quarkdown.com/wiki/document-types)来设置：
- `.doctype {plain}` （默认）
- `.doctype {paged}`
- `.doctype {slides}`
- `.doctype {docs}`

# 对比

|                       |     Quarkdown      |       LaTeX        |       Typst        |      AsciiDoc      |        MDX         |
|-----------------------|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|
| 简洁易读  | :white_check_mark: |        :x:         | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| 完整文档控制[^control] | :white_check_mark: | :white_check_mark: | :white_check_mark: |        :x:         |        :x:         |
| 脚本支持             | :white_check_mark: |      部分支持       | :white_check_mark: |        :x:         | :white_check_mark: |
| 书籍/文章导出   | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |    第三方     |
| 演示文稿导出   | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |    第三方     |
| 静态站点导出    | :white_check_mark: |        :x:         |    实验性    | :white_check_mark: | :white_check_mark: |
| 文档/Wiki 导出      | :white_check_mark: |        :x:         |        :x:         | :white_check_mark: | :white_check_mark: |
| 学习曲线        |   :green_circle:   |    :red_circle:    |  :orange_circle:   |   :green_circle:   |   :green_circle:   |
| 输出目标               |   HTML, PDF, TXT   |  PDF, PostScript   |     HTML, PDF      |  HTML, PDF, ePub   |        HTML        |

[^control]: 通过语言本身自定义文档及其输出产物属性的能力。

<table>
  <thead>
    <tr>
      <th>LaTeX</th>
      <th>Quarkdown</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>

```latex
\tableofcontents

\section{Section}

\subsection{Subsection}

\begin{enumerate}
    \item \textbf{First} item
    \item \textbf{Second} item
\end{itemize}

\begin{center}
    This text is \textit{centered}.
\end{center}

\begin{figure}[!h]
    \centering
    \begin{subfigure}[b]
        \includegraphics[width=0.3\linewidth]{img1.png}
    \end{subfigure}
    \begin{subfigure}[b]
        \includegraphics[width=0.3\linewidth]{img2.png}
    \end{subfigure}
    \begin{subfigure}[b]
        \includegraphics[width=0.3\linewidth]{img3.png}
    \end{subfigure}
\end{figure}
```

</td>
<td>

```markdown
.tableofcontents

# Section

## Subsection

1. **First** item
2. **Second** item

.center
    This text is _centered_.

.row alignment:{spacebetween}
    ![Image 1](img1.png)

    ![Image 2](img2.png)
    
    ![Image 3](img3.png)
```

</td>
</tr>
</tbody>
</table>

&nbsp;

# 快速上手

## 安装

### 安装脚本 (Linux/macOS)

```shell
curl -fsSL https://raw.githubusercontent.com/quarkdown-labs/get-quarkdown/refs/heads/main/install.sh | sudo env "PATH=$PATH" bash
```

Root 权限允许脚本将 Quarkdown 安装到 `/opt/quarkdown`，并将其包装脚本安装到 `/usr/local/bin/quarkdown`。
如果缺少 Java 17、Node.js 和 npm，将使用系统包管理器自动安装。

如需更多安装选项，请查看 [get-quarkdown](https://github.com/quarkdown-labs/get-quarkdown)。

### Homebrew (Linux/macOS)

```shell
brew install quarkdown-labs/quarkdown/quarkdown
```

### 安装脚本 (Windows)

```powershell
irm https://raw.githubusercontent.com/quarkdown-labs/get-quarkdown/refs/heads/main/install.ps1 | iex
```

### Scoop (Windows)

```shell
scoop bucket add java
scoop bucket add quarkdown https://github.com/quarkdown-labs/scoop-quarkdown
scoop install quarkdown
```

### GitHub Actions

请查看 [setup-quarkdown](https://github.com/quarkdown-labs/setup-quarkdown)，轻松将 Quarkdown 集成到你的 GitHub Actions 工作流中。

### 手动安装

<details>
<summary>手动安装说明</summary>

从[最新稳定版](https://github.com/iamgio/quarkdown/releases/latest)下载 `quarkdown.zip` 并解压，
或使用 `gradlew installDist` 构建。

可选：将 `<install_dir>/bin` 添加到你的 `PATH` 环境变量中，以便更方便地访问 Quarkdown。

依赖要求：
- Java 17 或更高版本
- （仅 PDF 导出需要）Node.js、npm、Puppeteer。详见 [*PDF 导出*](https://quarkdown.com/wiki/pdf-export)。

</details>

&nbsp;

## 快速入门 🆕

新用户？你将在**[快速入门指南](https://quarkdown.com/wiki/quickstart)**中找到**所需的一切**，让你的第一个文档焕发生机！

&nbsp;

## 创建项目

**`quarkdown create [directory]`** 将启动基于提示的项目向导，让你比以往更快地
搭建新的 Quarkdown 项目，所有[元数据](https://quarkdown.com/wiki/document-metadata)和初始内容均已就绪。

有关项目创建器的更多信息，请查看其 [Wiki 页面](https://quarkdown.com/wiki/cli-project-creator)。

或者，你也可以手动创建 `.qd` 源文件并从那里开始。

&nbsp;

## 编译

运行 **`quarkdown c file.qd`** 将编译给定文件并将输出保存到文件。

> 如果项目由多个源文件组成，目标文件必须是根文件，即包含其他文件的那个文件。
>
> - [如何包含其他文件？](https://quarkdown.com/wiki/including-other-quarkdown-files)

如果你想先熟悉 Quarkdown，`quarkdown repl` 可以让你在交互式 REPL 模式下体验。

#### 选项

最常用的选项有：

- **`-p`** 或 **`--preview`**：编译后启用自动内容重新加载。

- **`-w`** 或 **`--watch`**：每当源目录中的文件发生更改时重新编译。

> [!TIP]
> 结合 `-p -w` 即可实现***实时预览***！

- **`--pdf`**：生成 PDF 文件。详见 Wiki 中的 [*PDF 导出*](https://quarkdown.com/wiki/pdf-export) 页面。

完整的选项列表，请查看 [CLI 选项](https://quarkdown.com/wiki/cli-options) Wiki 页面。

&nbsp;

---

&nbsp;

## 示例文档

&nbsp;

<p align="center">
  <img width="550" src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/mock-demo.png" alt="示例文档演示">
</p>

***Mock*** 是用 Quarkdown 编写的，是该语言提供的视觉元素的全面集合，
非常适合探索和理解其核心功能 — 同时还能以页面或幻灯片的形式动手实践和实验。

- 该文档的源文件可在 [`mock`](https://github.com/iamgio/quarkdown/blob/main/mock) 目录中找到，可通过 `quarkdown c mock/main.qd -p` 编译。
- 所有主题组合生成的 PDF 产物可在 [`generated`](https://github.com/quarkdown-labs/generated) 仓库中查看。  

## 贡献

欢迎贡献！请查看 [CONTRIBUTING.md](https://github.com/iamgio/quarkdown/blob/main/CONTRIBUTING.md) 了解如何通过 issue 或 pull request 进行贡献。

## 赞助者

特别感谢所有[支持此项目](https://github.com/sponsors/iamgio)的赞助者！

<p align="center">
<a href="https://falconer.com"><img src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/sponsors/falconer.jpeg" alt="Falconer" width="350"></a>
</p>

<p align="center">
  <a href="https://github.com/RayOffiah"><img src="https://avatars.githubusercontent.com/u/77050471?v=4" alt="RayOffiah" width="90"></a>
</p>

<p align="center">
  <a href="https://github.com/vitto4"><img src="https://avatars.githubusercontent.com/u/128498605?v=4" alt="vitto4" width="60"></a>
</p>

<p align="center">
  <a href="https://github.com/LunaBluee"><img src="https://avatars.githubusercontent.com/u/145209701?v=4" alt="LunaBluee" width="35"></a>&nbsp;
  <a href="https://github.com/dcopia"><img src="https://avatars.githubusercontent.com/u/162327812?v=4" alt="dcopia" width="35"></a>
  <a href="https://github.com/Pallandos"><img src="https://avatars.githubusercontent.com/u/146179143?v=4" alt="Pallandos" width="35"></a>
  <a href="https://github.com/imogenxingren"><img src="https://avatars.githubusercontent.com/u/36161957?v=4" alt="imogenxingren" width="35"></a>
  <a href="https://github.com/serkonda7"><img src="https://avatars.githubusercontent.com/u/40118727?v=4" alt="serkonda7" width="35"></a>
</p>

## 理念

Logo 参考了原始的 [Markdown 图标](https://github.com/dcurtis/markdown-mark)，重点突出了 Quarkdown 的完整性、
丰富的功能和自定义选项，球体周围旋转的箭头强调了这一点。

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/ticon-light.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/ticon-dark.svg">
    <img alt="Quarkdown 图标" src="https://raw.githubusercontent.com/iamgio/quarkdown/project-files/images/ticon-dark.svg">
  </picture>
</p>

那个可能被误认为星球的东西，实际上是一个**夸克**，或者更准确地说，是一个**下夸克**，
一种构成物质主要成分的基本粒子：它们赋予了我们已知所有复杂结构以生命，
同时也是现存最轻的物体之一。

这正是 **Quarkdown** 所基于的理念。 

## 许可证

默认情况下，Quarkdown 及其模块采用 [GNU GPLv3](https://github.com/iamgio/quarkdown/blob/main/LICENSE) 许可证，但包含自己 `LICENSE` 文件的模块除外：
CLI（`quarkdown-cli`）和语言服务器（`quarkdown-lsp`）模块及二进制文件采用 GNU AGPLv3 许可证。

## 脚注

---
*README.md 汉化自 https://github.com/iamgio/quarkdown*
