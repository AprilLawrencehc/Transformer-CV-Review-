# 深度学习课程设计：Transformer 架构在计算机视觉中的应用与发展

## 📖 项目介绍

在课程报告中，我深入探讨了视觉 Transformer（ViT）从“纯注意力机制”向“高效层级化结构”演进的过程。为了验证报告中的核心观点，特别是关于**模型演进**与**IoT边缘端轻量化部署**的论述，本项目构建了两组对比实验：

1.  **架构演进验证**：对比标准 ViT 与 Swin Transformer 的推理效率，验证层级化窗口机制的有效性。
2.  **应用场景验证**：演示 SegFormer 在语义分割任务中的表现，论证其在物联网（IoT）资源受限场景下的适用性。

## 📂 文件结构

```text
Transformer-CV-Review/
├── README.md                   # 项目说明文档
├── requirements.txt            # 项目依赖环境
├── 1_classification_compare.py # 实验代码一：ViT vs Swin 分类与速度对比
├── 2_segmentation_demo.py      # 实验代码二：SegFormer 语义分割推理
