内容：

请使用以下残差模型，推导相应的雅可比，并在F-LOAM或A-LOAM基于该模型，实现解析式求导。

线特征残差：
$$
d_{\mathcal{E}}=\frac{\left|\left(\tilde{p}_{i}-p_{b}\right) \times\left(\tilde{p}_{i}-p_{a}\right)\right|}{\left|p_{a}-p_{b}\right|}
$$
面特征残差：

评价标准：

1）及格：推导雅可比，且结果正确；

2）良好：在及格的基础上，编程实现新模型的解析式求导，且结果正常；

3）优秀：在良好的基础上，给出运行结果的精度评测结果（基于evo）。



