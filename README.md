# Weather-checker
基于 PyQt5 的桌面天气查询应用：用户通过日期选择控件（QDateEdit 日历弹窗）选定日期，应用异步查询并以卡片形式展示该日期的天气状况（图标/emoji、最高最低温度、湿度、风向风力、文字描述）。
## 设置数据源
```
python -m weather_app.main                          # Mock 数据源（默认，无需网络）
python -m weather_app.main --real                   # Open-Meteo 真实数据源（失败自动回退 Mock）
python -m weather_app.main --real --lat 31.23 --lon 121.47  #样例
```
## 启动
运行main.py即可
