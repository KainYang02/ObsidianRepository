## 基础
[[定理 0 积分变换定理]]
期望的本质是积分：
[[定理 1 单调收敛定理]]
[[定理 1 Fatou 引理]]
[[定理 1 Lebesgue控制收敛定理]]

## 期望
[[定义 0 期望]]
相关性质：
[[性质 0 数学期望的基本性质]]
[[定理 0 独立随机变量的充要条件]]
[[定理 0 独立随机变量的期望]]
[[定理 2 Cauchy-Schwarz不等式]]
[[定理 6 多个随机变量和的期望]]
[[定理 6 全期望公式*]]

## 方差
[[定义 2 平方可积]]
[[定义 2 方差&标准差]]
[[定义 3 标准化随机变量]]
性质：
[[定理 6 多个随机变量和的方差]]

## 协方差和相关系数
[[定义 4 协方差]]
[[定义 4 协方差阵]]
[[定义 5 相关系数]]
性质：
[[定理 5 相关系数的范围]]
[[定理 5 相关性的等价条件*]]

## 万恶的“条件”
[[定义 6 条件分布]]
[[定义 6 条件期望]]
[[定义 6 条件方差]]

## 抽象死我
[[定义 6 阶梯随机变量]]

## 其他
[[定理 5 独立和不相关]]

## 分布的期望&方差
|名称|分布|期望|方差|
|----|----|----|----|
|[[定义 1 几何分布]]|$GE(p)\sim (1-p)^{k-1}p, k\in\mathbb N$|||
|[[定义 1 Bernoulli分布]]|$B(n,p)\sim \binom{n}{k}p^{k}(1-p)^{n-k}, k\in[0, n]$|||
|[[定义 1 Pascal分布]]|$Pas(r,p)\sim\binom{k-1}{r-1}p^r(1-p)^{k-r}, k\ge r$|||
|[[定义 2 均匀分布 U]]|$U(a,b)\sim \frac{1}{b-a}, x\in (a, b)$|||
|[[定义 2 正态分布 N]]|$N(a,\sigma^2)\sim \frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-a)^2}{2\sigma^2}},x\in\mathbb R$|||
|[[定义 2 指数分布]]|$Exp(\lambda)\sim \lambda e^{-\lambda x}, x\in [0, \infty)$|||
|[[定义 2 Gamma分布]]|$\Gamma(\lambda, r)\sim \frac{\lambda^r}{\Gamma(r)}x^{r-1}e^{-\lambda x}, x\in [0, \infty)$|||
|[[定义 2 Poisson分布]]|$Poi(\lambda)\sim \frac{\lambda^k}{k!}e^{-\lambda x}, x\in[0,\infty)$|||
|[[定义 6 Cauchy分布C]]|$C(\lambda, a)=\frac{1}{\pi}\frac{\lambda}{\lambda^2+(x-a)^2}, x\in\mathbb R$|||
|[[定义 7 Beta分布]]|$Beta(\alpha, \beta)\sim \frac{x^{\alpha-1}(1-x)^{\beta-1}}{B(\alpha, \beta)}, x\in (0, 1)$|||

|名称|分布|期望|方差|
|----|----|----|----|
|[[定义 4 二维正态分布]]|$N(a_1, \sigma^2_1, a_2, \sigma^2_2, r)=\frac{1}{2\pi\sigma_1\sigma_2\sqrt{1-r^2}}e^{-\frac{1}{2(1-r^2)}[\frac{(x-a_1^2)}{\sigma_1^2}-\frac{r(x-a_1)(y-a_2)}{\sigma_1\sigma_2}+\frac{(y-a_2)^2}{\sigma_2^2}]},(x,y)\in \mathbb R^2$|||
|[[定义 4 二维均匀分布]]|$U(D)\sim \frac{1}{m(D)},x\in D$|||
|[[定义 7 n个自由度的X2分布]]|$\mathcal X^2\sim\Gamma(\frac{n}{2}, \frac{1}{2})$|||
|[[定义 7 最大最小分布]]||||

