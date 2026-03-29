使用vscode插件LaTeX Workshop。

\#两种编译流程, 根据是否需要引用文献区分：

1.xelatex (不需要引用文献)

2\.xelatex -> bibtex -> xelatex \*2 (需要引用文献), 编译前需要在主文件夹删除main.bbl文件(这个文件时上一次编译时留下的,首次编译无需在意), 否则会在bibtex过程中卡住.

