# Py_dl_course2022_HW3

该项目为2022春“Python与深度学习基础”课程大作业项目三

项目的主要内容是复现发表在CVPR_2021上的文章**《PAConv: Position Adaptive Convolution with Dynamic Kernel Assembling on Point Cloud》**。项目源地址见[PAConv](https://github.com/CVMI-Lab/PAConv)，论文地址 [[arXiv](https://arxiv.org/abs/2103.14635)]

本次项目库框架：

- `code`：运行代码，并根据本次实验的具体运行环境做了微调
- `data`：训练过程中的数据，均以csv格式保存
- `fig`：训练过程中TensorBoard曲线图
- `log`：训练过程中的输出日志

复现结果与论文结果对比：

| Approach/Acc | PAConv (*PN) w/o vot. | PAConv (*DGC) w/o vot. | PAConv (*DGC) w/ vot.    |
| ------------ | --------------------- | ---------------------- | ------------------------ |
| Paper        | 93.2%                 | 93.6%                  | **93.9%**(SOTA in paper) |
| This repo    | 92.8%                 | 92.6%                  | 93.0%                    |

