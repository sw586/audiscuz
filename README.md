# Discuz! X3.4 自动登录与积分获取脚本

这是一个用于自动登录Discuz! X3.4论坛（特别是hostloc.com）并自动获取积分的Python脚本。

## 功能

- 自动登录指定的Discuz! X3.4论坛账户。
- 随机访问用户空间以获取积分。
- 自动回复指定帖子。

## 环境要求

- Python 3.x
- requests库

## 安装依赖

    ```bash
    pip install requests
    ```

## 使用方法

1. 克隆或下载此仓库到本地。
2. 打开`main.py`，找到以下代码行：

    ```python
    username = os.environ.get("sw586", "your_default_username")
    password = os.environ.get("sW201988", "your_default_password")
    ```

    替换`your_default_username`和`your_default_password`为您的Discuz! X3.4论坛的用户名和密码。

3. 在命令行中运行：

    ```bash
    python main.py
    ```


