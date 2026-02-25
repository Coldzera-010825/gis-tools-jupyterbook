# 地理空间数据处理工具集

欢迎来到 GIS 数据处理与分析教程！

## 📖 关于本书

本书收录了一系列基于 Python 的地理空间数据处理工具和教程，涵盖坐标转换、格式转换、数据处理和统计分析等常见 GIS 工作流程。

## 🗂️ 内容分类

### 1. 坐标系转换
- [坐标系转换 (trans_CRS)](trans_CRS.ipynb) - 批量转换 Shapefile 坐标系
- [Shapefile 范围查看与坐标系转换](shp-bounds-crs.ipynb) - 查看空间范围并进行坐标转换

### 2. 格式转换
- [批量 Shapefile 转 GeoTIFF (batch_shp2tif)](batch_shp2tif.ipynb) - 矢量栅格化批处理
- [Shapefile 转 GeoTIFF 工作流 (shp2tif_workflow)](shp2tif_workflow.ipynb) - 完整的矢量转栅格流程
- [KML 输出 (kml_ouput)](kml_ouput.ipynb) - 将数据导出为 KML 格式

### 3. 数据处理
- [更改字段名称](rename-fields.ipynb) - 批量修改属性表字段名
- [新增随机列表](add-random-column.ipynb) - 为数据添加随机属性
- [转换 Shapefile 对应 JSON 中的字段属性](shp-json-field-convert.ipynb) - 属性数据格式转换

### 4. 数据分析
- [管井高度变化值统计](pipe-height-stats.ipynb) - 时序数据统计分析
- [寻找映射关系](find-mapping.ipynb) - 数据关联关系挖掘

## 🛠️ 主要技术栈

- **GeoPandas** - 地理空间数据处理
- **Rasterio** - 栅格数据处理
- **Shapely** - 几何对象操作
- **PyProj** - 坐标系转换
- **Pandas** - 数据分析

## 🚀 快速开始

选择左侧导航栏中的任意教程开始学习！每个 notebook 都包含完整的代码示例和说明。
