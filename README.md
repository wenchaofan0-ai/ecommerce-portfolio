# 电商经营分析与 SKU 诊断作品集

温超凡的个人学习项目，使用 AI 辅助整理与实现，不代表企业内部项目或真实经营增长。

## 在线演示

[打开 SKU 经营诊断台](https://wenchaofan0-ai.github.io/ecommerce-portfolio/)

内置 12 个模拟 SKU，支持 CSV 上传、风险阈值调整、商品筛选、图表和诊断结果导出。数据仅在浏览器内处理，无需账号或 API Key。

## 汽车产品原型

- [打开车商线索与车源匹配助手](https://wenchaofan0-ai.github.io/ecommerce-portfolio/used-car-matcher/index.html)：用模拟线索和车源演示需求整理、规则匹配、待追问与人工核验提示。原型未接入真实业务数据。
- [查看项目说明与PRD](projects/03-used-car-lead-matching/README.md)

## 作品附件与代码

- [下载作品附件](portfolio-attachments.zip)：车载手机支架选品 Excel、汇报 PPT、Olist SQL 分析工作簿、SKU 工具。
- [下载完整代码](source-code.zip)：项目说明、可复现 Python / SQL 脚本、分析结果及网页源码。
- [CSV 上传示例](sample_sku_data.csv)

## 项目说明

1. **车载手机支架选品分析**：公开商品样本与模拟经营练习。评论数不等于销量，样本价格不代表当前价格，样本分布不代表市场需求。
2. **Olist SQL 经营分析**：基于 2016—2018 年公开电商数据，按订单口径分析经营表现与配送评价关系。金额为巴西雷亚尔；相关性不代表因果。原始数据不随本仓库分发，来源：[Olist Kaggle 数据集](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)。
3. **SKU 经营诊断台**：全部内置数据为模拟数据，输出规则诊断建议，未验证真实经营收益。

## 本地运行

下载 index.html 后，用 Chrome 或 Edge 打开即可。完整目录与 SQL 重跑步骤见代码包内 README。
