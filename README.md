# BDGD GDB to Shapefile Converter

Script em Python para converter todas as camadas de uma BDGD (Base de Dados Geográfica da Distribuidora) do formato File Geodatabase (.gdb) para Shapefiles (.shp).
O código utiliza as bibliotecas GeoPandas e Fiona para leitura e exportação automática de todas as feature classes da geodatabase.
É recomendado ter QGIS ou ArcGIS Pro instalado no computador. Também é recomendado rodar direto do QGis.

Este código é útil para análises em ferramentas como OpenDSS, QGIS, ArcGIS, estudos de perdas técnicas, validação espacial e manipulação de dados geográficos.

Você precisa ter instalados:

pip install geopandas

É recomendado instalar a biblioteca fiona através da instalação do software QGIS.

---------------------------------------------
Edite o caminho da sua BDGD .gdb:

gdb_path = r"C:\caminho\para\sua\BDGD.gdb"


Defina a pasta de saída:

output_folder = r"C:\destino\para\shapefiles"


Execute o script:

python bdgd_gdb_to_shp_converter.py


Os arquivos .shp serão gerados automaticamente.
