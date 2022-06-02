# my_lraspp_test
## 预训练权重下载地址：

* 注意：官方提供的预训练权重是在COCO上预训练得到的，训练时只针对和PASCAL VOC相同的类别进行了训练，所以类别数是21(包括背景)
* lraspp_mobilenet_v3_large: https://download.pytorch.org/models/lraspp_mobilenet_v3_large-d234d4ea.pth
* 注意，下载的预训练权重记得要重命名，比如在train.py中读取的是```lraspp_mobilenet_v3_large.pth```文件，
  不是```lraspp_mobilenet_v3_large-d234d4ea.pth```
