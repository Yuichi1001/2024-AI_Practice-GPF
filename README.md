# 2024-AI_Practice-GPF

## 仓库介绍

- 本仓库为2024年国科大夏季学期人工智能技术实践课程结课论文相关代码仓库

- 本仓库是论文《**Universal Prompt Tuning for Graph Neural Networks**》中基于PPI数据集的50-shot实验的相关代码

- 本仓库的代码修改自论文作者提供的代码，解决了原代码运行报错的bug

- 项目运行环境如下：

  ```
  python 3.7
  cuda 10.1
  pytorch 1.4.0
  torch-cluster 1.5.2
  torch-geometric 1.0.3
  torch-scatter 2.0.3
  torch-sparse 0.5.1
  torch-spline-conv 1.2.0
  rdkit 2022.3.4
  tqdm 4.31.1
  tensorboardX 1.6
  ```

- PPI数据集下载地址为： https://snap.stanford.edu/gnn-pretrain/data/bio_dataset.zip ，使用时下载数据集并将`\supervised`和`\unsupervised`文件夹解压到`dataset`文件夹中即可

## 使用方法

- 完成准备后运行`run_few_shot.sh`即可
