<div align="center">

# MultiSource Imagery Downloader for QGIS

**在 QGIS 中检索、预览并下载多源遥感影像**

[🇺🇸 English](./README.md) · [**🇨🇳 中文**](./README_CN.md)

<img src="https://img.shields.io/badge/QGIS-3.x-589632?style=flat-square&logo=qgis&logoColor=white" />
<img src="https://img.shields.io/badge/Version-1.0.0-1565C0?style=flat-square" />
<img src="https://img.shields.io/badge/Python-PyQGIS-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Imagery-Multi--Source-00838F?style=flat-square" />

</div>

---

## 项目简介

**MultiSource Imagery Downloader** 是一款面向 QGIS 的多源遥感影像检索、预览、加载与下载插件。插件将在线影像、STAC 卫星影像检索、历史影像资源和灾害应急影像目录整合到一个紧凑的 QGIS 侧边栏中，整体界面延续 QGIS 原生风格。

插件主要面向实际 GIS 与遥感应用场景，可直接在地图上定义研究范围、切换不同影像源、查看检索结果范围、突出显示当前选中影像，并对下载任务进行规模预估和过程控制。

## 主要功能

- 集成 ESRI World Imagery、天地图矢量/影像以及星图地球等在线影像和地图服务。
- 支持当前地图范围、地图框选范围和活动图层范围作为下载区域。
- 支持瓦片下载及实时进度显示。
- 提供开始、暂停、继续和取消任务功能。
- 下载过程中可在 QGIS 地图画布实时显示当前正在处理的瓦片范围。
- 下载完成后支持 GeoTIFF 拼接与范围裁剪。
- 基于 STAC 检索 Sentinel、Landsat 等卫星影像，可接入 Earth Search、Copernicus Data Space、Microsoft Planetary Computer 等平台。
- 检索结果 Footprint 可直接显示在地图上。
- 当前选中的影像或数据源采用明显的范围高亮显示。
- 集成 USGS、NASA Worldview、ESRI Wayback、Copernicus EMS、FIRMS、HDDS、UNOSAT、International Charter、NOAA、吉林一号、中国资源卫星应用中心等历史与灾害影像资源入口。
- 天地图 Key、星图 Token、Planet API Key、FIRMS MAP_KEY 等认证信息保存在本机配置中，不在源代码中写入实际密钥。
- 折叠栏采用 QGIS 风格绿色强调色，布局紧凑，可动态收缩。
- 支持中英文界面。

## 下载控制

插件不设置强制瓦片数量上限。当单次任务超过 **20,000 个瓦片**时，会提示预计任务规模和可能的下载风险；用户确认后仍可继续执行。

下载过程中，当前瓦片范围可实时显示在地图画布中，使下载进度不仅以百分比展示，也可以直观看到空间位置变化。

## 安装方法

### QGIS 官方插件库

正式发布后，可进入 **QGIS → 插件 → 管理并安装插件** 搜索并安装。

### ZIP 手动安装

1. 下载插件 ZIP 文件。
2. 打开 QGIS。
3. 进入 **插件 → 管理并安装插件 → 从 ZIP 安装**。
4. 选择 ZIP 文件并完成安装。
5. 从 QGIS 插件界面打开 **MultiSource Imagery Downloader**。

## 使用说明

部分影像服务需要账号、API Key、Token、订阅或额外的历史影像访问权限。插件仅在数据提供方授权范围内访问数据，不绕过登录、许可、订购或权限控制。

## 相关链接

- GitHub 仓库：https://github.com/zhangyhrs/MultiSource-Imagery-Downloader-QGIS
- 问题反馈：https://github.com/zhangyhrs/MultiSource-Imagery-Downloader-QGIS/issues
- GitHub 主页：https://github.com/zhangyhrs

---

## 关注交流

<table align="center">
  <tr>
    <th width="33%">微信公众号<br>测绘地信</th>
    <th width="33%">微信小程序<br>测绘地信</th>
    <th width="33%">知识星球<br>测绘地理信息共享中心</th>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/zhangyhrs/GeoStar-Selector-QGIS/main/assets/wechat-official-account.png" height="150"></td>
    <td align="center"><img src="https://raw.githubusercontent.com/zhangyhrs/GeoStar-Selector-QGIS/main/assets/wechat-mini-program.jpg" height="150"></td>
    <td align="center"><img src="https://raw.githubusercontent.com/zhangyhrs/GeoStar-Selector-QGIS/main/assets/knowledge-planet.jpg" height="150"></td>
  </tr>
</table>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@zhangyhrs-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zhangyhrs)

</div>
