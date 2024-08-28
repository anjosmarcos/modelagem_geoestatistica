# Organizando seus arquivos para a Modelagem Goestatística do Ambiente

Para garantir uma organização eficaz e facilitar o desenvolvimento de seus projetos na disciplina de Modelagem Geoestatística do Ambiente, recomendamos a adoção da seguinte estrutura de diretórios:

`project
|- src/             # código fonte
|- data/            # dados usados no projeto
|  |- r/            # dados no formato *.RDA
|  |- raster/       # dados matriciais (GeoTIFF)
|  |- vector/       # [dados vetoriais](https://moodle.utfpr.edu.br/mod/page/view.php?id=1696192) (SHP)
|- doc/             # documentos do projeto
|- res/             # resultados do projeto
|  |- fig/          # figuras (PNG, TIFF, JPEG, SVG)
|  |- tab/          # tabelas (CSV, TSV)
|- tmp/             # arquivos temporários   
|- README.md        # descrição do projeto`