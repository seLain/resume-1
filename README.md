This is a fork from [sb2nov/resume](https://github.com/sb2nov/resume).
The template format was modified according to my personal needs.
Feel free to reuse this format if it fits you.
If you are looking for the orginal copy with elegant design, please visit [sb2nov/resume](https://github.com/sb2nov/resume).

## Setup and Compilation (on Windows)

To compile this template on Windows, it is recommended to install [MiKTex](https://miktex.org/).

Then simply do 

```
pdflatex resume.tex
```

The compilation process might notify necessary installation of additional packages.
Just click `install` and let it perform automatically.
If the process stops somewhere on the command line, just press `Enter` to continue.
The result will be `resume.pdf`, which is a PDF version of your resume.

## 中文版本 (zhTW Chinese Version)

如果需要在 resume 中使用中文, 請改用 resume_zhTW.tex 版模.

版模中採用 CJKutf8 套件. 所有內容中都可以使用中文. 如果需要更改字體, 請找到以下

```latex
\begin{document}
\begin{CJK}{UTF8}{bkai}
```

修改其中的 `bkai` (楷體), 改用其他在你的 LaTeX 環境中可用字體, 例如 `bsmi` (細明體).

編譯時執行 

```
pdflatex resume_zhTW.tex
```

產出的檔案則為 `resume_zhTW.pdf`