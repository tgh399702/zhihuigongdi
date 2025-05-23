markdown
# 智慧工地管理系统
 
本仓库是一个基于物联网与AI技术的智慧工地解决方案，旨在通过数字化手段提升建筑施工现场的安全管理、效率监控与资源调度能力。系统集成环境监测、人员定位、设备管理、进度可视化等功能模块，支持实时数据采集与智能分析预警。
 
核心功能：
1. 📡 环境监测：实时采集PM2.5/噪声/温湿度数据，超标自动告警
2. 👷 人员管理：UWB定位+AI摄像头实现安全帽佩戴检测与轨迹追踪
3. 🚧 设备监控：BIM模型联动塔吊/升降机运行状态可视化
4. 📊 智能分析：基于机器学习的安全隐患预测与进度偏差预警
5. 📱 多端协同：Web管理后台+移动端APP实现远程巡检
 
技术架构：
- 前端：Vue3+ECharts可视化看板
- 后端：SpringCloud微服务+MySQL时序数据库
- 边缘计算：树莓派+NVIDIA Jetson边缘AI盒子
- 通信协议：MQTT+WebSocket实时推送
 
适合建筑企业数字化转型参考，欢迎提交PR完善工地数字化解决方案！
