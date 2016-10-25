 

\documentclass{article}
\usepackage{CJKutf8}
% use one of bsmi(trad Chinese), gbsn(simp Chinese), min(Japanese), mj(Korean)
\newcommand{\cntext}[1]{\begin{CJK}{UTF8}{gbsn}#1\end{CJK}}



\begin{document}

\begin{CJK}{UTF8}{gkai}
这是一个楷体中文测试，处理简体字。
\end{CJK}


\begin{CJK}{UTF8}{gbsn}
这是一个宋体中文测试，处理简体字。
\end{CJK}


\begin{CJK}{UTF8}{bkai}
這是一個big5編碼的楷體中文測試，處理繁體文字。
\end{CJK}


\begin{CJK}{UTF8}{bsmi}
這是一個个big5編碼的明體中文測試，處理繁體文字。
\end{CJK}

\cntext{中文}

\end{document}
