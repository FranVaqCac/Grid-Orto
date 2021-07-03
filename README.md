# Grid-Orto
Plugin para el control de calidad de ortofotos (ICV) en QGIS.
Se implementa un complemento de QGIS para un control de calidad visual de las ortofotos de la Comunidad Valenciana que gestiona el Institut Cartogràfic Valencià (ICV). A partir de una base de datos Spatialite semilla, donde se encuentran todas las capas necesarias para dicho control, el complemento de dicha una copia para trabajar sobre él y genera una conexión a esa base de datos dentro de QGIS.
Se crean relaciones entre las tablas de la base de datos para conseguir barrer todas las hojas 1:5000 de las ortofotos con un flujo de trabajo ordenado y exhaustivo. El barrido se hace a partir de niveles de zoom a escala 1:2000 y 1:1000.
Finalmente, el resultado de este trabajo es obtener una capa de errores tanto geométricos como radiométricos encontrados en las ortofotos revisadas.
