 数据分析的知识点

数据挖掘的核心：分类、聚类、预测、关联分析等

元数据：描述其他数据的数据，也称为中介数据

数据元：最小数据单元

Knowledge Discovery Database：数据预处理中对数据进行：数据清洗、数据集成、数据变换

.. figure:: ../images/11.jpg
用户是数据分析的出发点，用户画像建模步骤，给用户打标签也是用户消费行为分析，可以从用户标签、消费标签、行为标签、行为标签、内容分析4个维度进行标签划分。

.. figure:: ../images/12.jpg
按照数据流处理的阶段来划分用户画像建模的过程，可以分为数据层、算法层、业务层  

.. figure:: ../images/13.jpg
数据清洗的规则：“完全合一”
完整性：单条数据是否存在空值，统计的字段是否完善(对于缺失值：可以删除缺失的记录|使用当前列的均值|使用当前列出现频率最高的数据 对于空行，可以使用dropna()删除)
全面性：检查数据定义、单位标识、数值本身
合法性：数据的类型、内容、大小的合法性
唯一性：数据是否存在重复记录(一个列有多个参数，用split拆分|drop_duplicates()删除重复数据)  

.. figure:: ../images/14.jpg

数据集成的两种架构: ELT and ETL
Extract->Load->Transform  Extract->Transform->Load (Kettle Pentaho\DataX Ali)

.. figure:: ../images/17.jpg

.. figure:: ../images/16.jpg

Apache opensource software: Sqoop
Sqoop用来在Hadoop和关系型数据库中传递数据。通过Sqoop，可以方便的将数据从关系型数据库导入到HDFS或者将数据从HDFS导出到关系型数据库。

.. figure:: ../images/15.jpg
