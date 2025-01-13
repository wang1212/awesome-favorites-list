<div align="center">
  <h1>Awesome-GIS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 GIS 技术资源。</p>
</div>

<br />

> 地理信息系统（Geographic Information System或 Geo－Information system，GIS）有时又称为“地学信息系统”。它是一种特定的十分重要的空间信息系统。它是在计算机硬、软件系统支持下，对整个或部分地球表层（包括大气层）空间中的有关地理分布数据进行采集、储存、管理、运算、分析、显示和描述的技术系统。

（Recommend）推荐一个其它的很棒的收藏列表， :point_right: https://github.com/sshuair/awesome-gis

## 目录

*Resource navigation list.*

- [技术规范标准（Technical Specifications）](#技术规范标准)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [论坛社区（Forum Community）](#论坛社区)
- [在线工具（Online Tools）](#在线工具)
- [地理空间库（Geospatial Library）](#地理空间库)
- [空间数据库（Spatial Database）](#空间数据库)
- [地图服务器（Map Server）](#地图服务器)
- [地图引擎（Map Engine）](#地图引擎)
  - [WebGIS](#webgis)
  - [移动 GIS（Mobile GIS）](#移动-gis)
- [GIS 系统平台（GIS System Platform）](#gis-系统平台)
- [更多（More）](#更多)

## 技术规范标准

*Official technical specifications.*

- [OGC](http://www.opengeospatial.org/) - 开放地理空间联盟（OGC）是一个致力于为全球地理空间社区制定高质量开放标准的国际非营利组织。
- [OSGeo](https://www.osgeo.org/) - 开源空间信息基金会，一个全球性非营利性组织，目标是支持全球性的合作，建立和推广高品质的空间信息开源软件。
  - [OSGeo 中国中心](https://www.osgeo.cn/)
- [EPSG](https://epsg.org/home.html) - EPSG 的维护组织 IOGP 官网。
- [GeoJSON Specification](https://geojson.org/) - GeoJSON 规范。:point_right: [简体中文翻译](https://www.oschina.net/translate/geojson-spec?cmp)
- [TopoJSON Specification](https://github.com/topojson/topojson-specification) - TopoJSON 规范，是 GeoJSON 的扩展，优化了数据结构和效率。
- [Mapbox Vector Tile Specification](https://github.com/mapbox/vector-tile-spec) - Mapbox 矢量瓦片规范，（MVT）。
- [MBTiles Specification](https://github.com/mapbox/mbtiles-spec) - MBTiles 规范，在 SQLite 数据库中存储瓦片数据。
- [UTFGrid Specification](https://github.com/mapbox/utfgrid-spec) - UTFGrid 规范，栅格化交互数据。
- [PMTiles](https://github.com/protomaps/PMTiles) - 单文件瓦片数据存档。
- [TileJSON Specification](https://github.com/mapbox/tilejson-spec) - 用来描述切片地图集的 JSON 格式规范。
- [ESRI Shapefile Technical Description](https://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) - ESRI Shapefile 白皮书，Shapefile 技术描述。
  - [ESRI Shapefile Info](https://www.loc.gov/preservation/digital/formats/fdd/fdd000280.shtml)
  - [Data File Header Structure for the dBASE Version 7 Table File](http://www.dbase.com/Knowledgebase/INT/db7_file_fmt.htm)
- [GeoPackage](https://www.geopackage.org/) - 开放的地理空间信息数据格式。
- [COG](https://cogeo.org/) - 云优化的 GeoTIFF 格式。
- [SpatioTemporal Asset Catalogs](https://stacspec.org/en) - 时空资产目录，统一交付时空数据集。

*More others 👉 [Awesome-Development-Technical-Standard-Specifications](awesome-dev-specifications.md)*

[`Go Top ↑`](#awesome-gis-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [EPSG.io](http://epsg.io/) - 全球坐标系统 EPSG 在线查询，同时提供 API 支持，MapTiler 提供支持。
- [Spatial Reference](https://spatialreference.org/) - 空间参考定义查询。
- [Format Descriptions for Geospatial Data](https://www.loc.gov/preservation/digital/formats/fdd/gis_fdd.shtml) - 地理数据格式描述参考。

[`Go Top ↑`](#awesome-gis-list)

## 论坛社区

*Forum communities related to GIS topics.*

- [GIS Stack Exchange](https://gis.stackexchange.com/) - 问答社区，**StackExchange** 的 GIS 话题组。
- [ArcGIS 知乎](http://zhihu.geoscene.cn/) - 由 Esri 中国创办。
- [GeospatialOnline](https://www.geospatialonline.com/)
- [GIS Lounge](https://www.gislounge.com/)

[`Go Top ↑`](#awesome-gis-list)

## 在线工具

*Online geographic data tools.*

- 在线数据（Online Data）
  - [GeoConverter](https://geoconverter.infs.ch/) - 通过 Web 在线地图服务导出 GeoTiff 数据。
  - [Geospatial Data Cloud](http://www.gscloud.cn/) - 在线数据下载。

- 坐标转换（Coordinate Transformation）
  - [坐标系转换](https://www.lddgo.net/base/class?classID=8)
  - [gdal3.js](https://gdal3.js.org/) - 栅格矢量数据转换。
  - [MyGeodata](https://mygeodata.cloud/) - 在线地理数据转换工具。

- 数据预览、编辑（Data Preview and Editing）
  - [TileJSON.io](https://tilejson.io/)
  - [GeoJSON.io](http://geojson.io/) - 一个快速、简单的工具，用于创建、查看和共享地图。

[`Go Top ↑`](#awesome-gis-list)

## 地理空间库

*Geospatial libraries, some libraries or modules that support manipulation of geospatial data.*

### C++

- [GDAL](https://gdal.org/) - 通用的栅格和矢量数据转换工具，OSGeo 开源项目。
- [PDAL](https://pdal.io/) - 点云数据处理。
- [PROJ](https://proj.org/) - 通用的坐标转换工具，OSGeo 开源项目。
- [Mapnik](https://mapnik.org/) - 空间数据可视化（支持 Node.js、Python），开源。
- [3dtiles](https://github.com/fanvanzh/3dtiles) - 可将 OSGB 转换为 3D Tiles 数据。

### Java

- [GeoTools](https://geotools.org/)
- [JTS](https://github.com/locationtech/jts)

### Python

- [OpenSfM](https://github.com/mapillary/OpenSfM) - Python 编写的 SFM，利用二维图像进行三维重建。
- [Raster Vision](https://docs.rastervision.io/) - 开源 Python 框架，用来构建卫星图、无人机摄影等栅格数据的视觉分析模型。
- [PyShp](https://github.com/GeospatialPython/pyshp) - 纯 Python 编写的 ESRI Shapefiles 文件读写工具。

### JavaScript

_Available in browser（JavaScript）. **Tips:** Most of what is available in the browser can also be used in Node.js._

- [Turf.js](http://turfjs.org/) - 高级空间分析的工具库（支持 Node.js）。
- [JSTS](https://github.com/bjornharrtell/jsts) - 开源的空间分析库。
- [proj4js](http://proj4js.org/) - PROJ 的 JavaScript 实现，可进行坐标系统转换（支持 Node.js）。
- [mapshaper](https://mapshaper.org/) - 数据编辑，支持 Shapefile、GeoJSON、TopoJSON、DBF 和 CSV 格式，可在线预览转换，支持命令行，不提供坐标转换（支持 Node.js）。
- [shapefile](https://github.com/mbostock/shapefile) - Shapefile 转 GeoJSON，支持命令行（支持 Node.js）。
- [shp2geojson.js](https://github.com/gipong/shp2geojson.js) - Shapefile 转 GeoJSON，可在线预览转换，支持坐标系转换。
- [Geobuf](https://github.com/mapbox/geobuf) - 对 GeoJSON 数据进行 [protocol buffers](https://developers.google.com/protocol-buffers) 编/解码，大幅减小体积，加快网络传输速度，**Mapbox 公司发布**（支持 Node.js）。
  - [pbf](https://github.com/mapbox/pbf) - protocol buffers 编/解码，**Mapbox 公司发布**（支持 Node.js）。
- TopoJSON
  - [TopoJSON Server](https://github.com/topojson/topojson-server) - TopoJSON 生成。
  - [TopoJSON Simplify](https://github.com/topojson/topojson-simplify) - TopoJSON 简化和过滤。
  - [TopoJSON Client](https://github.com/topojson/topojson-client) - TopoJSON 数据操作，例如合并、获取边界坐标等。
- [H3](https://h3geo.org/) - 六边形分级地理空间索引系统。
- [SuperCluster](https://github.com/mapbox/supercluster) - 点聚合算法。

[`Go Top ↑`](#awesome-gis-list)

## 空间数据库

*Spatial data, support geographic data storage, analysis, etc.*

- [PostGIS](https://postgis.net/) - 基于 [PostgreSQL](https://www.postgresql.org/) 数据库的空间扩展，提供了高级、复杂、强大的空间分析功能。
- [SpatiaLite](https://www.gaia-gis.it/fossil/libspatialite/home) - 基于 [SQLite](https://www.sqlite.org/index.html) 数据库的空间扩展，轻量级完整的空间数据库。

[`Go Top ↑`](#awesome-gis-list)

## 地图服务器

*Server application that can provide web map service resources.*

- Java
  - [GeoServer](http://geoserver.org/) - OSGeo 基金会项目。
  
- Node.js
  - [TileStrata](https://github.com/naturalatlas/tilestrata) - 基于 Node.js、Mapnik 的可插拔地图切片服务器。
  
- Python
  - [TileStache](http://tilestache.org/) - 基于 Python、Mapnik 的地图瓦片服务器。
  - [titiler](https://github.com/developmentseed/titiler) - 建立在 FastAPI 和 Rasterio/GDAL 之上的现代动态切片服务器。

- Others
  - [ArcGIS Server](https://enterprise.arcgis.com/) - 性能很好，**ESRI 公司开发的商业软件**。

[`Go Top ↑`](#awesome-gis-list)

## 地图引擎

*Map Engine Framework.*

- [osgEarth](http://osgearth.org/) - C++ 地理空间 SDK 和地图引擎。

### WebGIS

*WebGIS, Web front-end map framework. :point_right: [WebGIS](http://www.webgis.com/)*

- [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) - 2D/3D 地图引擎，**ESRI 公司开发**。

- [Leaflet.js](https://leafletjs.com/) - 目前最流行的、移动端优先、轻量级 Web GIS 开源框架。
  - [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw) - Leaflet 插件，矢量绘图、编辑工具，**Leaflet 官方发布**。
  - [Leaflet.fullscreen](https://github.com/Leaflet/Leaflet.fullscreen) - Leaflet 插件，地图全屏显示，**Leaflet 官方发布**。
  - [Leaflet-measure](https://github.com/ljagis/leaflet-measure) - Leaflet 插件，面积、距离测量。
  - [esri-Leaflet](https://github.com/Esri/esri-leaflet) - Leaflet 插件，用于在 Leaflet 中使用 ArcGIS 地图服务的一组轻量级 api，**ESRI 官方实现**。
  - [Tangram](https://github.com/tangrams/tangram) - Leaflet 插件，基于 WebGL 技术，利用矢量数据实时渲染 2D 和 3D 地图的引擎。
  - [wrld.js](https://www.wrld3d.com/) -  Leaflet 插件，基于 WebGL 技术的 3D 地图引擎。
  - [React Leaflet](https://react-leaflet.js.org/) - 基于 React.js 的 Leaflet 组件库。
  
- [Openlayers](https://openlayers.org/) - 一个开源的、高性能、功能丰富的二维地图引擎。

- [Cesium.js](https://cesiumjs.org/) - 目前最具优势的、功能丰富的开源三维地图引擎。

- [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/overview/) - 基于 WebGL 技术的现代化地图引擎，**Mapbox 公司开发**。
  - [React Mapbox GL](https://uber.github.io/react-map-gl/) - 基于 React.js 集成了 Mapbox GL 的实现，**Uber 公司维护**。
  - [Open Font Glyphs for GL Styles](https://github.com/openmaptiles/fonts) - 开放的标记字体和图标源，无需 token 与 key。
  - [Maputnik](https://maputnik.github.io/) - [Mapbox 样式规范](https://docs.mapbox.com/mapbox-gl-js/style-spec/)**开源**的可视化编辑器，**非 Mapbox 官方发布**。

- [MapLibre](https://maplibre.org/) - 开源的地图 SDK，最初基于 Mapbox GL 开发。

- [vis.gl](https://vis.gl/frameworks/) - 基于 GPU 的地理可视化套件。
  - [DECK.GL](https://deck.gl/) - 由 WebGL 驱动的大数据可视化框架，**Uber 公司开发**。
    - [kepler.gl](https://kepler.gl/) - 大型数据集的功能强大的开源地理空间分析工具。

- [MapillaryJS](https://mapillary.github.io/mapillary-js/) - 街景地图引擎，可与众多地图引擎（Leaflet/Openlayers/Mapbox GL 等）搭配使用。

- [iTowns](http://www.itowns-project.org/) - 3D 地理数据可视化引擎。
- [procedural-gl.js](https://www.procedural.eu/) - 基于 WebGL 构建 3D 地图的框架。 (⚠️ 不再维护)

### 移动 GIS

*Mobile GIS, native map framework for mobile devices such as Android and IOS.*

- [Tangram ES](https://github.com/tangrams/tangram-es) - C++ 库，使用 OpenGL ES 从矢量数据渲染 2D 和 3D 地图。
- [Mapbox GL Native](https://www.mapbox.com/mobile/) - C++ 库，使用 OpenGL ES（或 Metal） 渲染引擎和 MVT 矢量数据渲染地图，支持完全的自定义样式。

[`Go Top ↑`](#awesome-gis-list)

## GIS 系统平台

*GIS System Platform.*

- [OpenStreetMap](https://www.openstreetmap.org/) - 一个**开放**的全球地图数据平台。
  - [Protomaps](https://protomaps.com/) - 单文件世界地图。
- [QGIS](https://www.qgis.org/) - 开源数据可视化，编辑，分析工具平台，**OSGeo 项目**。
- [OpenDroneMap](https://www.opendronemap.org/) - 无人机航片拼图工具平台，**开源。**
- [MapTiler](https://www.maptiler.com/) - 一个提供地图设计，地图托管工具，地图服务等资源的平台，**开源。**
- [OpenMapTiler](https://openmaptiles.org/) - 基于 OSM 数据，提供**全套开源**工具以进行全球地图样式设计和自托管地图服务。
- [ArcGIS](https://www.arcgis.com/) - GIS 行业商业巨头，其商业软件几乎为行业标准，**商业软件**。
- [carto](https://carto.com/) - 空间数据分析平台。

[`Go Top ↑`](#awesome-gis-list)

## 更多

*More other unclassified resources.*

- [ESRI](https://www.esri.com/) - GIS 行业商业巨头，ArcGIS 发布者的官网。
- [Mapillary](https://www.mapillary.com/) - 街景地图平台。
- [Mapzen](https://www.mapzen.com/)
- [mapscii](https://github.com/rastapasta/mapscii) - 地图命令行渲染器，支持交互。
- 文章（Article）
  - [How to use OpenStreetMap and OS digital maps](https://www.cumbriasoaringclub.co.uk/kb/osm.php)
- [DipperMap](https://nav.dippermap.com/) - 地图资源导航站。

[`Go Top ↑`](#awesome-gis-list)
