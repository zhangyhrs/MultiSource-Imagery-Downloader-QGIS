<div align="center">

# MultiSource Imagery Downloader for QGIS

**Search, preview and download multi-source imagery directly in QGIS**

[**🇺🇸 English**](./README.md) · [🇨🇳 中文](./README_CN.md)

<img src="https://img.shields.io/badge/QGIS-3.x-589632?style=flat-square&logo=qgis&logoColor=white" />
<img src="https://img.shields.io/badge/Version-1.0.0-1565C0?style=flat-square" />
<img src="https://img.shields.io/badge/Python-PyQGIS-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Imagery-Multi--Source-00838F?style=flat-square" />

</div>

---

## Overview

**MultiSource Imagery Downloader** is a lightweight QGIS plugin for discovering, previewing, loading and downloading multi-source remote-sensing imagery. It integrates online imagery, STAC-based satellite search, historical-imagery resources and disaster-response imagery/catalogs into a compact dockable interface that follows the native QGIS visual style.

The plugin is designed for practical GIS and remote-sensing workflows. Users can define a study area directly on the map, switch between imagery sources, inspect search-result footprints, highlight selected scenes, estimate download scale, and manage download tasks without leaving QGIS.

## Features

- Online imagery and map services, including ESRI World Imagery, Tianditu vector/imagery layers and GEOVIS Earth imagery.
- AOI selection from current map extent, interactive rectangle drawing or active-layer extent.
- Tile download with real-time progress display.
- Start, pause, resume and cancel controls for download tasks.
- Download footprint slider on the QGIS map canvas to visualize the current tile being processed.
- GeoTIFF mosaicking and cropping after download.
- STAC search for Sentinel and Landsat imagery through providers such as Earth Search, Copernicus Data Space and Microsoft Planetary Computer.
- Search-result footprints displayed directly on the map canvas.
- Clear visual highlighting for the currently selected scene/source.
- Historical and disaster-imagery resource entries, including USGS, NASA Worldview, ESRI Wayback, Copernicus EMS, FIRMS, HDDS, UNOSAT, International Charter, NOAA, Jilin-1 and CRESDA-related resources.
- Local credential settings for Tianditu Key, GEOVIS tokens, Planet API Key and FIRMS MAP_KEY. Credentials are not hard-coded in the source code.
- QGIS-inspired green accent color and compact collapsible sections.
- English/Chinese interface support.

## Download behavior

The plugin does not impose a hard tile-count limit. When a task exceeds **20,000 tiles**, it displays an estimated workload/risk warning and asks for confirmation before continuing.

During download, the current tile extent can be displayed dynamically on the map canvas so users can see the actual download progress spatially rather than relying only on a percentage value.

## Installation

### QGIS Plugin Repository

After the plugin is published, it can be installed from **QGIS → Plugins → Manage and Install Plugins**.

### Manual installation

1. Download the plugin ZIP package.
2. Open QGIS.
3. Go to **Plugins → Manage and Install Plugins → Install from ZIP**.
4. Select the ZIP package and install it.
5. Open **MultiSource Imagery Downloader** from the QGIS plugin interface.

## Notes

Some imagery providers require an account, API key, token, subscription, or additional historical-imagery permission. The plugin only uses services within the permissions granted by the corresponding provider and does not bypass authentication, licensing, ordering, or access controls.

## Links

- GitHub repository: https://github.com/zhangyhrs/MultiSource-Imagery-Downloader-QGIS
- Issues: https://github.com/zhangyhrs/MultiSource-Imagery-Downloader-QGIS/issues
- GitHub profile: https://github.com/zhangyhrs

---

## Connect

<table align="center">
  <tr>
    <th width="33%">WeChat Official Account<br>微信公众号：测绘地信</th>
    <th width="33%">WeChat Mini Program<br>微信小程序：测绘地信</th>
    <th width="33%">Knowledge Planet<br>知识星球：测绘地理信息共享中心</th>
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
