# PPQ Tools(PPQ扩展工具仓库)
This repository is intended for the development of Extended tool collection. It includes PPQ  mutil-models Benchmark on mutil-platform, the examples of model quantification and deployment using PPQ, and some other tested utilities for PPQ.

本仓库是一个[PPQ(PPL QuantTool)](https://github.com/openppl-public/ppq)扩展工具集合，其中包含了PPQ多模型多平台测试Benchmark，使用PPQ进行模型量化和部署的样例，以及一些其他经过测试的实用工具。

## How to use PPQ Tools

The implementation of this repository  tools depend on PPQ. Please install  the PPQ  before use it.

PPQ installation guide：https://github.com/openppl-public/ppq

Please read the guide documents under each tool folder for detailed functions and usage methods of each tool.

本仓库工具实现依赖于PPQ，使用前请提前安装配置好PPQ相关代码环境。  
PPQ安装教程指引：https://github.com/openppl-public/ppq

请参阅各个工具文件夹下的引导文档，了解各工具详细的功能和使用方法。

## An overview of the PPQ Tools

[2022.09.29]   **benchmark**:  A PPQ Benchmark, which is able to quantify、inference and evaluate image classification, object detection and instance segmentation models on multiple platforms with PPQ conveniently.

[2022.09.29]   **benchmark**: 一个PPQ Benchmark，能够使用PPQ对图像分类、目标检测、实例分割等多模型在多平台上一键量化推理与精度测试。


## Update the repository documentation
In order to keep a clean usage containing all contributed tools, the following files need to be created/adapted:

Update this README.md file on overview. Here, you add your tools with a single-line description

Add a README.md inside your own tools folder. This README explains which functionality (separate functions) is available, links to the corresponding samples, and explains in somewhat more detail what the module is expected to do. If any extra requirements are needed to build the module without problems, add them here also.

为了保持包含所有贡献的工具清晰易用，以下文件需要被创建：

更新本README.md文件，贡献者需要用一句话描述自己实现工具的功能。

在您自己的工具文件夹中添加一个 README.md，该README.md文件解释了哪些功能（单独的功能）可用，链接到相应的示例，并更详细地解释了工具的预期功能。

