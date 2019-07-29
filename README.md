欢迎使用本系统！

本系统由两部分组成，HumanFace.exe为人脸变形程序，face_detect.exe为检测人脸关键点程序，运行环境为Windows 10(64位)，可使用Qt5人脸变形程序进行编译，对依赖库为Opencv、Dlib、Numpy。
由于face_detect.exe文件较大，GitHub代码中没有上传，请通过该链接下载到程序所在目录：
https://cloud.tsinghua.edu.cn/f/cee1a4a12c88418caa04/
　　

## 建议测试流程
- 将一张新的人脸照片导入到程序所在目录下，运行face_detect.exe，按提示导出相应的人脸识别点，导出的txt文件命名需与图片名称一致！程序启动可能需要一些时间，请耐心等待。
- 运行HumanFace.exe，选择两张人脸照片，在右侧功能栏勾选所需功能，若没有勾选则执行默认选项（不显示关键点、TPS变形、最近邻插值），点击生成新人脸按钮完成操作。生成图片后，可点击保存图片按钮保存。图片名称为”a.img_to_b.img”，保存到程序所在目录下。


## 注意
- 要选择B样条变形方式时首先要选择B样条，否则会按照默认参数进行TPS变形。
- 要保证名称一致的图片文件和txt文件都在程序所在目录。
- 查看大图功能开发不完善，目前还不能拖动图片，可以通过拉伸弹出窗口大小调整图片区域。也可以打开保存的图片来查看大图。




