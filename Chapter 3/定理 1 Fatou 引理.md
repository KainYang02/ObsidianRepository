$\{\xi_n\}$是随机变量序列，
1. 如果存在可积随机变量满足$\xi_n\ge \sigma$则：
$$
E(\liminf _n \xi_n)\le \liminf_n E(\xi_n)
$$
2. 如果存在可积随机变量满足$\xi_n\le \tau$则：
$$
E(\limsup_n \xi_n)\ge \limsup_n E(\xi_n)
$$
## 证明
$$
E[\liminf_n(\xi_n -\sigma)]=\lim_n E[\min_{k=n}^{\infty}(\xi_k-\sigma)]\le \liminf_n E(\xi_n-\sigma)
$$
