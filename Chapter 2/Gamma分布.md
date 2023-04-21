对于由$\lambda,t$决定的[[Poisson分布]]$P_k(t)=\frac{(\lambda t)^k}{k!}e^{-\lambda t}$，我们考虑**第$r$个质点到达的时间**$\eta_r$的概率分布函数：
$$
F(t) = P(\eta_r < t) = P(\xi_t\ge r)=\sum_{k=r}^{\infty}P_k(t)= \sum_{k=r}^{\infty}\frac{(\lambda t)^k}{k!}e^{-\lambda t}
$$
对其求导得到$\eta$的概率密度函数：
$$
P(\eta = t) =\frac{\lambda ^r}{(r-1)!}t^{r-1}e^{-\lambda t}
$$
回忆$\Gamma$函数$\Gamma(r)=\int_{-\infty}^{+\infty}x^{r-1}e^{-x}dx$满足：
* $\Gamma(r)=r\Gamma(r-1)$
* $\Gamma(1)=1, \Gamma(n+1)=n!$
* $\Gamma(\frac{1}{2})=\sqrt\pi$
故$eta$的概率密度函数可写为：
$$
P(\eta =x) = \frac{\lambda ^r}{\Gamma(r)}x^{r-1}e^{-\lambda x}
$$
该函数对应的分布称为$\Gamma(\lambda,r)$分布