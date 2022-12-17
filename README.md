# Firebase-Python-Visualizer-
This is a test case model for firebase data visualizer for python programming languages. The idea came accross my mind as i was looking at the real time database with GUI. I don't know whether it works or not but lets give it a try since its only a prototype for this. Feel free to commit to the repo :)  <br/>

# 基于Python去实现Firebase数据可视化
这只是个雏形想法，能否实现目前任然是个未知数。各位大佬可以对此代码进行更改。

 # 使用方式 <br/>
- 导入所需的库，包括 PyQt5 用于创建 GUI 和 Pyrebase 用于与 Firebase 交互。<br/>
- 使用你的 Firebase 项目的配置信息填充 config 字典。<br/>
- 使用 config 字典初始化 Pyrebase 客户端。<br/>
- 使用 db 变量获取 Firebase 数据库的引用。<br/>
- 定义 MainWindow 类，它是 PyQt5 的 QMainWindow 的子类。此类负责创建 GUI 并与 Firebase 交互。<br/>
- 定义 __init__ 方法，在创建 MainWindow 实例时调用。此方法设置主窗口及其部件，包括条形图 QGraphicsView、"Refresh" 按钮和包含这些部件的布局。<br/>
- 定义 refresh_data 方法，在单击 "Refresh" 按钮时调用。此方法从 Firebase 获取数据并更新条形图以反映新数据。<br/>
- 执行 if __name__ == "__main__": 块，创建 MainWindow 实例并显示它。然后，应用程序进入事件循环并等待用户输入。<br/>
