# MaxVideoChat-Max Caulfield面部追踪系统 v0.1.0版
## 介绍
想要与max在电脑面前一起愉快的聊天吗？想要有一个陪伴在你身边的游戏角色吗？基于Blender和Google的开源插件Mediapipe制作的MaxVideoChat可以帮助你快速实现此功能。
![7}ZJ0XY{ZY}2VWUAI8%YL_H_tmb](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/dfa96bed-7085-4a5c-b60d-e74ba4316db7)

## 配置要求
### 最低配置要求
处理器：Intel(R) Core(TM) i5-10210U或更好的处理器。<Br/>
内存：16GB及以上RAM<Br/>
操作系统：Windows7/10/11<Br/>
显卡：具有NVIDIA GeForce GTX 1050TI，4GB及以上显存的GPU显示适配器<Br/>
摄像头：不低于800*600成像分辨率的设备摄像头<Br/>
### 推荐配置要求
处理器：Intel(R) Core(TM) i7-7700K或更好的处理器。<Br/>
内存：24GB及以上RAM<Br/>
操作系统：Windows10/11<Br/>
显卡：具有NVIDIA GeForce RTX 2060，6GB及以上显存的GPU显示适配器<Br/>
摄像头：不低于1920*1080成像分辨率的设备摄像头<Br/>
### 其它配置要求：<Br/>
Blender 3.6及以上版本，你可以通过https://www.blender.org/ 下载该软件。<Br/>
需要启用BlendArMocap插件，你可以通过https://github.com/cgtinker/BlendArMocap 下载该插件。<Br/>
## 安装与配置MaxVideoChat
### 打开Blender
在你的计算机中启动Blender<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/18a1a4cb-85f2-499e-aad9-bb54457987a6)<Br/>
### 启用插件
导航到编辑-偏好设置下<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/7a089ff1-c9d5-4ac2-ad85-e56b0c938765)<Br/>
切换到“插件”选项卡，然后点击“安装…”<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/abcbbf6d-b7b0-4bb6-88da-1bcb397e78c5)<Br/>
在弹出的菜单中找到BlendArMocap插件，然后单击“安装插件”，此时，你会看到如下界面<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/a5446c3f-e6b8-4e6f-a30f-d2ccb2fc8bc2)<Br/>
勾选此插件，然后展开，如果下方有Install按钮，则点击并安装附加组件<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/4d425391-64b2-47ec-a72c-d2bf2951dead)<Br/>
### 打开工程文件
导航到文件-打开-打开位于下载目录下的MaxVideoChat.blend文件<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/91db117a-838f-4508-88b0-688b1eac4716)<Br/>
### 切换材质预览模式
按下键盘上的“Z”键不放，此时Blender将会弹出饼状菜单，鼠标移动到“渲染”选项下并松开<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/11d54bdd-2b0c-41f3-ae5d-d3c5d1ac85cb)<Br/>
### 等待预览渲染完成
等待预览渲染，直到画面与此界面相接近<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/d1db0133-e4f3-4214-8ccc-7cd58f904196)<Br/>
### 找到插件选项卡
按下键盘上的“n”键，然后展开Mediapipe和传递选项卡<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/4f1ca0b9-b362-4ff1-abb5-bd93f0f7bd1b)<Br/>
### 启用Mediapipe面部追踪
确保目标为“面”，如果不是请选择它，然后单击“Start Detection”按钮<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/661f9f17-2e60-4f31-89ac-00880c6954ef)<Br/>
### 开始追踪
此时将开始追踪其面部<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/60f8fbad-d2fc-4718-a07a-016eabd7aa8d)<Br/>
### 未成功启用追踪？
如果未成功启用追踪，请查阅插件选项是否与以下内容符合，或者重新尝试点击这些选项，直到成功追踪到你的面部<Br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/8b324395-2c34-40a6-9fb9-57ec2447aeb6)<Br/>





