# 互评作业1: 数据探索性分析与数据预处理
 
# 作业要求
1. 问题描述：

    本次作业中，自行选择2个数据集进行探索性分析与预处理。

2. 数据集

    可选数据集包括：
    ```
    Consumer & Visitor Insights For Neighborhoods

    Wine Reviews

    Oakland Crime Statistics 2011 to 2016

    Chicago Building Violations

    Trending YouTube Video Statistics

    Melbourne Airbnb Open Data

    MLB Pitch Data 2015-2018
    ```

3. 数据分析要求

    3.1 数据可视化和摘要

    * 数据摘要：

      标称属性，给出每个可能聚会的频数

      数值属性，给出5数概括及缺失值的个数

    * 数据可视化：

      使用直方图、盒图等检查数据分布及离群点

    3.2 数据缺失的处理

        观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:
        将缺失部分剔除
        用最高频率值来填补缺失值
        通过属性的相关关系来填补缺失值
        通过数据对象之间的相似性来填补缺失值
        注意：在处理后，要可视化地对比新旧数据集。
4. 提交内容

    * 分析过程报告（PDF格式）

    * 程序所在代码仓库地址（建议使用Github或码云），仓库中应包含完整的处理数据的程序和使用说明

    * 所选择的数据集应在仓库的README文件中说明

    * 相关的数据文件不要上传到代码仓库中

    (建议：使用Jupyter Notebook将分析报告和代码组织在一起，使用Notebook的导出功能将报告导出为PDF格式的文件上传到乐学)

# 选择的数据集介绍

## Wine Reviews [(download)](https://www.kaggle.com/zynicide/wine-reviews)

* Description: 

    130k wine reviews with variety, location, winery, price, and description.

* Contents:
    ```
    winemag-data-130k-v2.csv: contains 10 columns and 130k rows of wine reviews.

    winemag-data_first150k.csv: contains 10 columns and 150k rows of wine reviews.

    winemag-data-130k-v2.json: contains 6919 nodes of wine reviews.
    ```

## Oakland Crime Statistics 2011 to 2016 [(download)](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016?select=records-for-2012.csv)

* Description: 

    This is a dataset hosted by the city of Oakland in California. The organization has an open data platform found here and they update their information according to the amount of data that is brought in. Explore Oakland's Data using Kaggle and all of the data sources available through the city of Oakland organization page!

* Contents:
    ```
    records-for-2011.csv
    records-for-2012.csv
    records-for-2013.csv
    records-for-2014.csv
    records-for-2015.csv
    records-for-2016.csv
    ```

# 使用说明
下载数据集并上传至main.ipynb文件所在目录，然后使用jupyter notebook 打开main.ipynb文件，运行指定cell，即可得到相应可视化结果。
