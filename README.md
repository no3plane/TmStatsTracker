# TmStatsTracker
## 简介
测试时用眼睛读任务管理器太艰难，于是写了一个脚本自动抓取任务管理器UI上的进程数据。数据的获取使用`Python-UIAutomation-for-Windows
`库。
## 适用对象
- Windows 11 任务管理器
## 安装依赖
- 安装`Python-UIAutomation-for-Windows`：使用`pip install uiautomation`进行安装
- （可选）安装`matplotlib`：如果要以折线图形式展示数据，需要安装这个。使用`pip install matplotlib`或`conda install matplotlib`进行安装
## 使用
- 先打开任务管理器，切换到“进程”页面，单击选中要监视的进程
- 然后以管理员身份使用python运行`Main.py`文件
