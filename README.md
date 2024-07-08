\documentclass{article}
\usepackage{amsmath} % Required for mathematical environments and symbols
 
\begin{document}
\title{Following Two Mathematical Equations}
\date{}
\maketitle
 
% Use the 'align' environment to align equations properly
\[
\begin{aligned}
% Left side: equations about 'x'
& \begin{aligned}
x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \\
&= \frac{-2 \pm \sqrt{2^2 - 4 \ast (1) \ast (-8)}}{2 \ast 1} \\
&= \frac{-2 \pm \sqrt{4 + 32}}{2}
\end{aligned}
\quad
% Add horizontal space between left and right sides
&
% Right side: equations about '\varphi_{\sigma}^{\lambda} A_{t}'
\begin{aligned}
\varphi_{\sigma}^{\lambda} A_{t} &= \sum_{\pi \in C_{t}} \operatorname{sgn}(\pi) \varphi_{\sigma}^{\lambda} \varphi_{\pi}^{\lambda} \\
&= \sum_{\tau \in C_{\sigma t}} \operatorname{sgn}(\sigma^{-1} \tau \sigma) \varphi_{\sigma}^{\lambda} \varphi_{\sigma^{-1} \tau \sigma}^{\lambda} \\
&= A_{\sigma t} \varphi_{\sigma}^{\lambda}
\end{aligned}
\end{aligned}
\]
\end{document}
