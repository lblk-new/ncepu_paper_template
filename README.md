# ncepu_paper_template
华北电力大学本科毕业论文latex模板







暂时没有目录和封面模板（对于想要使用tex实现目录和封面的人来说，本项目不是一个好的选择）

所以应该使用word对学校的封面和目录模板进行填写，完成后几个文件都输出成pdf一起打印，足球场旁的书虫书店对此有足够丰富的经验，能够将几份文件叠加成标准的胶状格式。

本文包括：

中英文摘要

正文

参考文献

致谢

附录





# 使用方法：

### 五级标题

\section                     此为章节

\subsection

\subsubsection

\paragraph

\subparagraph

##### !ps:请注意在每章节开头前使用\newpage换页



### 引用：(bib+cite)

\cite{a}

##### !应注意引用时如果是连续引用多篇文章,比如连引a、b、c,应使用\cite{a,b,c}形式



### 定理环境(th1)

可另行定义定理环境，自行决定

\begin{th1}[定理名称]

\end{th1}



### 注释

\begin{comment}

\end{comment}

### 插图


\includegraphics[]{}

请自行脑补上述命令的使用方法，为添加图注，请使用figure环境对其进行包裹并用caption进行图注，详见：

[图表环境说明](https://github.com/WenboSheng/epslatex-cn)



### 编译方法

xelatex>bib>xelatex>xelatex

可参考[vscode配置latex教程](https://lblk.github.io/2021/04/07/vs-latex-workshop/)











### 有关查重

查重是一种特产，专门排斥latex，所以查重时需要先输出为pdf，然后用word打开pdf使之转化为word文档，再进行上传和查重。请放心，知网查重可以提交pdf









# 6.12更新：

添加了公式编号环境，建议在论文写作过程中全文使用equation环境而不是\\[-\\]或$$-$$

添加了figure和table 环境下的注释（即图注、表注）