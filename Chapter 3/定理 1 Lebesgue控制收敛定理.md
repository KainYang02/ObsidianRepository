$\{\xi_n\}$为随机变量序列，$\exists \eta$满足$|\xi_n|\le \eta$，且$\lim_n \xi_n = \xi$，则随机变量$\xi$可积且：
$$
\lim_nE(\xi_n)=E(\xi)
$$
由[[定理 1 Fatou 引理]]：
$$
E(\xi)\le \liminf_nE(\xi_n)\le \limsup_n E(\xi_n)\le E(\xi)
$$
故$E(\xi)$存在，$\xi$可积