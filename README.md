# 时间序列预测系统

## 项目简介

这是一个基于PyQt5和TensorFlow开发的时间序列预测系统，使用LSTM和不同优化算法进行预测分析。该系统提供图形化界面，方便用户上传数据、训练模型和可视化结果。

## 功能特点

- 支持多种数据格式导入
- 内置多种优化算法：PSO、WOA、SCA、SOA、SHO、BOA、ABC、GOA、SMA等
- 预测结果可视化
- 模型性能评估与对比
- 友好的用户界面

## 下载和使用

### 方法一：直接下载可执行文件

由于可执行文件较大，我们提供了外部下载链接：

通过网盘分享的文件：TimeSeriesPredictor.zip

-链接: https://pan.baidu.com/s/1rTNuoiZwiuxEoBVDuXd9ZQ?pwd=j2iu 
-提取码: j2iu

下载后解压缩，双击运行`TimeSeriesPredictor.exe`即可使用。

### 方法二：克隆仓库并自行打包

```bash
# 克隆仓库
git clone https://github.com/zkk-123/time-series-predictor.git

# 进入项目目录
cd time-series-predictor

# 安装依赖
pip install -r requirements.txt

# 运行打包脚本
.\打包程序_修正.bat
```

## 数据文件说明

- `upload_data`: 包含训练数据
- `SavedFigures`: 保存生成的图表
- `output_information`: 输出结果信息

## 系统要求

- 操作系统：Windows 10/11
- 内存：至少4GB（推荐8GB）
- 硬盘空间：至少500MB 
