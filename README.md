# License_plate_recognition
* A license plate recognition system based on PaddleOCR.
* 一个基于PaddleOCR套件开发的车牌识别系统

# 快速使用
* 使用下面的代码启动车牌识别系统
* 可根据运行平台设置运行的参数
```shell
git clone https://github.com/jm12138/License_plate_recognition.git
cd License_plate_recognition
python tools/infer/predict_system.py --use_gpu False --use_tensorrt False --enable_mkldnn False
```
