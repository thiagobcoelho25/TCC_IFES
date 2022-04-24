<!-- ============== HEADER ============== -->
<div align="center" id="header">
  <a href="https://cachoeiro.ifes.edu.br/"><img src="assets\ifes-horizontal-cor.png" alt="Logo" width="60%"></a>
</div>

# Utilização de Algoritimos genéticos para Distribuição de patrulha Policial

> Este repositório tem por objetivo armazenar a codificação, os arquivos textuais em _latex_ como também os dados utilizados para a elaborados do trabalho de conclusão de curso no Instituto Federal do Espírito Santo - Campus Cachoeiro de Itapemirim, para o bacharelado em Sistemas de Infomação.

---

# Introdução

A distribuição das forças de segurança é uma questão estratégica de imensa importância, visto que o posicionamento adequado de forças de segurança em áreas de atuação na cidade pode aumentar a eficiência do patrulhamento e combate ao crime. Partindo dessa premissa, esse trabalho propõe novas formas de se distribuir o contingente policial levando em consideração vários critérios como número de habitantes por bairro, tamanho das áreas de atuação entre outros e se utilizou de algoritmo genético para a formação das áreas de atuação. Esse Trabalho utilizou-se da cidade de Cachoeiro de Itapemirim - ES como estudo de caso e consequentemente seu contingente policial para aplicação do algoritmo. Foi proposta uma nova configuração, com uma melhor distribuição policial levando em conta os atributos utilizados.

# tecnologias

Para o desenvolvimento desse trabalho, utilizou-se a linguagem de programação _Python_, juntamente com as bibliotecas para estruturação e análise de grande volumes de dados com vastas relações entre eles:

- **NumPy** - Biblioteca para a linguagem de programação Python, que suporta o processamento de grandes, multi-dimensionais arranjos e matrizes, juntamente com uma grande coleção de funções matemáticas de alto nível para operar sobre estas matrizes.
- **GeoPandas** - Projeto de código aberto para facilitar o trabalho com dados geoespaciais em Python.
- **Matplotlib** - Biblioteca de software para criação de gráficos e visualizações de dados em geral.
- **Pysal** - Biblioteca de código aberto para ciência de dados geoespaciais com ênfase em dados vetoriais geoespaciais escritos em Python.

A ferramenta de Sistema de Informação Geográfica, o **QGIS**, foi utilizada
para a construção do shapefile a partir do mapa obtido com a prefeitura. O Ambiente de Desenvolvimento ou IDE, utilizada no trabalho foi a Spyder 4, juntamente com o gerenciador de dependências Anaconda com a versão do Python 3.7.

# Organização do repositório

Os arquivos de codifiçacão, juntamente com os dados e o desenvolvimento dos _shapefiles_ da cidade então na pasta `codigo e dados/`. Nela também esta a atual distribuição de patrulha na cidade (`SETOR DE SERVIÇO_1.pdf`) como o programa principal (`Testando_Centroid_shapefile.ipynb`).

O diretório `atributos bairros/` estão os dados utilizados no trabalho por cada bairro. Nos diretórios `shapefile com ponte/` e `shapefile com ponte/` estão o resultados da construção do shapefiles da cidade, tendo uma levando em conta as pontes e a outra as desconsiderando.

No diretório `trabalho escrito/` estão os trabalhos elaborados
utilizando o [LaTeX] com o pacote [abnTeX2] para diagramação de texto, tanto o codigo fonte em _LaTeX_ em formato zip (`nome_aquivo_zip_latex.zip`) quanto o pdf (`pdf_trabalho.pdf`).

Nesse repositório, os slides elaborados para apresentações também são mantido. O diretório `presentations/` é dedidaco a este fim.

```

.
├── codigo e dados
│   ├── .ipynb_checkpoints
│   │   └── Testando_Centroid_shapefile-checkpoint.ipynb
│   ├── atributos bairros
|   |   ├── ÁREA_BAIRROS_SEPARADAMENTE_2018.ods_0.ods
|   |   ├── ÁREA_BAIRROS_SEPARADAMENTE_2018.ods_0.xlsx
|   |   └── ÁREA_POPULAÇÃO_BAIRROS_SEPARADAMENTE_2018.ods_0.ods
│   ├── shapefile com ponte
|   |   ├── Mapa_Cachoeiro.dbf
|   |   ├── Mapa_Cachoeiro.prj
|   |   ├── Mapa_Cachoeiro.shp
|   |   ├── Mapa_Cachoeiro.shx
|   |   └── Projeto_Mapa_Cachoeiro_com_pontes.qgz
│   ├── shapefile sem ponte
|   |   ├── Mapa_Cachoeiro.dbf
|   |   ├── Mapa_Cachoeiro.prj
|   |   ├── Mapa_Cachoeiro.shp
|   |   ├── Mapa_Cachoeiro.shx
|   |   └── Projeto_Mapa_Cachoeiro_com_pontes.qgz
│   ├── SETOR DE SERVIÇO_1.pdf
│   └── Testando_Centroid_shapefile.ipynb
├── trabalho escrito
│   ├── *****.pdf
│   └── ********.zip
│   ├── presentations
|   |   └── *****.ppt
presentations
├── README.md
└── environment.yml

```

# Autor:

[<img alt="ThiagoRibeiro" src="https://github.com/thiagobcoelho25.png?size=210" width="115"><br><sub>@Thiagobcoelho25</sub>](https://github.com/thiagobcoelho25)

<p align="right">(<a href="#top">back to top</a>)</p>
