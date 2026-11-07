# 作物产量预测回归模型对比
机器学习课程作业，对比 Ridge、Lasso、KNN、RandomForest、XGBoost 五种回归模型。

## 文件说明
- `croptestnew.ipynb`：完整实验代码（Jupyter Notebook）
- `crop_yield.csv`：原始数据集

## 环境依赖
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
## 运行方式
启动Jupyter Notebook，打开 `croptestnew.ipynb`，逐单元格顺序执行。
运行完成后自动生成7张绘图与 `result_full.csv` 指标文件。

## 实验设置
随机种子 RANDOM_SEED=42，7:3划分训练测试集，5折交叉验证网格搜索调参，以R²为调参指标。
