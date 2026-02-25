# 地理空间数据处理工具集

这是一个基于 Python 的 GIS 数据处理与分析工具集，使用 Jupyter Book 构建。

## 📖 在线阅读

访问在线文档：*(部署后更新此链接)*

## 🛠️ 工具集内容

### 1. 坐标系转换
- **坐标系转换 (trans_CRS)** - 批量转换 Shapefile 坐标系
- **Shapefile 范围查看与坐标系转换** - 查看空间范围并进行坐标转换

### 2. 格式转换
- **批量 Shapefile 转 GeoTIFF** - 矢量栅格化批处理
- **Shapefile 转 GeoTIFF 工作流** - 完整的矢量转栅格流程
- **KML 输出** - 将数据导出为 KML 格式

### 3. 数据处理
- **更改字段名称** - 批量修改属性表字段名
- **新增随机列表** - 为数据添加随机属性
- **转换 Shapefile 对应 JSON 字段属性** - 属性数据格式转换

### 4. 数据分析
- **管井高度变化值统计** - 时序数据统计分析
- **寻找映射关系** - 数据关联关系挖掘

## 🚀 快速开始

### 安装依赖

```bash
pip install jupyter-book
```

### 本地预览

```bash
cd my-book
jupyter-book start
```

然后在浏览器中访问 http://localhost:3000

### 构建静态网站

```bash
jupyter-book build .
```

## 📦 主要技术栈

- **GeoPandas** - 地理空间数据处理
- **Rasterio** - 栅格数据处理
- **Shapely** - 几何对象操作
- **PyProj** - 坐标系转换
- **Pandas** - 数据分析
- **Jupyter Book** - 文档构建

## 📝 许可证

MIT License

## 👤 作者

lishuhao
