# 《机器人SLAM导航核心技术与实战》张虎 著 （随书配套源码+PPT课件+课后习题答案）
## 关于
* 作者: （英文名）xiihoo（中文名）张虎（网名）  小虎哥哥爱学习
* 官网:  http://www.xiihoo.com
* QQ群： 
  + QQ技术1群：728661815（1群已满，请加2群）
  + QQ技术2群：117698356
* 邮箱:  robot4xiihoo@163.com
* 源码:  https://github.com/xiihoo/Books_Robot_SLAM_Navigation
* 购书链接：https://item.jd.com/13041503.html

## 图书封面
![avatar](http://xiihoo.com/static/image/book_front_800x800.jpg)
## 目录
* <font color=#008000 >序</font>
* <font color=#008000 >前言</font>
* <font color=#008000 >编程基础篇</font>
* 第1章 ROS入门必备知识 2
* 第2章 C++编程范式 29
* 第3章 OpenCV图像处理 35
* <font color=#008000 >硬件基础篇</font>
* 第4章 机器人传感器 56
* 第5章 机器人主机 119
* 第6章 机器人底盘 132
* <font color=#008000 >SLAM篇</font>
* 第7章 SLAM中的数学基础 158
* 第8章 激光SLAM系统 223
* 第9章 视觉SLAM系统 272
* 第10章 其他SLAM系统 344
* <font color=#008000 >自主导航篇</font>
* 第11章 自主导航中的数学基础 418
* 第12章 典型自主导航系统 470
* 第13章 机器人SLAM导航综合实战 502
* 附录A Linux与SLAM性能优化的探讨 512
* 附录B 习题 523

## 环境要求
* ubuntu 18.04 LTS
* ROS melodic

## 仓库内容说明
* **1.例程源码**
  + chapter_01: **ROS入门必备知识**
    - topic_example 话题通信
    - service_example 服务通信
    - action_example 动作通信
  + chapter_02: **C++编程范式**
    - g++_compile 利用g++编译
    - make_compile 利用make编译
    - cmake_compile 利用cmake编译
  + chapter_03: **OpenCV图像处理**
    - image_from_img 从图片文件中获取图像数据
    - image_from_vid 从视频文件中获取图像数据
    - image_from_cam 从相机设备中获取图像数据
    - calc_hist 直方图均衡
    - xfeatures2d_example 图像特征点提取
  + chapter_04: **机器人传感器**
    - imu_tk IMU内参标定
    - imu_utils IMU内参标定
    - imu_tools Madgwick姿态融合 
    - ManhonyAHRS Manhony姿态融合
  + chapter_05: **机器人主机**
  + chapter_06: **机器人底盘**
  + chapter_07: **SLAM中的数学基础**
  + chapter_08: **激光SLAM系统**
    - gmapping gmapping激光SLAM系统
    - cartographer cartographer激光SLAM系统
    - loam LOAM激光SLAM系统
  + chapter_09: **视觉SLAM系统**
    - orb_slam2 ORB_SLAM2视觉SLAM系统
    - lsd_slam LSD_SLAM视觉SLAM系统
    - svo SVO视觉SLAM系统
  + chapter_10: **其他SLAM系统**
    - rtabmap rtabmap激光视觉融合SLAM系统
    - vins VINS视觉惯导融合SLAM系统
    - LeNet-5-tensorflow LeNet-5卷积神经网络
    - CNN_SLAM 基于CNN的SLAM系统
    - DeepVO 基于深度学习的端到端SLAM系统
  + chapter_11: **自主导航中的数学基础**
  + chapter_12: **典型自主导航系统**
    - ros-navigation 
    - riskrrt
    - autoware
  + chapter_13: **机器人SLAM导航综合实战**
    - patrol_fsm 多目标点巡逻
  + 更新中......
* **2.课件PPT**
  + 0-先导课：课程大纲.pdf
  + 0-先导课：如何安装Ubuntu系统.pdf
  + 0-先导课：SLAM的应用价值与技术难点.pdf
  + 1-第1季：第0章_SLAM发展综述.pdf
  + 1-第1季：第1章_ROS入门必备知识.pdf
  + 更新中......
* **3.习题答案**
  + 附录B_习题.pdf
  + 更新中......
* **4.学习思维导图**
  + 学习思维导图.png
  + 学习思维导图.xmind

## 知乎专栏教程
* 知乎：https://www.zhihu.com/people/hiram_zhang
* 知乎专栏：
  + 《机器人SLAM导航核心技术与实战》笔记
    https://www.zhihu.com/column/c_1363309952996577280
  + 自己动手做一台SLAM导航机器人
    https://www.zhihu.com/column/c_1084087088789569536

## 视频教程
* B站：https://space.bilibili.com/66815220
* 视频列表：
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=1">【先导课】1.课程大纲-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=2">【先导课】1.1.课程大纲-学习思维导图（上）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=3">【先导课】1.2.课程大纲-学习思维导图（下）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=4">【先导课】1.3.课程大纲-全书内容速览-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=5">【先导课】1.4.下集预告-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=6">【先导课】2.如何安装Ubuntu系统-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=7">【先导课】2.1.如何安装Ubuntu系统-操作系统概念-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=8">【先导课】2.2.如何安装Ubuntu系统-Linux操作系统-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=9">【先导课】2.3.如何安装Ubuntu系统-Ubuntu发行版-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=10">【先导课】2.4.如何安装Ubuntu系统-物理机安装Ubuntu（独立硬盘）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=11">【先导课】2.5.如何安装Ubuntu系统-物理机安装Ubuntu（独立硬盘双系统）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=12">【先导课】2.6.如何安装Ubuntu系统-物理机安装Ubuntu（单硬盘双系统）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=13">【先导课】2.7.如何安装Ubuntu系统-虚拟机安装Ubuntu（VMware方法）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=14">【先导课】2.8.如何安装Ubuntu系统-虚拟机安装Ubuntu（virtualbox方法）-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=15">【先导课】2.9.如何安装Ubuntu系统-Ubuntu系统基础入门-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=16">【先导课】3.SLAM的应用价值与技术难点-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=17">【先导课】3.1.SLAM的应用价值与技术难点-SLAM价值-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=18">【先导课】3.2.SLAM的应用价值与技术难点-产业应用与生态-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=19">【先导课】3.3.SLAM的应用价值与技术难点-核心技术与难点-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=20">【第1季】0.第0章_SLAM发展综述-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=21">【第1季】0.1.第0章_SLAM发展综述-梳理定位导航技术-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=22">【第1季】0.2.第0章_SLAM发展综述-揭秘SLAM技术路线-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=23">【第1季】0.3.第0章_SLAM发展综述-展望SLAM未来趋势-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=24">【第1季】1.第1章_ROS入门必备知识-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=25">【第1季】1.1.第1章_ROS入门必备知识-ROS简介-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=26">【第1季】1.2.第1章_ROS入门必备知识-ROS开发环境搭建-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=27">【第1季】1.3.第1章_ROS入门必备知识-ROS系统架构-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=28">【第1季】1.4.第1章_ROS入门必备知识-ROS调试工具-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=29">【第1季】1.5.第1章_ROS入门必备知识-ROS节点通信-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=30">【第1季】1.6.第1章_ROS入门必备知识-ROS其他重要概念-视频讲解</a>
  + <a href="https://www.bilibili.com/video/BV1jS4y1a7Lz?p=31">【第1季】1.7.第1章_ROS入门必备知识-ROS2.0展望-视频讲解</a>
  + 更多精彩内容，正在更新...
