# MaxVideoChat-Max Caulfield面部追踪系统 v0.1.0版
语言：简体中文（中国），如果你需要英文说明，请参阅此README.md后半段，感谢Discord用户B3nsn0w提供英文版本的说明，并翻译与校对。<Br/>
Language: Simplified Chinese (China). If you need an English explanation, please refer to the second half of this README.md. Thank you to Discord user B3nsn0w for providing the English version of the explanation and translating and proofreading it.<Br/>
## 介绍
想要与max在电脑面前一起愉快的聊天吗？想要有一个陪伴在你身边的游戏角色吗？基于Blender和Google的开源插件Mediapipe制作的MaxVideoChat可以帮助你快速实现此功能。
![7}ZJ0XY{ZY}2VWUAI8%YL_H_tmb](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/dfa96bed-7085-4a5c-b60d-e74ba4316db7)

## 配置要求
### 最低配置要求
处理器：Intel(R) Core(TM) i7-12700H或更好的处理器。<Br/>
内存：16GB及以上RAM<Br/>
操作系统：Windows7/10/11<Br/>
显卡：具有NVIDIA GeForce RTX 3060，6GB及以上显存的GPU显示适配器<Br/>
摄像头：不低于1280*720成像分辨率的设备摄像头<Br/>
### 推荐配置要求
处理器：Intel(R) Core(TM) i9-13900K或更好的处理器。<Br/>
内存：32GB及以上RAM<Br/>
操作系统：Windows10/11<Br/>
显卡：具有NVIDIA GeForce RTX 4090，16GB及以上显存的GPU显示适配器<Br/>
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

# MaxVideoChat-Max Caulfield Facial Tracking System v0.1.0
Language: English. If you need a Chinese explanation, please refer to the first half of this README.md.<Br/>
语言：英语（English），如果你需要中文说明，请参阅此README.md前半段。<Br/>
## Introduction
Do you want to have a fun chat with Max in front of your computer? Do you want to have a game character by your side? MaxVideoChat, based on Blender and Google's open source plugin Mediapipe, can help you achieve this quickly.
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/dfa96bed-7085-4a5c-b60d-e74ba4316db7)
## System Requirements
### Minimum Requirements
Processor: Intel(R) Core(TM) i7-12700H or better processor.<br/>
Memory: 16GB RAM or higher.<br/>
Operating System: Windows 7/10/11.<br/>
Graphics Card: GPU display adapter with NVIDIA GeForce RTX 3060, 6GB VRAM or higher.<br/>
Camera: Device camera with imaging resolution not less than 1280*720.<br/>
### Recommended Requirements
Processor: Intel(R) Core(TM) i9-13900K or better processor.<br/>
Memory: 32GB RAM or higher.<br/>
Operating System: Windows 10/11.<br/>
Graphics Card: GPU display adapter with NVIDIA GeForce RTX 4090, 16GB VRAM or higher.<br/>
Camera: Device camera with imaging resolution not less than 1920*1080.<br/>
### Other Requirements:<br/>
Blender 3.6 or higher version, you can download the software from https://www.blender.org/.<br/>
BlendArMocap plugin needs to be enabled, you can download the plugin from https://github.com/cgtinker/BlendArMocap.<br/>
## Installation and Configuration of MaxVideoChat
### Open Blender
Launch Blender on your computer.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/18a1a4cb-85f2-499e-aad9-bb54457987a6)<br/>
### Enable the Plugin
Navigate to Edit -> Preferences.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/7a089ff1-c9d5-4ac2-ad85-e56b0c938765)<br/>
Switch to the "Add-ons" tab, then click on "Install...".<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/abcbbf6d-b7b0-4bb6-88da-1bcb397e78c5)<br/>
In the popup menu, find the BlendArMocap plugin and click "Install Add-on". You will see the following interface.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/a5446c3f-e6b8-4e6f-a30f-d2ccb2fc8bc2)<br/>
Check the checkbox for this plugin and expand it. If there is an "Install" button below, click it to install the additional components.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/4d425391-64b2-47ec-a72c-d2bf2951dead)<br/>
### Open the Project File
Navigate to File -> Open -> Open the MaxVideoChat.blend file located in the download directory.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/91db117a-838f-4508-88b0-688b1eac4716)<br/>
### Switch to Material Preview Mode
Press and hold the "Z" key on your keyboard. Blender will pop up a pie menu, move the mouse to the "Render" option and release the key.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/11d54bdd-2b0c-41f3-ae5d-d3c5d1ac85cb)<br/>
### Wait for Preview Rendering to Complete
Wait for the preview rendering to complete until the screen is similar to this interface.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/d1db0133-e4f3-4214-8ccc-7cd58f904196)<br/>
### Find the Plugin Tab
Press the "n" key on your keyboard, then expand the Mediapipe and Pass tabs.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/4f1ca0b9-b362-4ff1-abb5-bd93f0f7bd1b)<br/>
### Enable Mediapipe Facial Tracking
Make sure the target is "Face", if not, select it and click the "Start Detection" button.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/661f9f17-2e60-4f31-89ac-00880c6954ef)<br/>
### Start Tracking
Now it will start tracking your face.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/60f8fbad-d2fc-4718-a07a-016eabd7aa8d)<br/>
### Tracking not enabled successfully?
If tracking is not enabled successfully, please check if the plugin options match the following or try clicking on these options again until your face is successfully tracked.<br/>
![image](https://github.com/MaxCauIfield/MaxVideoChat/assets/61368414/8b324395-2c34-40a6-9fb9-57ec2447aeb6)<br/>
