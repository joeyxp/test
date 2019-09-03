

test

关于这样的简单欧式期权的定价，有经典的Black - Scholes [1] 公式：

\begin{align*}
\text{Call}(S, K, r, \tau, \sigma) & =  \ S \text{N}(d_1) - K\text{e}^{-r\tau}\text{N}(d_2), \\\\[5pt]
d_1 & =  \frac{\text{ln}(S/K) + (r + \frac{1}{2}\sigma^2)\tau}{\sigma \sqrt{\tau}}, \\\\[5pt]
d_2 & =  d_1 - \sigma \sqrt{\tau}. \\\\[5pt]
\end{align*}
