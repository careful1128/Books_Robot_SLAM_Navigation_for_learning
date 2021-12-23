# 《机器人SLAM导航核心技术与实战》张虎 著 （随书配套源码+PPT课件+课后习题答案）
![avatar](https://github.com/xiihoo/Books_Robot_SLAM_Navigation/blob/main/BOOK1.jpg)
![avatar](https://github.com/xiihoo/Books_Robot_SLAM_Navigation/blob/main/BOOK2.jpg)
## 图书封面
![avatar](http://xiihoo.com/static/image/book_front_800x800.jpg)
## 目录
* <font color=#008000 >序</font>
* <font color=#008000 >前言</font>
* <font color=#008000 >编程基础篇</font>
* 第1章 ROS入门必备知识 2
  + 1.1 ROS简介 2
    - 1.1.1 ROS的性能特色 2
    - 1.1.2 ROS的发行版本 3
    - 1.1.3 ROS的学习方法 3
  + 1.2 ROS开发环境的搭建 3
    - 1.2.1 ROS的安装 4
    - 1.2.2 ROS文件的组织方式 4
    - 1.2.3 ROS网络通信配置 5
    - 1.2.4 集成开发工具 5
  + 1.3 ROS系统架构 5
    - 1.3.1 从计算图视角理解ROS架构 6
    - 1.3.2 从文件系统视角理解ROS架构 7
    - 1.3.3 从开源社区视角理解ROS架构 8
  + 1.4 ROS调试工具 8
    - 1.4.1 命令行工具 9
    - 1.4.2 可视化工具 9
  + 1.5 ROS节点通信 10
    - 1.5.1 话题通信方式 12
    - 1.5.2 服务通信方式 15
    - 1.5.3 动作通信方式 19
  + 1.6 ROS的其他重要概念 25
  + 1.7 ROS 2.0展望 28
  + 1.8 本章小结 28
* 第2章 C++编程范式 29
  + 2.1 C++工程的组织结构 29
    - 2.1.1 C++工程的一般组织结构 29
    - 2.1.2 C++工程在机器人中的组织结构 29
  + 2.2 C++代码的编译方法 30
    - 2.2.1 使用g++编译代码 31
    - 2.2.2 使用make编译代码 32
    - 2.2.3 使用CMake编译代码 32
  + 2.3 C++编程风格指南 33
  + 2.4 本章小结 34
* 第3章 OpenCV图像处理 35
  + 3.1 认识图像数据 35
    - 3.1.1 获取图像数据 35
    - 3.1.2 访问图像数据 36
  + 3.2 图像滤波 37
    - 3.2.1 线性滤波 37
    - 3.2.2 非线性滤波 38
    - 3.2.3 形态学滤波 39
  + 3.3 图像变换 40
    - 3.3.1 射影变换 40
    - 3.3.2 霍夫变换 42
    - 3.3.3 边缘检测 42
    - 3.3.4 直方图均衡 43
  + 3.4 图像特征点提取 44
    - 3.4.1 SIFT特征点 44
    - 3.4.2 SURF特征点 50
    - 3.4.3 ORB特征点 52
  + 3.5 本章小结 54
* <font color=#008000 >硬件基础篇</font>
* 第4章 机器人传感器 56
  + 4.1 惯性测量单元 56
    - 4.1.1 工作原理 56
    - 4.1.2 原始数据采集 60
    - 4.1.3 参数标定 65
    - 4.1.4 数据滤波 73
    - 4.1.5 姿态融合 75
  + 4.2 激光雷达 91
    - 4.2.1 工作原理 92
    - 4.2.2 性能参数 94
    - 4.2.3 数据处理 96
  + 4.3 相机 100
    - 4.3.1 单目相机 101
    - 4.3.2 双目相机 107
    - 4.3.3 RGB-D相机 109
  + 4.4 带编码器的减速电机 111
    - 4.4.1 电机 111
    - 4.4.2 电机驱动电路 112
    - 4.4.3 电机控制主板 113
    - 4.4.4 轮式里程计 117
  + 4.5 本章小结 118
* 第5章 机器人主机 119
  + 5.1 X86与ARM主机对比 119
  + 5.2 ARM主机树莓派3B+ 120
    - 5.2.1 安装Ubuntu MATE 18.04 120
    - 5.2.2 安装ROS melodic 122
    - 5.2.3 装机软件与系统设置 122
  + 5.3 ARM主机RK3399 127
  + 5.4 ARM主机Jetson-tx2 128
  + 5.5 分布式架构主机 129
    - 5.5.1 ROS网络通信 130
    - 5.5.2 机器人程序的远程开发 130
  + 5.6 本章小结 131
* 第6章 机器人底盘 132
  + 6.1 底盘运动学模型 132
    - 6.1.1 两轮差速模型 132
    - 6.1.2 四轮差速模型 136
    - 6.1.3 阿克曼模型 140
    - 6.1.4 全向模型 144
    - 6.1.5 其他模型 148
  + 6.2 底盘性能指标 148
    - 6.2.1 载重能力 148
    - 6.2.2 动力性能 148
    - 6.2.3 控制精度 150
    - 6.2.4 里程计精度 150
  + 6.3 典型机器人底盘搭建 151
    - 6.3.1 底盘运动学模型选择 152
    - 6.3.2 传感器选择 152
    - 6.3.3 主机选择 153
  + 6.4 本章小结 155
* <font color=#008000 >SLAM篇</font>
* 第7章 SLAM中的数学基础 158
  + 7.1 SLAM发展简史 158
    - 7.1.1 数据关联、收敛和一致性 160
    - 7.1.2 SLAM的基本理论 161
  + 7.2 SLAM中的概率理论 163
    - 7.2.1 状态估计问题 164
    - 7.2.2 概率运动模型 166
    - 7.2.3 概率观测模型 171
    - 7.2.4 概率图模型 173
  + 7.3 估计理论 182
    - 7.3.1 估计量的性质 182
    - 7.3.2 估计量的构建 183
    - 7.3.3 各估计量对比 190
  + 7.4 基于贝叶斯网络的状态估计 193
    - 7.4.1 贝叶斯估计 194
    - 7.4.2 参数化实现 196
    - 7.4.3 非参数化实现 202
  + 7.5 基于因子图的状态估计 206
    - 7.5.1 非线性最小二乘估计 206
    - 7.5.2 直接求解方法 206
    - 7.5.3 优化方法 208
    - 7.5.4 各优化方法对比 218
    - 7.5.5 常用优化工具 219
  + 7.6 典型SLAM算法 221
  + 7.7 本章小结 221
* 第8章 激光SLAM系统 223
  + 8.1 Gmapping算法 223
    - 8.1.1 原理分析 223
    - 8.1.2 源码解读 228
    - 8.1.3 安装与运行 233
  + 8.2 Cartographer算法 240
    - 8.2.1 原理分析 240
    - 8.2.2 源码解读 247
    - 8.2.3 安装与运行 258
  + 8.3 LOAM算法 266
    - 8.3.1 原理分析 266
    - 8.3.2 源码解读 267
    - 8.3.3 安装与运行 270
  + 8.4 本章小结 270
* 第9章 视觉SLAM系统 272
  + 9.1 ORB-SLAM2算法 274
    - 9.1.1 原理分析 274
    - 9.1.2 源码解读 310
    - 9.1.3 安装与运行 319
    - 9.1.4 拓展 327
  + 9.2 LSD-SLAM算法 329
    - 9.2.1 原理分析 329
    - 9.2.2 源码解读 334
    - 9.2.3 安装与运行 337
  + 9.3 SVO算法 338
    - 9.3.1 原理分析 338
    - 9.3.2 源码解读 341
  + 9.4 本章小结 341
* 第10章 其他SLAM系统 344
  + 10.1 RTABMAP算法 344
    - 10.1.1 原理分析 344
    - 10.1.2 源码解读 351
    - 10.1.3 安装与运行 357
  + 10.2 VINS算法 362
    - 10.2.1 原理分析 364
    - 10.2.2 源码解读 373
    - 10.2.3 安装与运行 376
  + 10.3 机器学习与SLAM 379
    - 10.3.1 机器学习 379
    - 10.3.2 CNN-SLAM算法 411
    - 10.3.3 DeepVO算法 413
  + 10.4 本章小结 414
* <font color=#008000 >自主导航篇</font>
* 第11章 自主导航中的数学基础 418
  + 11.1 自主导航 418
  + 11.2 环境感知 420
    - 11.2.1 实时定位 420
    - 11.2.2 环境建模 421
    - 11.2.3 语义理解 422
  + 11.3 路径规划 422
    - 11.3.1 常见的路径规划算法 423
    - 11.3.2 带约束的路径规划算法 430
    - 11.3.3 覆盖的路径规划算法 434
  + 11.4 运动控制 435
    - 11.4.1 基于PID的运动控制 437
    - 11.4.2 基于MPC的运动控制 438
    - 11.4.3 基于强化学习的运动控制 441
  + 11.5 强化学习与自主导航 442
    - 11.5.1 强化学习 443
    - 11.5.2 基于强化学习的自主导航 465
  + 11.6 本章小结 467
* 第12章 典型自主导航系统 470
  + 12.1 ros-navigation导航系统 470
    - 12.1.1 原理分析 470
    - 12.1.2 源码解读 475
    - 12.1.3 安装与运行 479
    - 12.1.4 路径规划改进 492
    - 12.1.5 环境探索 496
  + 12.2 riskrrt导航系统 498
  + 12.3 autoware导航系统 499
  + 12.4 导航系统面临的一些挑战 500
  + 12.5 本章小结 500
* 第13章 机器人SLAM导航综合实战 502
  + 13.1 运行机器人上的传感器 502
    - 13.1.1 运行底盘的ROS驱动 503
    - 13.1.2 运行激光雷达的ROS驱动 503
    - 13.1.3 运行IMU的ROS驱动 504
    - 13.1.4 运行相机的ROS驱动 504
    - 13.1.5 运行底盘的urdf模型 505
    - 13.1.6 传感器一键启动 506
  + 13.2 运行SLAM建图功能 506
    - 13.2.1 运行激光SLAM建图功能 507
    - 13.2.2 运行视觉SLAM建图功能 508
    - 13.2.3 运行激光与视觉联合建图功能 508
  + 13.3 运行自主导航 509
  + 13.4 基于自主导航的应用 510
  + 13.5 本章小结 511
* 附录A Linux与SLAM性能优化的探讨 512
* 附录B 习题 523

## 关于
* 作者: （英文名）xiihoo（中文名）张虎（网名）  小虎哥哥爱学习
* 官网:  http://www.xiihoo.com
* QQ群： 728661815
* 邮箱:  robot4xiihoo@163.com
* 源码:  https://github.com/xiihoo/Books_Robot_SLAM_Navigation
## 环境要求
* ubuntu 18.04 LTS
* ROS melodic
## 源码包介绍
* chapter_1: **ROS入门必备知识**
  + topic_example 话题通信
  + service_example 服务通信
  + action_example 动作通信
* chapter_2: **C++编程范式**
  + g++_compile 利用g++编译
  + make_compile 利用make编译
  + cmake_compile 利用cmake编译
* chapter_3: **OpenCV图像处理**
  + image_from_img 从图片文件中获取图像数据
  + image_from_vid 从视频文件中获取图像数据
  + image_from_cam 从相机设备中获取图像数据
  + calc_hist 直方图均衡
  + xfeatures2d_example 图像特征点提取
* chapter_4: **机器人传感器**
  + imu_tk IMU内参标定
  + imu_utils IMU内参标定
  + imu_tools Madgwick姿态融合 
  + ManhonyAHRS Manhony姿态融合
* chapter_5: **机器人主机**
* chapter_6: **机器人底盘**
* chapter_7: **SLAM中的数学基础**
* chapter_8: **激光SLAM系统**
  + gmapping gmapping激光SLAM系统
  + cartographer cartographer激光SLAM系统
  + loam LOAM激光SLAM系统
* chapter_9: **视觉SLAM系统**
  + orb_slam2 ORB_SLAM2视觉SLAM系统
  + lsd_slam LSD_SLAM视觉SLAM系统
  + svo SVO视觉SLAM系统
* chapter_10: **其他SLAM系统**
  + rtabmap rtabmap激光视觉融合SLAM系统
  + vins VINS视觉惯导融合SLAM系统
  + LeNet-5-tensorflow LeNet-5卷积神经网络
  + CNN_SLAM 基于CNN的SLAM系统
  + DeepVO 基于深度学习的端到端SLAM系统
* chapter_11: **自主导航中的数学基础**
* chapter_12: **典型自主导航系统**
  + ros-navigation 
  + riskrrt
  + autoware
* chapter_13: **机器人SLAM导航综合实战**
  + patrol_fsm 多目标点巡逻

## PPT课件
* 正在更新...

## 课后习题答案
* 正在更新...

## 视频教程
* 正在更新...
