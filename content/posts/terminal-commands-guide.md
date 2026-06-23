---
title: '终端命令的基本掌握要求'
date: 2026-06-23T20:30:00+08:00
draft: false
tags:
  - terminal
  - command-line
  - macOS
  - VPS
categories:
  - 技术笔记
description: '按 macOS + Ghostty + VPS + AI 开发场景整理，每个类别列出最常用的命令'
---

下面按我在 **macOS + Ghostty + VPS + AI 开发** 场景来整理，每个类别列出 **最常用命令**，优先列出实际使用频率高的。

---

## 1. 📁 文件管理

| 命令 | 作用 |
| ---- | ---- |
| `ls` | 列出文件 |
| `ls -l` | 详细列表 |
| `ls -la` | 显示隐藏文件 |
| `cp` | 复制文件 |
| `cp -r` | 复制目录 |
| `mv` | 移动/重命名 |
| `rm` | 删除文件 |
| `rm -r` | 删除目录 |
| `rm -rf` | 强制删除 |
| `touch` | 创建文件 |
| `file` | 查看文件类型 |
| `stat` | 查看文件信息 |
| `open` | 用默认程序打开 |
| `pbcopy` | 复制到剪贴板 |
| `pbpaste` | 粘贴剪贴板内容 |

---

## 2. 📂 目录管理

| 命令 | 作用 |
| ---- | ---- |
| `pwd` | 当前目录 |
| `cd` | 切换目录 |
| `cd ..` | 上级目录 |
| `cd ~` | Home 目录 |
| `mkdir` | 创建目录 |
| `mkdir -p` | 递归创建 |
| `rmdir` | 删除空目录 |
| `tree` | 树状显示目录 |
| `find . -type d` | 查目录 |
| `du -sh *` | 查看目录大小 |
| `pushd` | 保存目录 |
| `popd` | 返回目录 |
| `dirs` | 查看目录栈 |
| `basename` | 获取目录名 |
| `dirname` | 获取路径 |

---

## 3. 📄 文件查看

| 命令 | 作用 |
| ---- | ---- |
| `cat` | 查看文件 |
| `less` | 分页查看 |
| `more` | 简单分页 |
| `head` | 前 10 行 |
| `tail` | 后 10 行 |
| `tail -f` | 实时日志 |
| `grep` | 搜索文本 |
| `wc` | 统计行数 |
| `sort` | 排序 |
| `uniq` | 去重 |
| `cut` | 提取列 |
| `paste` | 合并列 |
| `column` | 格式化表格 |
| `strings` | 提取文本 |
| `diff` | 比较文件 |

---

## 4. 🔍 搜索与过滤

| 命令 | 作用 |
| ---- | ---- |
| `find` | 查找文件 |
| `grep` | 文本搜索 |
| `grep -r` | 递归搜索 |
| `locate` | 快速查找 |
| `which` | 查命令路径 |
| `whereis` | 查程序 |
| `awk` | 文本处理 |
| `sed` | 替换文本 |
| `xargs` | 批量处理 |
| `cut` | 切字段 |
| `tr` | 字符替换 |
| `sort` | 排序 |
| `uniq` | 去重 |
| `fzf` | 模糊搜索 |
| `rg` | ripgrep 高速搜索 |

---

## 5. 🔑 权限管理

| 命令 | 作用 |
| ---- | ---- |
| `chmod` | 修改权限 |
| `chmod +x` | 增加执行权限 |
| `chown` | 修改所有者 |
| `chgrp` | 修改组 |
| `id` | 查看用户 ID |
| `whoami` | 当前用户 |
| `groups` | 用户组 |
| `sudo` | 提权 |
| `su` | 切换用户 |
| `passwd` | 修改密码 |
| `umask` | 默认权限 |
| `visudo` | 编辑 sudo |
| `ls -l` | 查看权限 |
| `stat` | 查看权限细节 |
| `getfacl` | ACL 权限 |

---

## 6. 🗜️ 压缩与解压

| 命令 | 作用 |
| ---- | ---- |
| `zip` | 压缩 |
| `unzip` | 解压 |
| `tar` | 打包 |
| `tar -xvf` | 解包 |
| `tar -czvf` | tar.gz 压缩 |
| `tar -xzvf` | tar.gz 解压 |
| `gzip` | gzip 压缩 |
| `gunzip` | gzip 解压 |
| `bzip2` | bz2 压缩 |
| `bunzip2` | bz2 解压 |
| `xz` | xz 压缩 |
| `unxz` | xz 解压 |
| `7z` | 7zip |
| `unar` | 解压 RAR |
| `archive` | macOS 归档 |

