# Underwater Robot Learning

水下机器人（Underwater Robot / AUV / ROV）学习资料库，系统整理水下机器人的**基础理论、核心硬件、控制算法、通信导航与行业应用**相关笔记、代码实践与资料索引。

## 内容方向

- **基础理论**：流体力学基础、静水力学与浮力配平、水动力建模、运动学与动力学
- **核心硬件**：推进器与推进系统、密封舱与耐压结构、电池与能源管理、舵机/执行器
- **感知与导航**：水下摄像头与声呐、IMU、深度传感器、DVL、SLAM、水声定位（USBL/LBL/SBL）
- **通信技术**：水声通信、水下光通信、线缆/脐带通信、水面组网
- **控制算法**：姿态控制、路径规划、定点悬停、PID / LQR / MPC、故障诊断与容错控制
- **软件开发**：ROS/ROS2 实践、仿真（Gazebo、UUV Simulator）、嵌入式开发（Jetson、RDK 等）
- **行业应用**：科考探测、海洋工程、水产养殖、应急救援、水下巡检
- **企业与产业**：国内外代表性厂商（深之蓝、潜行创新、鳍源科技等）产品与技术路线梳理

## 目录结构

```
underwater-robot-learning/
├── README.md
├── LICENSE
├── notes/            # 学习笔记（理论、硬件、算法）
├── code/             # 代码实践与仿真示例
├── resources/        # 论文、书籍、开源项目索引
└── docs/             # 专题文档与行业研究
```

## 适合人群

- 机器人 / 船舶海洋 / 电子信息相关专业学生
- 从陆地机器人、无人机转向水下机器人的开发者
- 关注海洋装备与水下机器人赛道的研究者与从业者

## 如何使用

1. 按 `notes/` 中的专题顺序学习，或直接按需查阅
2. `code/` 下的示例建议配合 ROS2 仿真环境动手复现
3. 欢迎通过 Issue 补充资料、纠正错误，PR 请先开 Issue 讨论

## 推荐学习路线（PID → MPC）

1. **AtsushiSakai/PythonRobotics**：纯 Python 动画实现 PID、迭代线性 MPC、LQR、Pure Pursuit
2. **ros-controls/control_toolbox + ros2_controllers**：ROS 官方工程化 PID（PidROS）
3. **Walid-khaled/autonomous_mobile_robots**：ROS2 差速机器人 PID/LQR/MPC 对照
4. **rst-tu-dortmund/mpc_local_planner**：MPC 如何嵌入 ROS 导航栈
5. **uuvsimulator/uuv_simulator**：水下级联 PID、非线性 PID、反馈线性化与推力分配矩阵
6. **ethz-asl/mav_control_rw / Nav2 MPPI / OCS2**：进阶与生产级

## 路线图

- [ ] 完成水下机器人基础理论笔记框架
- [ ] 推进器与密封结构硬件拆解笔记
- [ ] ROS2 + UUV Simulator 环境搭建教程
- [ ] 水声通信与定位专题
- [ ] 主流厂商产品与技术路线对比

## 许可证

本项目基于 [MIT License](LICENSE) 开源。
