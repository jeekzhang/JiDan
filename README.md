# 第三届计图 (Jittor) 人工智能算法挑战赛-热身赛
——生成特定数字图像
![主要结果](./result.png)
## 简介
本项目为第三届计图 (Jittor) 人工智能算法挑战赛-热身赛的代码实现，基于jittor深度学习框架，训练了一个CGAN模型，用以生成手写数字图像。

直接运行本仓库，得分为0.9996。

| 排名 | 队伍  | 得分   |
| ---- | ----- | ------ |
| ...  | ...   | ..     |
| 19   | JiDan | 0.9996 |
| ...  | ...   | ...    |



## 安装 
本项目在GPU（A100）上运行，训练时间约为 20 分钟。
#### 运行环境
- jittor >= 1.3.6.10

#### 安装jittor框架
执行以下命令安装 jittor框架
```
pip install jittor=1.3.6.10  
```

## 数据预处理
无
## 训练
执行以下命令
```
python CGAN.py
```
## 推理
无

## 致谢
此项目基于论文 *A Style-Based Generator Architecture for Generative Adversarial Networks* 实现，部分代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。