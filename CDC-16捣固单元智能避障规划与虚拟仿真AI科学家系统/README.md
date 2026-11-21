# CDC-16 捣固单元智能避障规划与虚拟仿真 AI 科学家系统

本目录是仓库的开发主线，包含 2D 栅格地图、五种路径规划算法、实验评估、多智能体模块、Streamlit 界面和 FastAPI 服务。当前功能仍为二维栅格研究系统，CDC-16 捣固领域能力处于规划阶段。

- `agents/application_service.py`：当前地图实验与决策的统一服务。
- `algorithms/`、`map/`、`evaluation/`：算法、地图与评估实现。
- `gui/`、`api/`、`main.py`：界面、接口和命令行入口。
- `tests/`：自动化测试；`data/` 保存数据管理代码及本地运行数据。

安装依赖、启动和离线快速演示请参阅[仓库 README](../README.md)。本地密钥、数据库和生成的报告不应提交到 Git。
