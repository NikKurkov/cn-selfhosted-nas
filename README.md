# 中文自托管与 NAS 工具清单

![preview](assets/preview.png)

自托管的乐趣是东西都在自己手里，麻烦也是东西都在自己手里。这个仓库会优先收成熟项目，不鼓励把半成品服务直接暴露公网。

先备份，再折腾。没有备份的 NAS 只是一个看起来很高级的单点故障。

## 先看这几个

awesome-selfhosted / Docker / CasaOS / Immich

Docker Compose、反向代理、备份策略先准备好，再上 Immich、Jellyfin、Nextcloud。

## 入口

| 名称 | 我为什么留它 |
| --- | --- |
| [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | 自托管项目大列表。 |
| [Docker](https://www.docker.com/) | 容器基础设施。 |
| [CasaOS](https://casaos.io/) | 家庭云系统。 |
| [Immich](https://github.com/immich-app/immich) | 自托管相册。 |
| [Jellyfin](https://jellyfin.org/) | 自托管媒体服务器。 |
| [Nextcloud](https://nextcloud.com/) | 个人云盘和协作平台。 |
| [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | 轻量 Bitwarden 兼容服务。 |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | 自托管监控面板。 |

## 我的使用顺序

- 先用 Docker Compose 管理服务。
- 所有外网暴露服务都要有 HTTPS 和强密码。
- 先搭备份，再搭相册和网盘。

## 别踩坑

- 不要把管理面板直接暴露公网。
- 家庭 NAS 最大风险不是部署失败，而是硬盘坏了没备份。

## 截图来源

这张图来自公开页面：[https://github.com/awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)。如果页面改版，截图可能会和当前官网略有出入。

## 维护方式

链接数据放在 [`data/links.json`](data/links.json)。我倾向于少而准：入口失效就换，说明过时就改，不把这里做成什么都往里塞的大杂烩。

## License

MIT. 第三方商标、页面截图和网站内容归原权利方所有；本仓库只做中文导航和使用笔记。
