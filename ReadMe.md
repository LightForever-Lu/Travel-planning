### 1. 说明
1. 旅游线路规划数学建模，基于定向问题建立MINLP模型，设计两步求解算法，得出最佳线路，需要参观的景点，各个景点最佳参观时间
2. Lingo用来求解算法的第一部分，主要解决混合整数非线性规划问题。
3. Matlab求解算法的第二部分，主要解决线性规划问题，以及得到各种需要输出的结果
4. TOPSIS和层次分析用以产生景点的重要性

### 2. 运行环境及依赖
1. Lingo版本：18.0x64
2. Matlab版本：R2019b
3. CVX版本：CVX2.2
4. CVX解释器：SeduMi

### 3. 运行方式
 1. 先运行Lingo，再运行Matlab
 2. 参数的改变方式已在程序注释中说明
 3. Lingo文件的输出路径要正确加载到Matlab中，请自行调整
 4. <b>Be Careful</b>: 当要改变参数时，Lingo中的total_cost和Matlab中的max_cost要一致，LIngo中的per_num要和Matlab中的per_num一致


### 4. 层次分析：直接调用

### 5. TOPSIS：直接调用