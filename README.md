# Mapserver-GUI-wrap

基于Mapserver构建的一套文件系统与数据库系统结合的开箱即用式GIS服务可视化管理软件，

目标是替换掉Geoserver的大部分市场。

## 应用场景

高度适用于最新的国土空间规划、智慧城市、CIM、城市大脑、数字孪生、元宇宙等应用场景。

## 软件优势

1.低价、开源。

2.文件系统+数据库系统模式管理，不用导入导出，便于拷备和汇交，符合GIS行业工作模式。

3.高性能，核心代码基于C开发。

4.基于CGI模式，实时切片，无需预切片操作。

5.一次配置多种数据格式输出，等PNG、MVT等。

6.支持shp、Sqlite3、POSTGIS等多种数据源。

7.支持OGC标准，可输出WMTS、WMS等多种服务。

8.支持CGCS2000、WGS84等多种坐标系。

## 软件截图

![服务管理页面](https://user-images.githubusercontent.com/9045263/153699227-a009091b-204d-4903-b89c-3bad7df2eeab.png)

![服务编辑页面](https://user-images.githubusercontent.com/9045263/153699249-dd632fbf-ab6d-4da0-9886-cc40595831a5.png)

![默认示例查看](https://user-images.githubusercontent.com/9045263/153699268-bcc49517-8efa-4142-b4d5-f8d85caa0c7f.png)

![快速开始介绍](https://user-images.githubusercontent.com/9045263/153699290-31dc6e1a-c5bd-4d17-974f-4c35fc06054c.png)

![配置说明文档](https://user-images.githubusercontent.com/9045263/153699308-94887b49-715a-4182-a323-a76f8a0b6eaf.png)

## 研发动机

本人从事GIS行业应用开发工作多年，深感GIS行业亟需革新。

1.目前市面上除Esri、超图、中地数码等商业公司的GIS服务引擎外，仅有Geoserver占据大量市场，GIS行业需要有更多开源软件的声音。

2.商业GIS服务引擎体积大、售价高，对个人开发者、小微企业、小型项目不友好。

3.Geoserver基于JAVA开发，Wicket框架过老，在性能和可维护性方面都较差。

4.官方维护的Mapserver，如：MS4W、DebianGIS、Homebrew等维护较差，文档较差，不便于使用。

5.商业GIS引擎与业务系统深度集成难，无法满足当前国土空间规划、智慧城市等应用场景的最新要求。仅最Geoserver新版虽开放了大量API，但更新缓慢且有较多BUG。

6.文件系统与数据库系统结合是目前GIS行业最合理的数据管理方式，便于拷备和数据汇交，市面上缺少一种文件系统+数据库结合的地图服务引擎。

7.ESRI File Geodatabase (FileGDB)格式广泛应用于GIS行业，但它作为一个闭源格式长期占据GIS市场本身就是一种不正常的现象。

8.实时切片，目前有大量应用场景需要高性能的实时切片技术。


## 收费情况

免费虽然好，但我也要吃饭，我想了个折中的办法：薄利多销，按需购买。

由于价格较低，购买后的软件不提供后续更新，如需更新请重新购买最新版本。

### 成品购买：

10元人民币/份

`如果你的朋友或公司有10块零钱,请购买一份后再使用，感谢支持！`

### 使用技术支持：

500元人民币/次

`具体内容待定`

### 源代码购买：

2000元人民币/份

### 二次开发技术支持：

2000元人民币/次

`具体内容待定`

## 联系方式

本人微信

![c996eb876e61f10117472c7713ae7a2](https://user-images.githubusercontent.com/9045263/153696421-dee4e4e2-8ecb-4b3f-9360-c58e9544777d.jpg)

