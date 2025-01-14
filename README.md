# NUAA-AI-Project
## 成员及分工
162100101 郑思哲
162100103 周健文
162100104 周扬超
162100106 赵猛
162150107 纪冠州

郑思哲负责实验代码的实现，得出实验结果，论文的整合；周健文负责总体部分的介绍；周扬超负责相关工作的调查，阐明我们项目的不同之处；赵猛负责方法部分的阐述，创新点的分析；纪冠州负责论文的配图与编辑。

## 预训练模型

预训练模型模型下载地址为[stabilityai/stable-diffusion-2-1 at main (huggingface.co)](https://huggingface.co/stabilityai/stable-diffusion-2-1/tree/main)

## 文件说明
十五种风格图片数据存放在/A目录下，结果图片存放在/output_dreamlora下，每种风格的微调权重在/style内。

## 训练
```
bash train_all.sh
```
## 推理
```
python run_all.py
```
