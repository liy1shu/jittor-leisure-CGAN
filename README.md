# Jittor 挑战热身赛 CGAN
![主要结果](https://github.com/liy1shu/jittor-leisure-CGAN/blob/main/result.png)

采用CGAN的方法训练手写数字的生成对抗网络，上图为生成一串特定数字的结果。

## 简介
本项目包含了第二届计图挑战赛计图热身赛的代码实现。本项目的特点是：采用了Conditional GAN的方法对手写数字的生成进行处理，取得了较为不错的效果。

## 安装 
本项目训练时间约为 2 小时。

#### 运行环境
- python >= 3.7
- jittor >= 1.3.0

#### 预训练模型
预训练模型模型为discriminator_last.pkl，generator_last.pkl。

## 训练 + 推理
可运行以下命令：
```
python CGAN.py
```

会默认训练100个Epoch后进行推理，生成一串指定数字的图片(results.png)。