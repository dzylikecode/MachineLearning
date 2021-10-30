
# KNN

近朱者赤，近墨者黑  <br>

**表达了概念的分类**   <br>

事物可以划分到离它最近距离的概念

然而由于事物的复杂性(有众多因素的影响)，单纯考虑最近，容易“一叶障目”

同时兼顾思考本身是有局限性的，设置一个范围 k

以权重的形式，k 个临近的概念来影响事物的最终认识

**用于回归**   <br>

利用 k 个临近的概念构造出一个新的值(例如取平均)，作为预测值

[make_blobs](https://blog.csdn.net/weixin_44177568/article/details/102213508)
[scatter](https://blog.csdn.net/qiu931110/article/details/68130199)
[pcolormesh](https://doraemonzzz.com/2018/07/15/%E5%88%A9%E7%94%A8matplotlib%E5%BA%93%E4%B8%ADpcolormesh%E4%BD%9C%E5%BD%A9%E5%9B%BE/)
[reshape](https://www.cnblogs.com/shuchang/articles/12242889.html)


## 聚类

### 基本流程

1. 采集数据，并且画出图形观察
2. knn 训练
3. 构造或插值 ， 让 knn 预测 ， 根据充分的预测画出颜色分布图
4. 训练图和预测图比对
5. 给一个数据放入预测图中观察 ， 并比对 knn 预测结果
6. 模型正确率

## 回归

同上

## practice

1. 采集数据
2. 分割数据， 一部分用于训练，一部分用于测验
3. 训练数据
4. 测试数据
