# router-scripts

Scripts for GL-iNet BE3600 router.  
GL-iNet BE3600 路由器专用脚本。

---

## 📦 介绍（Introduction）

本项目收集了适用于 GL-iNet BE3600 路由器的实用脚本，方便进行系统安装、管理和维护操作。  
A collection of useful scripts for GL-iNet BE3600 router to simplify installation and management.

---

## 🚀 脚本说明（Scripts）

| 文件名            | 功能简介           |
|-------------------|--------------------|
| `gl-be3600.sh`    | 一键刷机或环境搭建  |

---

## ⚡ 一键运行（推荐方式）

1. **SSH连接到路由器，或者在路由器终端执行如下命令：**

    ```sh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/Kevin-C-0331/router-scripts/main/gl-be3600.sh)"

可用 SCP、WinSCP 等方式。

SSH 连接路由器，运行脚本

例如：

<BASH>
chmod +x be3600-install.sh
./be3600-install.sh
详细用法请见每个脚本的注释说明。

⚠️ 注意事项（Notices）
脚本为个人分享，风险自负，建议提前备份重要数据。
遇到权限问题可尝试用 sudo。
💬 反馈（Feedback）
如发现问题或有建议，欢迎提交 Issue 或联系我。

📃 许可证（License）
本项目采用 MIT License。
