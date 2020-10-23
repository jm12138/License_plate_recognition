# License_plate_recognition
* A license plate recognition system based on PaddleOCR.
* 一个基于PaddleOCR套件开发的车牌识别系统

# 项目简介
* 车牌识别即识别车牌上的文字信息，属于光学字符识别(OCR)的一项子任务
* 车牌识别技术目前已广泛应用于例如停车场、收费站等等交通设施中，提供高效便捷的车辆认证的服务
* OCR一般分为如下两个步骤：
  1. 检测图片中的文本位置
  2. 识别其中的文本信息  
* 车牌识别的一般流程如下图：

![流程图](https://ai-studio-static-online.cdn.bcebos.com/35a3dab32ac948549de41afba7b51a5770d3f872d60b437d891f359a5cef8052)

* [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)是最近Paddle开源的一个OCR算法套件，其中包含了各种主流的检测和识别算法，如DB、CRNN等等，不仅效果出色，而且使用上也非常方便
* 本次就使用PaddleOCR来开发一个车牌识别算法

# 快速使用
* 使用下面的代码启动车牌识别系统
* 可根据运行平台设置运行的参数
```shell
git clone https://github.com/jm12138/License_plate_recognition.git
cd License_plate_recognition
python tools/infer/predict_system.py --use_gpu False --use_tensorrt False --enable_mkldnn False
```

# 模型训练
* 训练方法请参考AIStudio教程：[PaddleOCR：车牌识别](https://aistudio.baidu.com/aistudio/projectdetail/739559)
