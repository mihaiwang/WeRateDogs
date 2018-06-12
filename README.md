### 概述
在本数据整理项目中，使用python，通过twitter api采集推特用户 [@dog_rates](https://twitter.com/dog_rates)的数据档案，然后评估其质量和整洁度，最后进行清洗。

### 文件列表
#### 代码主文件
- `wrangle_act.ipynb`：用于收集、评估、清洗、分析和可视化数据的代码
#### 数据
- `twitter_archive_enhanced.csv`：给定的文件
- `image_predictions.tsv`：以编程方式下载的文件
- `tweet_json.txt`：通过 API 构建的文件
- `dfa.csv`：处理过程中间文件
- `twitter_archive_master.csv`：合并与清洗后的数据
#### 报告
- `wrangle_report.pdf`：汇总数据整理步骤的文档：收集，评估和清洗
- `act_report2.pdf`：对最终数据进行观察与分析的文档

### 使用的Python库
- tweepy
- json
- pandas
- numpy 
- requests
- re
- sys