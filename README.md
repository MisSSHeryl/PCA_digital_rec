# PCA_digital_recognition

使用kaggle数据集train.csv 使用80%训练，10%交叉验证，10%测试。

KNN:
dRPCA方法进行降维 ModelTrain训练模型

SVM:getOptimalAccuracy方法通过改变主成分数目查找准确率最高的模型
    
    preDRSVM预测测试数据
    
    analyse_data(dataMat):# 分析数据,看数据是否满足要求（通过这些来检测数据的相关性，考虑在分类的时候提取出重要的特征）
    
    详情见代码SVM_digit_recognize.ipynb

