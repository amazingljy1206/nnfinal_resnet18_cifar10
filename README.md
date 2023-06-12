# 深度学习期末作业Task1 ResNet18-CIFAR10

### 预训练权重准备

预训练权重下载地址：https://download.pytorch.org/models/resnet18-f37072fd.pth

下载后放在根目录即可

### 预训练模型微调

运行`python train_pretrained.py` ，模型权重和训练信息会保存在文件夹`./models_no_pretrained`。

### ResNet18全参数训练

运行`python train_no_pretrained.py`， 模型权重和训练信息会保存在文件夹`./models_pretrained`。



