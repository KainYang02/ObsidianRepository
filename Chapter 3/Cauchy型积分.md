设$\Gamma$是$\mathbb C$中可求长 Jordan曲线，$f\in C(\Gamma)$，则可以定义函数：
$$
F_{\Gamma}(z) = \frac{1}{2\pi i}\int_{\Gamma}\frac{f(\xi)}{\xi-z}d\xi,\forall z\in \mathbb C\backslash \Gamma.
$$
则$F_{\Gamma}(z)$各阶导数存在且：
$$
F_{\Gamma}^{(n)}(z)=\frac{n!}{2\pi i}\int_{\Gamma}\frac{f(\xi)}{(\xi-z)^{n+1}}d\xi=\frac{1}{2\pi i}\int_{\Gamma}\frac{\partial^n}{\partial z^n}(\frac{f(\xi)}{\xi-z})d\xi,\forall z\in \mathbb C\backslash \Gamma.
$$