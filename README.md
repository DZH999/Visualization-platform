# Visualization-platform
## 项目技术：Python、Flask、Ajax、Neo4j、PostgreSQL
## 项目介绍：
为实现中成药知识整合、提高数据关联性并挖掘数据的潜在价值，采用知识图谱存储结构结合可视化技术组织中成药临床技术、商业流通、标准规范等信息，搭建中成药知识图谱可视化平台。
## 项目亮点：
- 使用 **Python 爬虫技术**获取数据，并对其进行清洗，再将其存储在 PostgreSQL 数据库中；
- 根据 **Neo4j 数据库**构建中成药知识图谱，并使用 Flask 框架开发了中成药知识图谱可视化平台；
- 结合**自然语言处理技术**实现平台的中医药智能问答功能。

## 系统设计
首先从中成药数据的实际需求关系出发，选取必要的实体、属性等；然后使用爬虫技术从互联网上获取相关数据，存入对象关系型数据库 Postgresql，通过对中成药数据进行实体识别、关系抽取、整理分析，构建中成药知识图谱
并存入图形数据库 Neo4j中；最后利用 Python 中的 Flask 框架搭建可视化平台，实现数据的多角度展示以及智能问答。
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/3a0fc64f-139c-4eb1-ab26-cd9aef905e78)

## 效果展示
启动程序，输入http://127.0.0.1:5000/，得到界面。
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/ef655ddc-a0cb-4b2f-897a-5a2eaebb34b1)

知识图谱展示
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/789ffe66-ba7c-4717-b2f3-ab6cfab5fe36)

中成药数据库
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/a282c5cd-4dcc-457e-beb1-6bd8b57904e5)

中成药辅助筛选
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/cc09faca-366b-4594-b707-43243171f772)

医药智能问答
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/3c954bcc-2e4a-461d-a435-4fc3f6476493)

中成药知识图谱可视化
![image](https://github.com/DZH999/Visualization-platform/assets/68979616/c4cad492-9cd7-45e0-bc93-a54183a276c5)





