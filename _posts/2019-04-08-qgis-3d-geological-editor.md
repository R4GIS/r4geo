---
title: QGIS Albion plugin
category: geology
feature_image: "https://github.com/geosaber/r4geo/raw/gh-pages/img/osm_bkground.png"
tags: QGIS, Volume, 3D, Geology, Borehole, cross section
---
## ***Build 3D geological model from wells information***
Este plugin fornece ferramentas para criar modelos geológicos 3D no QGIS.

[![Albion](https://github.com/geosaber/r4geo/raw/gh-pages/img/albion_oslandia.png)](https://github.com/Oslandia/albion)

### Nota
As camadas criadas são camadas de memória, os dados não são salvos, você deve usar a função qgis "Salvar Como" se você planeja armazenar a camada como uma camada shapefile ou spatialite, você também pode copiar/colar o recurso de camada em uma camada PostGIS que tem a estrutura certa. Isso se destina a maximizar a flexibilidade do formato de dados de origem.

[![Albion](https://github.com/geosaber/r4geo/raw/gh-pages/img/albion_qgis.png)](https://github.com/Oslandia/albion)

## Instalação rápida do desenvolvedor
Você precisa instalar as seguintes dependências:
- OpenGL para Python (python-opengl)
- QtOpenGL para Python (python-qt4-gl)
- shapely
- sphinx (python-sphinx)
- gitpython
- pytest, hipótese e simulação (somente para testes em execução)
Clone o repo em um diretório albion. Adicione o diretório contendo albion à sua variável de ambiente PYTHONPATH. Instale o pluign.

## Referências:
- [3D Borehole visualization](https://oslandia.com/en/2019/01/18/visualization-of-borehole-logs-with-qgis)
- [Albion - volume construction (O vídeo mostra como construir volumes 3D rápidos a partir de dados de furos)](https://vimeo.com/326854657)
