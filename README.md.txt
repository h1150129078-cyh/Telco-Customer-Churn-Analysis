# Telco Customer Churn Prediction (电信客户流失预测)

## 📖 项目概述
通过机器学习模型预测电信客户流失风险，并识别关键影响因素，为制定客户挽留策略提供数据支持。

**数据集来源**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## 🛠️ 技术栈
- **语言**: Python
- **库**: Pandas, NumPy, Scikit-learn, XGBoost, CatBoost, Matplotlib, Seaborn, Plotly

## 📊 工作流程
1.  **数据清洗**: 处理缺失值与异常值（如 `TotalCharges` 列），转换数据类型。
2.  **探索性分析**: 发现月合同、高费用、无技术支持服务的客户流失率更高。
3.  **特征工程**: 对分类变量进行编码（标签编码与独热编码）。
4.  **建模与评估**: 比较多种模型（如逻辑回归、随机森林、XGBoost等），最终集成模型AUC达 **0.864**。

## 💡 核心洞察与策略
- **策略1**: 鼓励客户签订长期合同，降低月度合约比例。
- **策略2**: 为高月费客户提供专属增值服务与VIP支持。
- **策略3**: 将“技术支持”、“在线安全”等服务打包进核心套餐。
- **策略4**: 利用模型精准定位高风险客户，进行低成本定向挽留。

## 📁 文件说明
- `notebooks/churn_analysis.ipynb`: 完整的数据分析、建模与评估代码。
- `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`: 从Kaggle获取的原始数据。
- `visualization`: 项目成果预览图（例如热力图、模型比较图或ROC曲线）。

---
*本项目为数据分析学习作品，旨在展示从数据清洗到模型部署的完整流程。*