# AdaMotif

***AdaMotif***: 通过自适应模体设计简化图形

## 安装

使用 conda 配置两个 Python 环境：一个用于 py 文件夹，另一个用于 align 文件夹。具体的包信息在每个对应文件夹的 requirements.txt 文件中。目前，只能通过依赖这些单独的环境来运行来自不同环境的代码。

## 运行

1. 运行 `./run.py` 在 py 文件夹中运行，处理和获取图社区相关数据。 

2. 运行 align 文件夹中的文件以获取对齐数据。

3. 运行 html 文件夹中的前端文件，将子图节点的链接保存在本地，以获取图形模式中的子图样式数据。

4. 运行 Matlab 生成图的轮廓信息。

在执行过程中，模块之间的数据依赖关系会生成并存储在 'data_processed' 文件夹中。由于框架中使用了许多机器学习算法，因此这些算法生成的数据每次都会略有不同。