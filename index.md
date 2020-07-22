## 关于我

- 姓名：王天玺
- 学历：本科毕业于中南大学计算机专业，北京邮电大学计算机专业在读硕士研究生
- 研究方向：移动机器人目标检测与追踪
- 个人博客：[https://me.csdn.net/qq_24894159](https://me.csdn.net/qq_24894159)
- 邮箱：584481076@qq.com

### 主要经历

1. 室内机器人跟随及避障系统
- 硬件：Kobuki移动机器人地盘、单目摄像头
- 软件：Linux、ROS
- 语言：C++、Python
- 主要内容：移动机器人通过位置固定的单目相机连续获取RGB图像，机器人对图像中特定目标进行跟随拍摄，并在跟随移动过程中实时检测地面上障碍物并进行躲避。具体地，目标跟踪模块（Tracking Node）执行执行跟踪算法对目标在连续的图像帧中进行跟踪，同时将跟踪结果发送给运动控制节点（Motion Control Node, MC Node）。障碍物检测节点（Obstacle Detection Node, OD Node)负责检测障碍物并将检测结果发送给MC Node。最后由MC Node综合控制机器人的运动。

2. 室内机器人建图、导航
- 硬件：AutoLabor机器人、2D激光雷达UTM-30LX、单目摄像头
- 软件：Linux、ROS
- 语言：C++、Python
- 主要内容：以Cartographer、move_base为基础搭建室内大场景建图、导航、定点巡航（抓拍人脸）功能，语音询路功能。
![avatar](https://github.com/Miaowaaaa/miaowaaaa.github.io/imgs/BigMap.png)

### 其他作品

#### Android开发

1. 基于LBS校园会议推送App
- 获取用户授权的位置信息，主动搜索、推送周围近期举办的学术会议。采用Material Design界面设计风格，基于BaiduMap，为用户提供直观、便捷信息获取体验。
2. 和风天气
- Android课程设计作业，简洁界面设计，布局设计适配平板和手机端。

#### Web开发
1. 在线排课系统
- 数据库课程设计，挑战10天从零学习Html+js+css+php后台，搭建完整前后端Web应用。整体采用Bootstrap风格页面设计，支持条件排课，在线手动调课、课表生成，课表下载。

2. 影院售票系统
- java web实习练手项目，MVC设计开发模式，分工协作，统一进度推进安排。
