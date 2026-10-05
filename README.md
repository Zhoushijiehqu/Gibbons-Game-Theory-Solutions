# 吉本斯《博弈论基础》第 1–4 章习题答案详解

本仓库提供第 1–4 章共 60 道习题的中文推导、图表辅助、XeLaTeX 源码与编译后的 PDF。答案由若光ovo 与 ChatGPT 整理，供学习和交流使用。

## 文件

| 文件 | 内容 |
| --- | --- |
| `吉本斯博弈论基础_第1-4章习题答案详解.pdf` | 编译后的答案详解 |
| `latex/main.tex` | 主 TeX 文件 |
| `latex/preamble.tex` | 宏包、版式和绘图设置 |
| `latex/chapters/` | 第 1–4 章答案源文件 |

本仓库不包含教材章节拆分文件夹或原题 PDF。习题依据理查德·吉本斯《博弈论基础》整理；题目内容的著作权仍归原作者及相应权利人。

## 编译

安装支持中文的 TeX Live 后，在 `latex/` 目录连续运行两遍：

```sh
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

## 许可

本仓库原创解答文字、图表与 TeX 排版源码采用 MIT License。教材题目内容不包含在该许可授权范围内。

联系邮箱：a15759219744@163.com
