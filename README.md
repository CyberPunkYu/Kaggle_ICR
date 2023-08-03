# Kaggle_ICR
ICR - Identifying Age-Related Conditions

## 类型
- 数据挖掘
- 匿名特征工程
- 表格数据特征
- 二分类


## 任务
- greeks元数据感觉是有用的，虽然测试集没有这部分特征，但是通过训练集应该也能够预测元特征生成新的数据集，从而提高模型的泛化能力
- 突然发现greek里面的Gamma完全可以100%预测出Class，所以通过Gamma来预测Class没有意义，但是预测Beta和Delta预测准确率确实有点低了（未经过调参）