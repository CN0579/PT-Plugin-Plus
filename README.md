> [!NOTE]
> PT-Plugin-Plus 项目已经进入停止维护期（具体说明见： https://github.com/pt-plugins/PT-Plugin-Plus/issues/2235 ）
> 
> 我们推荐您使用全新的替代方案：  **[PT-depiler](https://github.com/pt-plugins/PT-depiler)** 。
> PT-depiler 是 PT-Plugin-Plus 的继任者，保留了绝大多数核心功能并进行了全面优化，包括更好的兼容性、更稳定的性能和更丰富的功能支持。建议所有用户迁移至新项目以获得持续的更新和支持。


<p align="center">
<img src="https://github.com/pt-plugins/PT-Plugin-Plus/raw/master/public/assets/icon-128.png"><br/>
<a href="https://github.com/pt-plugins/PT-Plugin-Plus/releases?include_prereleases/latest" title="GitHub Pre-releases"><img src="https://img.shields.io/github/release/pt-plugins/PT-Plugin-Plus.svg?include_prereleases&label=pre-release"></a>
<a href="https://github.com/pt-plugins/PT-Plugin-Plus/releases" title="GitHub All Releases"><img alt="Releases" src="https://img.shields.io/github/downloads/pt-plugins/PT-Plugin-Plus/total.svg?label=Downloads"></a>
<img src="https://img.shields.io/badge/Used-TypeScript%20Vue-blue.svg">
<a href="https://github.com/pt-plugins/PT-Plugin-Plus/LICENSE" title="GitHub license"><img src="https://img.shields.io/github/license/pt-plugins/PT-Plugin-Plus.svg?label=License" alt="GitHub license"/></a>
<a href="https://t.me/joinchat/NZ9NCxPKXyby8f35rn_QTw"><img src="https://img.shields.io/badge/Telegram-Chat-blue.svg?logo=telegram" alt="Telegram"/></a>
</p>

---

## 关于

PT 助手 Plus，是一款浏览器插件（Web Extensions），一个可以提升 PT 站点使用效率的工具。

适用于各 PT 站，可使下载种子等各项操作变化更简单、快捷。配合下载服务器（如 Transmission、µTorrent 等），可一键下载指定的种子。

该版本是对原来的 [PT 助手](https://github.com/ronggang/PT-Plugin) 进行了重构，去掉了繁琐的配置，以获得更好的使用体验；

> ~~注意：`1.0.0` 以下的配置不能直接用于该版本，请勿将 `1.0.0` 以下的版本配置进行导入操作。~~

最新版本请登录后从[Pre-release](https://github.com/pt-plugins/PT-Plugin-Plus/releases?include_prereleases/latest)获取。如不会安装请参看Wiki

**提Issue前请务必检查Dev版本、Pull Request以及之前的Issue**

**M-Team 请于站点控制台 -> 实验室 获取 Token 填入后使用**

## 已支持的浏览器
- <a href="https://chrome.google.com/webstore/detail/abkdiiddckphbigmakaojlnmakpllenb" title="已在 Chrome Web Store 市场上发布的版本">![Google Chrome](https://img.shields.io/chrome-web-store/v/abkdiiddckphbigmakaojlnmakpllenb.svg?label=Google%20Chrome)</a> （已下架，见[原因](https://github.com/pt-plugins/PT-Plugin-Plus/wiki#%E5%B7%B2%E8%A2%AB%E4%B8%8B%E6%9E%B6%E7%9A%84%E6%B5%8F%E8%A7%88%E5%99%A8)）
- <a href="https://addons.mozilla.org/zh-CN/firefox/addon/pt-plugin-plus/" title="已在 Mozilla Add-on 上发布的版本">![Mozilla Firefox](https://img.shields.io/amo/v/pt-plugin-plus.svg?label=Mozilla%20Firefox)</a> （已下架，见[原因](https://github.com/pt-plugins/PT-Plugin-Plus/wiki#%E5%B7%B2%E8%A2%AB%E4%B8%8B%E6%9E%B6%E7%9A%84%E6%B5%8F%E8%A7%88%E5%99%A8)）
- <a href="https://microsoftedge.microsoft.com/addons/detail/ekhingnlcjebipkdcgkkheigmljefepn" title="已在 Microsoft Edge 上发布的版本">![Microsoft Edge](https://img.shields.io/badge/dynamic/json?label=Edge%20Addons&prefix=v&query=%24.version&url=https%3A%2F%2Fmicrosoftedge.microsoft.com%2FAddons%2Fgetproductdetailsbycrxid%2Fekhingnlcjebipkdcgkkheigmljefepn)</a>
- 及其他基于 `Chromium` 内核的浏览器

## 功能

- 一键发送指定的种子到下载服务器，目前已支持：
  - Transmission
  - Synology Download Station
  - µTorrent
  - Deluge
  - qBittorrent `v4.1+`
  - ruTorrent
  - Flood
- 比 RSS 更灵活的下载方式：
  - 针对不同的站点发送到不同的下载服务器；
  - 针对不同的站点、下载服务器设置不同的保存路径；
- 批量下载当前页所有种子；
- 批量复制当前页面所有种子的下载链接（`部分站点需要设置 passkey`）；
- 显示默认下载服务器当前可用空间，目前已支持：
  - Transmission
- 多站聚合搜索相同关键字的种子；
  - 查看 [已支持的站点列表](https://github.com/pt-plugins/PT-Plugin-Plus/wiki/supported-sites)
- 根据当前站点显示专属功能，如：
  - 封面模式浏览种子页面；
- 保存下载历史记录（默认关闭）；
- `豆瓣` 电影页面、[Top250](https://movie.douban.com/top250)、[选电影](https://movie.douban.com/explore) 一键搜索 PT 种子支持；
- `IMDb` 电影页面、[Top250](https://www.imdb.com/chart/top?ref_=nv_mv_250) 一键搜索 PT 种子支持；
- 更多功能请参考 [Wiki](https://github.com/pt-plugins/PT-Plugin-Plus/wiki) ；

## 安装及使用

- 如何安装和使用，请参考 [Wiki](https://github.com/pt-plugins/PT-Plugin-Plus/wiki) 的详细说明；
- 常见问题可 [点这里](https://github.com/pt-plugins/PT-Plugin-Plus/wiki/frequently-asked-questions) 找到答案；
