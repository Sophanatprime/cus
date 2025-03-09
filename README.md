# CusTeX

CusTeX 是一个文档类框架。使用者可以方便地设置标题、目录、页面样式（页面几何元素、页眉页脚等）、
图表、背景、水印、边注、脚注、列表、索引、术语表等文档元素，具有强大的可定制性。

目前该宏集还处在早期的开发阶段，很多功能还并不完善。

CUS 需依赖未上传到 CTAN 的 [`lt3ekeys`](https://github.com/Sophanatprime/lt3ekeys) 和 [`texhigh`](https://github.com/Sophanatprime/texhigh) 这两个宏集，需先下载它们。

如果没有把 CUS 放在 TDS 目录下，可先设置环境变量 `TEXINPUTS` 为 `./;./lt3ekeys;./texhigh;./module;./library;../;../lt3ekeys;./texhigh;../module;../library;`，这样 kpathsea 就能找到 `lt3ekeys` 等目录下的文件。

使用 `xelatex cus-cn.tex` 编译三次即可得到文档。索引等内容将自动编译处理。

欢迎提交 [pr](https://github.com/Sophanatprime/cus/pulls) 和 [issue](https://github.com/Sophanatprime/cus/issues)。

license: [LPPL1.3c](http://www.latex-project.org/lppl.txt)

Copyright 2023, 2024 Wenjian Chern

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either
version 1.3c of this license or (at your option) any later
version. This version of this license is in
   http://www.latex-project.org/lppl/lppl-1-3c.txt
and the latest version of this license is in
   http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of
LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained`.

The Current Maintainers of this work is Wenjian Chern (Longaster).
