# NoMoreWalls

[![Fetch Status](https://github.com/peasoft/NoMoreWalls/actions/workflows/fetch.yml/badge.svg)](https://github.com/peasoft/NoMoreWalls/actions/workflows/fetch.yml) [![Stars](https://img.shields.io/github/stars/peasoft/NoMoreWalls?style=flat)](https://www.star-history.com/?repos=peasoft%2FNoMoreWalls) [![Forks](https://img.shields.io/github/forks/peasoft/NoMoreWalls?style=flat)](https://github.com/peasoft/NoMoreWalls/forks) [![Repo size](https://img.shields.io/github/repo-size/peasoft/NoMoreWalls)](https://github.com/peasoft/NoMoreWalls/commits) [![jsDelivr stats](https://data.jsdelivr.com/v1/package/gh/peasoft/NoMoreWalls/badge?style=rounded)](https://www.jsdelivr.com/package/gh/peasoft/NoMoreWalls) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=peasoft.NoMoreWalls) [![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu) [![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/peasoft/NoMoreWalls/blob/master/LICENSE.md)

自动抓取合并互联网上的公开节点。

## 免责声明

订阅节点仅作学习交流使用，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。**做出违法行为需要承担法律责任，侥幸逃脱是不可能的**！~~为阻止违法行为，本项目随时可以停止运行~~ 本项目可以采取各种技术手段来尽力阻止违法行为。


## 本地部署

请确保你安装了 Python 且版本大于等于 3.8。

1. 使用 Git 克隆本仓库，由于本仓库的完整 Commit 历史极大，请务必指定 `--depth=1`：
    ```bash
    git clone https://github.com/peasoft/NoMoreWalls.git --depth=1
    ```
    或者 [下载项目文件](https://github.com/peasoft/NoMoreWalls/archive/refs/heads/master.zip) 并解压。
2. 安装依赖库
    ```bash
    pip install -r requirements.txt
    ```
3. 如果你所在地区没有墙或你在使用 Tun 模式或透明代理：创建空白文件 `local_proxy.conf`，填入 `NONE`，然后跳到第 9 步
4. 如果你已有代理，请跳到第 8 步
5. 创建空白文件 `local_proxy.conf`
6. 运行 `fetch.py`
7. 将生成的订阅导入代理工具并正确配置好代理
8. 在 `local_proxy.conf` 中按如下格式填入你的代理工具的 http(s) 地址，如：
    ```plain
    http://127.0.0.1:7890/
    ```
9. 如有需要，可将 `fetch_config.yml` 复制为 `local_fetch_config.yml` 并调整相关设置
10. 运行 `fetch.py`
11. 你已获得完整订阅

如果本地仓库长期未更新，也请使用 `--depth=1` 更新仓库：

```bash
git pull --depth=1
git reset --hard origin/master
```

## Star History

<a href="https://www.star-history.com/?repos=peasoft%2FNoMoreWalls">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=peasoft/NoMoreWalls&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=peasoft/NoMoreWalls&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=peasoft/NoMoreWalls&type=date&legend=top-left" />
 </picture>
</a>
