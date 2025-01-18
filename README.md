# 华为云Serverless数据集

## 数据集说明

原始数据集来自华为云的公有云和私有云平台，处理后的数据集仅包含私有云数据，主要的指标有请求数量（每秒/每分钟）、CPU和内存使用情况，后续可用于做负载预测或故障检测相关任务。详细的数据集描述可以参考：
[@sir-lab/data-release](https://github.com/sir-lab/data-release/blob/main/README_data_release_2023.md)

## 数据集特点

### 私有云数据集
- 包含200个函数的141天数据（在235天内收集）
- 涵盖所有可用区的函数调用数据
- 包含多个关键指标：
  - 请求数量（每秒/每分钟）
  - 函数执行延迟
  - 平台延迟
  - CPU和内存使用情况
  - 实例数量

### 公有云数据集
- 包含5093个函数的26天数据
- 来自单个可用区
- 主要指标：每分钟请求数

### 处理后的数据集
| 属性 | 值 |
|------|-----|
| 数据集大小 | 152.92MB |
| 时间序列数量 | 200 |
| 序列长度 | 67680 |
| 采样频率 | 5分钟 |

## 相关研究

- ACM SoCC 2023: "How Does It Function? Characterizing Long-term Trends in Production Serverless Workloads"

## 数据来源

更多详细信息和原始数据下载，请访问：[sir-lab/data-release](https://github.com/sir-lab/data-release/blob/main/README_data_release_2023.md)
<!--
**dmwyd/dmwyd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
