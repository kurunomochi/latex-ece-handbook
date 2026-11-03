# LaTeX 实验写作手册
一份面向 ECE 与计算机系统学习者的中文入门教程。九节练习从第一份中文 PDF 讲到 RC 电路公式、图表、代码清单、文献和 CSAPP 实验报告。

## 阅读
下载本仓库后用浏览器打开 [index.html](index.html)，即可离线阅读、复制代码、下载示例和打印手册。

## 动手
- [第一份中文 PDF](examples/first-pdf/main.tex) 可在 Overleaf 空白项目中选择 XeLaTeX 编译。
- [CSAPP 完整报告](examples/csapp-report/) 包含 main.tex 和 refs.bib。将两个文件放入同一个项目，在该目录运行以下命令。需要包含 ctex、Fandol 字体、biblatex、Biber 和 latexmk 的 TeX 环境。

~~~sh
latexmk -xelatex main.tex
~~~

报告中的偏移量是演算示例，请用自己的测量结果替换。
