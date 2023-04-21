对于**位置参数**$a$和**形状参数**$\sigma$，可以写出正态分布$N(a,\sigma^2)：
$$
\varphi_{a,\sigma}(x)=\frac{1}{\sigma \sqrt {2\pi}}e^{-\frac{(x-a)^2}{2\sigma^2}}
$$
注：$N(0,1)$称为标准正态分布/Gauss分布，简写为$\varphi(x)$。
>下证明这确实是一个密度函数

$$
I = \int_{-\infty}^{+\infty}\varphi_{a,\sigma}(x)dx
$$
$$
I^2 = \frac{1}{2\pi}\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}e^{-\frac{x^2 + y^2}2{}}
$$
$$
I^2 = \frac{1}{2\pi}\int_{0}^{2\pi} d\theta\int_{0}^{\infty}re^{-\frac{r^2}{2}}dr=1
$$
>$3\sigma$原则：通常认为$\xi$只取$[a-3\sigma,a+3\sigma]$，误差几率不超过千分之三$P(|a-\xi|\le 3\sigma)=0.9974$