---

## 7. 🌐 网络工具

| 命令 | 作用 |
| ---- | ---- |
| `ping` | 测试连通性 |
| `curl` | 请求 URL |
| `wget` | 下载文件 |
| `dig` | DNS 查询 |
| `nslookup` | DNS 解析 |
| `host` | 域名查询 |
| `ssh` | 远程登录 |
| `scp` | 文件传输 |
| `rsync` | 同步文件 |
| `traceroute` | 路由追踪 |
| `ifconfig` | 网络配置 |
| `netstat` | 网络状态 |
| `lsof -i` | 端口占用 |
| `nc` | 网络测试 |
| `speedtest` | 测速 |

---

## 8. ⚙️ 进程管理

| 命令 | 作用 |
| ---- | ---- |
| `ps` | 查看进程 |
| `ps aux` | 所有进程 |
| `top` | 实时监控 |
| `htop` | 增强版 top |
| `kill` | 结束进程 |
| `kill -9` | 强制结束 |
| `pkill` | 按名称结束 |
| `pgrep` | 查进程 |
| `jobs` | 后台任务 |
| `bg` | 后台运行 |
| `fg` | 前台运行 |
| `nohup` | 挂后台 |
| `screen` | 会话保持 |
| `tmux` | 终端复用 |
| `uptime` | 系统运行时间 |

---

## 9. 🧑‍💻 Git 开发

| 命令 | 作用 |
| ---- | ---- |
| `git init` | 初始化 |
| `git clone` | 克隆仓库 |
| `git status` | 查看状态 |
| `git add` | 添加文件 |
| `git commit` | 提交 |
| `git push` | 上传 |
| `git pull` | 拉取 |
| `git fetch` | 获取更新 |
| `git branch` | 分支 |
| `git checkout` | 切换 |
| `git switch` | 新切换命令 |
| `git merge` | 合并 |
| `git rebase` | 变基 |
| `git log` | 日志 |
| `git diff` | 比较 |

---

## 10. 🍺 Homebrew 与软件管理

| 命令 | 作用 |
| ---- | ---- |
| `brew install` | 安装 |
| `brew uninstall` | 卸载 |
| `brew search` | 搜索 |
| `brew update` | 更新源 |
| `brew upgrade` | 升级软件 |
| `brew list` | 已安装 |
| `brew info` | 查看详情 |
| `brew doctor` | 诊断 |
| `brew cleanup` | 清理 |
| `brew services list` | 服务列表 |
| `brew services start` | 启动服务 |
| `brew services stop` | 停止服务 |
| `brew autoremove` | 自动清理 |
| `brew deps` | 查看依赖 |
| `brew leaves` | 顶层软件 |

---

## 11. 🖥️ VPS 运维

| 命令 | 作用 |
| ---- | ---- |
| `ssh` | 登录服务器 |
| `scp` | 上传下载 |
| `rsync` | 同步 |
| `systemctl status` | 服务状态 |
| `systemctl restart` | 重启服务 |
| `journalctl -u` | 查看日志 |
| `df -h` | 磁盘空间 |
| `du -sh` | 目录大小 |
| `free -h` | 内存 |
| `top` | CPU 监控 |
| `uname -a` | 系统信息 |
| `hostnamectl` | 主机信息 |
| `crontab -e` | 定时任务 |
| `curl ifconfig.me` | 查看公网 IP |
| `reboot` | 重启服务器 |

---

## 12. 🤖 AI 工具

| 命令 | 作用 |
| ---- | ---- |
| `codex` | OpenAI Codex |
| `claude` | Claude Code |
| `gemini` | Gemini CLI |
| `ollama list` | 本地模型 |
| `ollama run` | 运行模型 |
| `ollama pull` | 下载模型 |
| `ollama rm` | 删除模型 |
| `ollama ps` | 运行状态 |
| `uv` | Python 环境 |
| `pip` | Python 包 |
| `python3` | Python |
| `node` | Node.js |
| `npm` | 包管理 |
| `npx` | 临时运行 |
| `code .` | 打开 VS Code |

---

## 总结

如果按你的使用场景（MacBook Pro M5 + Ghostty + VPS + Codex + Claude Code + Hugo 网站），真正应该优先掌握的命令主要集中在：

**文件管理 + 网络工具 + SSH + Git + Homebrew + VPS 运维 + AI 工具**

这几类已经覆盖你目前 90% 以上的实际使用场景。