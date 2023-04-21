若一列二项分布$\{b(k;n,p_n)\}$的参数列满足$\lim_n np_n=\lambda >0$则：
$$
b(k;n,p)\approx \frac{(np)^k}{k!}e^{-np}
$$
记$np=\lambda$则：
$$
b(k;\lambda)\approx \frac{\lambda ^k}{k!}e^{-\lambda}
$$
##### 最可能值
$$
\frac{b(k;\lambda)}{b(k-1;\lambda)}=\frac{\lambda}{k}
$$

最可能值为$[\lambda]$
##### Poisson分布在随机选择下不变
对于每个粒子，有额外p的概率则：
$$
b(k;\lambda,p) = \frac{(\lambda p)^k}{k!}e^{-\lambda p}
$$
##### Poisson过程
1. **独立增量性** 在不相交时段内到达的质点数目相互独立
2. **平衡性** 在长为$t$的时段$[a,a+t)$内到达$k$个质点的概率，只与计时长度$t$有关而与计时起点$a$无关
3. **普通性** 有限的时间区间只会到达有限个质点，充分短的时间内最多只会到达一个质点
$$
P_k(t) = \frac{(\lambda t)^k}{k!}e^{-\lambda t}
$$