### 北航课程报告模板

- 修改自overleaf的北航报告模板，主要是为了在`windows`系统中使用`texlive+vscode`进行本地编译，支持粗体显示
- 编译链：`xelatex -> bibtex -> xelatex*2`
- 不需要本地编译的可以直接使用overleaf中的[原模板](https://www.overleaf.com/latex/templates/buaa-report-latex-template/dfptbrczkpxh)
- `texlive+vscode`环境配置参考知乎[Visual Studio Code (vscode)配置LaTeX](https://zhuanlan.zhihu.com/p/166523064)
- 粗体显示修改自`ctex-fontset-windows.def`，修改原理为伪粗体显示，原理参考知乎[LaTeX 中文字体配置基础指南](https://zhuanlan.zhihu.com/p/538459335)
