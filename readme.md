#数据分析

-------

 ###一. Numpy是什么
 * Numrical Python,数值的Python
 * 开源的科学计算库
 * 是一个python模块，弥补了Python在数值计算方面，能力弱，
 速度慢的不足
 ###二. Numpy都包含哪些东西
 * 丰富的数学函数，强大的多维数组和有意的运算性能
 * 几乎所有的数学函数，而且都是经过优化的，速度很快
 * Numpy 与Scipy、scikit、matplotlib等其他科学计算库
 可以很好地协调工作，因为内部的数据结构几乎相似
 * Numpy可以取代Matlab等工具，允许用户进行快速开发
 的同时完成交互式的原型设计。
 ###三、Numpy数组
 

 ####1.创建数组
 >a = numpy.arrange()
 
> a = numpy.array()
 ####2.多维数组的方法
 >a.dtype 获得d的数据类型
 
 >b = a.astype(destiType) 将a的元素转换为
 destiType，赋值给b的元素数据结构和a一样，只是
 数据类型不一样
 
 >a.shape 获取数组的维度
 ####3.多维数组的索引
    a[索引]
    a[行索引][列索引]
    a[页索引][行索引][列索引]
    a[页索引 ,行索引 ,列索引]
    
 ####4.
 
 ###三、统计
 
 样本：S = [s1,s2,...,sn]
 
 均  值：m = (s1+s2+...+sn)/n
 
 加权平均值：
 
 中位数：应先排序
 
 离  差：D = [s1-m,s2-m,...,sn-m]，离差是一个数组
 
 离差和：sum(D)
 
 方  差：v = ((s1-m)^2 + (s2-m)^2+...+(sn-m)^2)/n
 
 标准差：std = sqrt(v) (方均根离差)(.../n)
 
 numpy.std(数组，ddof=1)，第二个参数是非自由
 
 总体方差和总体标准差：.../n
 
 样本方差和样本标准差：.../(n-1)
 
 
 
 