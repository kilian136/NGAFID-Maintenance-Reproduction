# NGAFID 航空维护事件预测：MiniRocket 基准复现

本项目复现了论文 [A Large-Scale Annotated Multivariate Time Series Aviation Maintenance Dataset from the NGAFID] 中 Section 3.2 的基准实验，使用 MiniRocket 特征提取器和逻辑回归，在 19 类维护事件的 2 天基准子集上进行维护前/后航班二分类，并报告了五折交叉验证结果。

## 快速开始

### 1. 环境配置
```bash
# 克隆仓库
git clone https://github.com/[你的用户名]/NGAFID-Maintenance-Project.git
cd NGAFID-Maintenance-Project

# 创建虚拟环境（推荐）
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 或 venv\Scripts\activate  # Windows

# 安装依赖
pip install -r requirements.txt
