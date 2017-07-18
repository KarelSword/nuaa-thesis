# nuaa-thesis

nuaa-thesis is a LaTeX style package providing nuaa thesis format for undergraduate, postgraduate and Phd.
This repository is forked from the undergradute LaTeX thesis project [nuaathesis](https://github.com/JackWzh/nuaathesis) developed by [Jack](https://github.com/JackWzh) and HuangDaning, DengXinke, XuTianhao, ShiKun.

nuaa-thesis是一个LaTeX样式包，提供了南京航空航天大学本科、硕士和博士学位论文的样式模板。
该代码库从南航本科LaTeX学位论文模板项目[nuaathesis](https://github.com/JackWzh/nuaathesis)fork而来，nuaathesis由[Jack](https://github.com/JackWzh)和黄大宁、邓欣珂、徐添豪、石坤开发。

The project has just been started and not finished yet.

# Agenda
1. 确认并修改README中关于前人项目作者的描述
2. 完成硕士学位论文模板
3. 完成博士学位论文模板
   3.1 创建

# Contributors
- [Ding Fei](https://github.com/uraplutonium)
- [Wang Jun](https://github.com/traceflight)
- [Hou Guomin](https://github.com/ChenDianGuDeng)
- [Zhong Wei](https://github.com/Veviz)

The following are contents from the README.md in previous nuaathesis project.

[示例文件](https://github.com/jackwzh/nuaathesis/raw/master/sample.pdf)

## 特点

* 模版开发遵照南航官方论文模版排版要求
* 完美支持XeLaTeX进行编译
* 支持Windows / Linux / macOS系统环境

## 快速上手

请使用XeLaTeX对论文进行编译，使用biber编译生成参考文献。

命令行方式1：

```
xelatex -no-pdf sample
biber --debug sample
xelatex sample
xelatex sample # 此处需要运行两遍
```

命令行方式2：

```
latexmk -xelatex sample
```

GUI方式：

请根据个人喜好选择TeXworks、TeXmaker、TeXStudio、Texpad(macOS)、Emacs、Atom等进行编辑和编译。

## 目录结构

`sample.tex`：主文件，此文件仅包含对模版和所有子文件的引用关系，建议实际使用时将文件名更改为论文名称。

`chapter/`：存放具体各个章节的内容。

`figure/`：被引用图片的文件夹，其中nuaa.png为南航图标，不可删除。

`bib/`：存放引用文献库，bib文件可使用常见的文献管理工具（EndNote、Mendeley、Papers等）进行生成。

`nuaathesis.cfg` / `nuaathesis.cls`：模版文件，用户无需改动。
