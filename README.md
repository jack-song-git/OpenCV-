# OpenCV学习笔记
1. 使用平台：Rasspiberry4B
2. 摄像头：原装Model3

# 树莓派初始化
1. 镜像下载安装
  + Raspberry Pi Imager获取网站https://www.raspberrypi.com/software/
  + 使用 Raspberry Pi Imager 安装 Raspberry Pi OS
  + 选择设备，系统Raspberry OS (64-BIT),SDcard
  + 配置用户信息，WIFI，使能SSH
  + 烧录
3. 启用SSH使能VNC
```vim
$sudo raspi-config
```
4. 树莓派中文手册网站https://pidoc.cn/
5. 摄像头的初步操作参考https://pidoc.cn/docs/computers/camera-software
6. OpenCV安装：sudo apt-get install python3-opencv
7. 检查CV版本，在终端依次运行下面代码https://zhuanlan.zhihu.com/p/615187665
```python
python
import cv2
cv2.__version__
```
8. 在Thonny调用CV2
