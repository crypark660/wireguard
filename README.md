# WireGuard 管理脚本

基于 `ailg666/xy` 项目中的 `wireguard_setup.sh` 修改维护。

## 一键安装

在 SSH 终端执行：

```bash
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/crypark660/wireguard/main/wireguard_setup.sh)"
```

> GitHub 会在代码块右上角提供 **Copy** 按钮，可以直接一键复制安装命令。

## 快捷管理

首次运行安装脚本后，会自动创建：

```text
/usr/local/bin/sd
```

以后直接执行：

```bash
sd
```

即可打开 WireGuard 管理菜单。

`sd` 每次运行都会从本仓库获取最新版管理脚本。

## 功能

管理菜单包含：

1. 安装 WireGuard / 创建隧道 - 服务端
2. 安装 WireGuard / 加载配置 - 客户端
3. 生成客户端配置
4. 查看隧道状态
5. 查看客户端配置
6. 删除客户端配置
7. 启动 WireGuard 隧道
8. 停止 WireGuard 隧道
9. 隧道管理
10. 卸载 WireGuard
11. 卸载 WireGuard（客户端）

### 卸载快捷命令

执行菜单 10 或菜单 11，在卸载流程正常完成后，会自动删除：

```text
/usr/local/bin/sd
```

如果取消卸载操作，则不会删除 `sd`。

## 原始项目与致谢

本仓库中的 `wireguard_setup.sh` 基于以下项目中的原始脚本进行修改：

- 原项目：https://github.com/ailg666/xy
- 原始脚本：https://github.com/ailg666/xy/blob/master/wireguard_setup.sh
- 原始脚本 Raw：https://raw.githubusercontent.com/ailg666/xy/master/wireguard_setup.sh
- 原始作者：ailg666

感谢原作者的开源工作。

## 本仓库的修改

在原始 `wireguard_setup.sh` 基础上，本仓库进行了以下修改：

- 增加 `sd` 快捷命令自动安装
- `sd` 自动从本仓库获取最新版脚本
- WireGuard 完整卸载后自动删除 `sd`
- WireGuard 客户端卸载后自动删除 `sd`
- 增加安装及使用说明

## 许可证说明

原项目 `ailg666/xy` 的 GitHub 仓库目前未声明许可证，且仓库中未发现 `LICENSE`、`LICENSE.md`、`LICENSE.txt`、`COPYING` 等许可证文件。

因此，本仓库不对原项目的许可证作任何推断或声明。

原始脚本的版权及相关权利归原作者及相关权利人所有。如对原始脚本的使用、修改或再发布存在疑问，请以原作者的许可和相关法律规定为准。
