安装命令∶sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/crypark660/wireguard/main/wireguard_setup.sh)"

快捷方式∶sd

## 致谢与原始项目

本项目中的 `wireguard_setup.sh` 基于以下开源项目：

- 原项目：ailg666/xy
- 原项目地址：https://github.com/ailg666/xy
- 原脚本：https://github.com/ailg666/xy/blob/master/wireguard_setup.sh
- 原始脚本 Raw：https://raw.githubusercontent.com/ailg666/xy/master/wireguard_setup.sh

感谢原作者 **ailg666** 的开源工作。

### 本项目修改说明

在原始 `wireguard_setup.sh` 基础上，本仓库进行了以下修改：

- 增加 `sd` 快捷命令自动安装
- `sd` 自动从本仓库获取最新版脚本
- WireGuard 完整卸载后自动删除 `sd`
- WireGuard 客户端卸载后自动删除 `sd`
- 增加相关安装及使用说明

本仓库仅用于个人学习、配置和维护，原始脚本版权及相关权利归原作者所有。

