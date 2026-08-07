+++
date = '2026-06-05T23:50:45-05:00'
draft = false
title = 'Notes'
+++

<!-- Using latex example:
{{<katex>}}
inline: \(\int_{-\infty}^{\infty}dx e^{-(x-\mu)^2/\sigma^2}\)
 
block:

$$
\int_{-\infty}^{\infty}dx e^{-(x-\mu)^2/\sigma^2}
$$ -->

{{<katex>}}

$$
\begin{align*}
\delta\mathcal{L} = &\left(\frac{\partial\mathcal{L}}{\partial\phi} + \sum_{n=1}^\infty (-\boldsymbol{\nabla})^{\otimes n}\cdot\frac{\partial\mathcal{L}}{\partial(\boldsymbol{\nabla}^{\otimes n}\phi)}\right)\delta\phi\\ &+ \sum_{n=1}^{\infty}\boldsymbol{\nabla}\cdot\left(\sum_{k=0}^{n-1}\left((-\boldsymbol{\nabla})^{\otimes k}\cdot \frac{\partial\mathcal{L}}{\partial(\boldsymbol{\nabla}^{\otimes n}\phi)}\right)\cdot \boldsymbol{\nabla}^{\otimes n-1-k}\delta\phi\right)
\end{align*}
$$
