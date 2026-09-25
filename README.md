# Multi-Source Imagery Downloader for QGIS

A lightweight QGIS plugin for discovering, previewing, loading, and downloading multi-source remote-sensing imagery. The plugin integrates online basemaps, STAC-based satellite search, historical imagery resources, and disaster-response imagery/catalogs in a compact QGIS-style interface.

**Version:** 1.0.0  
**Platform:** QGIS 3.x  
**Language:** Python / PyQGIS / PyQt

## Features

- Online imagery and map services, including ESRI World Imagery, Tianditu vector/imagery layers, and GEOVIS Earth imagery.
- AOI selection from current map extent, interactive rectangle drawing, or active-layer extent.
- Tile download, progress display, pause/resume/cancel controls, and GeoTIFF mosaicking/cropping.
- Download footprint slider on the QGIS map canvas to visualize the current tile being processed.
- STAC search for Sentinel and Landsat imagery through providers such as Earth Search, Copernicus Data Space, and Microsoft Planetary Computer.
- Search-result footprints with selected-scene highlighting.
- Historical and disaster-imagery resource entries, including USGS, NASA Worldview, ESRI Wayback, Copernicus EMS, FIRMS, HDDS, UNOSAT, International Charter, NOAA, Jilin-1, and CRESDA-related resources.
- Local credential settings for Tianditu Key, GEOVIS tokens, Planet API Key, and FIRMS MAP_KEY. Credentials are not hard-coded in the source code.
- QGIS-inspired green accent color and compact dock-panel workflow.

## Download behavior

The plugin does not impose a hard tile-count limit. When a task exceeds **20,000 tiles**, it displays an estimated size/risk warning and asks for confirmation before continuing.

## Installation

1. Download the plugin ZIP package.
2. Open QGIS.
3. Go to **Plugins → Manage and Install Plugins → Install from ZIP**.
4. Select the ZIP package and install it.
5. Open **Multi-Source Imagery Downloader** from the QGIS plugin interface.

## Notes

Some imagery providers require an account, API key, token, subscription, or additional historical-imagery permission. This plugin only uses services within the permissions granted by the corresponding provider and does not bypass authentication, licensing, ordering, or access controls.

---

# 多源遥感影像下载器（QGIS）

一款面向 QGIS 的多源遥感影像检索、预览、加载与下载插件。插件将在线地图、STAC 卫星影像检索、历史影像资源和灾害应急影像入口整合到一个简洁、紧凑、符合 QGIS 风格的侧边栏中。

**版本：** 1.0.0  
**平台：** QGIS 3.x  
**开发：** Python / PyQGIS / PyQt

## 主要功能

- 在线影像与地图：ESRI World Imagery、天地图矢量/影像及注记、星图地球影像等。
- 下载范围：当前视图、地图框选、活动图层范围。
- 在线瓦片下载、进度显示、暂停/继续、取消任务、GeoTIFF 拼接与范围裁剪。
- 下载过程中在 QGIS 地图画布实时显示当前瓦片范围滑窗。
- 基于 STAC 检索 Sentinel、Landsat 等卫星数据，支持 Earth Search、Copernicus Data Space、Microsoft Planetary Computer 等平台。
- 检索结果 Footprint 显示，选中影像后对应范围高亮。
- 历史与灾害数据资源入口，包括 USGS、NASA Worldview、ESRI Wayback、Copernicus EMS、NASA FIRMS、USGS HDDS、UNOSAT、International Charter、NOAA、吉林一号、中国资源卫星应用中心等。
- 天地图 Key、星图 Token、Planet API Key、FIRMS MAP_KEY 等仅保存于本机 QGIS Settings，不在源代码中写入实际密钥。
- 界面采用 QGIS 绿色作为强调色，保持轻量、清爽和原生风格。

## 下载数量提示

插件不设置强制瓦片数量上限。当单次任务超过 **20,000 个瓦片**时，会提示预计规模和风险；用户确认后仍可继续下载。

## 安装方法

1. 下载插件 ZIP。
2. 打开 QGIS。
3. 进入 **插件 → 管理并安装插件 → 从 ZIP 安装**。
4. 选择插件 ZIP 并安装。
5. 在 QGIS 插件界面打开“多源遥感影像下载器”。

## 使用说明

部分数据源需要账号、API Key、Token、订阅或历史影像权限。插件仅在数据提供方授权范围内访问数据，不绕过登录、订购、许可或权限控制。
