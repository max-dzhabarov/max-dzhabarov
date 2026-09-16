# Привет! Я Max Dzhabarov 👋

Я ГИС-инженер, специализирующийся на пространственных базах данных, автоматизации обработки геоданных и сопровождении геоинформационной инфраструктуры.

## Чем я занимаюсь

- проектирую решения на PostgreSQL/PostGIS и пишу пространственные SQL-запросы;
- автоматизирую загрузку, проверку и обновление геоданных;
- публикую пространственные данные через GeoServer и QGIS Server;
- настраиваю WMS/WFS/WMTS-сервисы, QGIS-проекты и серверную ГИС-инфраструктуру;
- разрабатываю прикладные алгоритмы пространственного анализа на PostGIS и pgRouting;
- создаю небольшие инструменты автоматизации на Python и PyQGIS.

## Опыт работы с инфраструктурой

Участвую в сопровождении корпоративной ГИС-инфраструктуры, включающей:

- 6 серверов;
- около 50 баз данных PostgreSQL;
- около 10 000 пространственных слоёв;
- 7 экземпляров GeoServer;
- около 300 опубликованных слоёв;
- порядка 1 000 пользователей ГИС.

## Технологии

`PostgreSQL` · `PostGIS` · `SQL` · `pgRouting` · `QGIS` · `QGIS Server` · `GeoServer` · `FME Workbench` · `Python` · `PyQGIS` · `GDAL/OGR` · `Linux` · `Nginx` · `WMS` · `WFS` · `WMTS`

## Портфолио

- [Переименование PostgreSQL-слоёв в QGIS](https://github.com/max-dzhabarov/qgis-postgresql-layer-renamer) — PyQGIS-скрипт для приведения имён слоёв к формату `schema_table`.
- [Нормализация геометрии в PostGIS](https://github.com/max-dzhabarov/postgis-geometry-normalization) — триггерная функция для безопасной подготовки полигональной геометрии перед сохранением.
- [Анализ транспортной доступности](https://github.com/max-dzhabarov/postgis-accessibility-analysis) — воспроизводимый пример расчёта доступности объектов по дорожному графу с PostGIS и pgRouting.
- [Осевые линии дорожных полигонов](https://github.com/max-dzhabarov/postgis-road-centerlines) — устойчивое построение осевых линий с нормализацией проблемных геометрий и резервными сценариями.
- [Сводные данные по АГР](https://github.com/max-dzhabarov/postgis-urban-data-integration) — демонстрационный ETL-процесс объединения семи табличных и пространственных источников в материализованное представление.

---

# Hello! I'm Max Dzhabarov 👋

I am a GIS Engineer specializing in spatial databases, geodata processing automation, and geospatial infrastructure support.

## What I do

- design PostgreSQL/PostGIS solutions and write spatial SQL queries;
- automate geodata loading, validation, and update workflows;
- publish spatial data with GeoServer and QGIS Server;
- configure WMS/WFS/WMTS services, QGIS projects, and server-side GIS infrastructure;
- develop applied spatial-analysis workflows with PostGIS and pgRouting;
- create small automation tools with Python and PyQGIS.

## Infrastructure experience

I contribute to the support of a corporate GIS environment that includes:

- 6 servers;
- about 50 PostgreSQL databases;
- about 10,000 spatial layers;
- 7 GeoServer instances;
- about 300 published layers;
- approximately 1,000 GIS users.

## Technologies

`PostgreSQL` · `PostGIS` · `SQL` · `pgRouting` · `QGIS` · `QGIS Server` · `GeoServer` · `FME Workbench` · `Python` · `PyQGIS` · `GDAL/OGR` · `Linux` · `Nginx` · `WMS` · `WFS` · `WMTS`

## Portfolio

- [Renaming PostgreSQL layers in QGIS](https://github.com/max-dzhabarov/qgis-postgresql-layer-renamer) — a PyQGIS script that renames layers using the `schema_table` convention.
- [Geometry normalization in PostGIS](https://github.com/max-dzhabarov/postgis-geometry-normalization) — a trigger function for safely preparing polygon geometries before they are saved.
- [Network accessibility analysis](https://github.com/max-dzhabarov/postgis-accessibility-analysis) — a reproducible PostGIS and pgRouting example for measuring facility accessibility over a road graph.
- [Road-polygon centerlines](https://github.com/max-dzhabarov/postgis-road-centerlines) — resilient centerline generation with invalid-geometry cleanup and fallback strategies.
- [Consolidated AGR data](https://github.com/max-dzhabarov/postgis-urban-data-integration) — a demonstration ETL workflow that merges seven tabular and spatial sources into a materialized view.
