# PUC - Pontifícia Universidade Católica do Rio de Janeiro

<p align="center">
  <img src="https://images.squarespace-cdn.com/content/v1/59a8480fccc5c52fff14d38a/1529026153457-7W1EX1C6VUVUNIQN0CE1/image-asset.png" alt="PUC logo" border="0" width="100px">
</p>

# MVP desenvolvido para o módulo de Engenharia de dados do curso de Pós Graduação em Ciência de Dados e Analytics da PUC-RIO

### 🚀 Desenvolvedor
- <a href="https://www.linkedin.com/in/daniel-vcosta/">Daniel Vibranovski Costa</a> - daniel.vc7@gmail.com

## 🔍 Sumário

| Tópicos|
|---|
| [Definição do Problema](#-definição-do-problema)|
| [Etapas do Projeto](#-etapas-do-projeto)|
| [Estrutura do Repositório](#-estrutura-do-repositório)|
| [Tecnologias Utilizadas](#-tecnologias-utilizadas)|
| [Bibliotecas Utilizadas](#-bibliotecas-utilizadas)|
| [Executando em cloud](#-executando-em-cloud)|
| [Licença/License](#-licençalicense)|
| [Referências](#-referências)|
| [Agradecimentos](#-agradecimentos)|


## 📜 Definição do Problema

O dataset [Global AI Job Market & Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025) é um conjunto de dados que oferece uma análise abrangente do mercado de trabalho em inteligência artificial, com mais de 15.000 vagas reais coletadas nas principais plataformas de emprego do mundo. Ele inclui informações detalhadas sobre salários, requisitos das vagas, insights sobre as empresas e tendências geográficas.

Este repositório trata-se do projeto de engenharia de dados, aplicando conceitos de arquitetura de data warehouse e data lake. Foi construído uma pipeline de dados utilizando tecnologias na nuvem, escolhido para o projeto especificamente o Databricks. A pipeline envolve a busca, coleta, modelagem, carga e análise dos dados.

## 🪜 Etapas do Projeto

1) Definição do Problema.

2) Premissas ou hipóteses sobre o problema.

3) Modelagem e escolha de arquitetura.

4) Aplicação em uma plataforma na nuvem (Databricks).

5) Análise exploratória dos dados.


## 📁 Estrutura do Repositório

```
├── 📝 MVP_Eng_Dados.ipynb
├── 📝 README.md
```

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>README.md</b>: Arquivo que serve como guia e explicação geral sobre o projeto (arquivo atual).
- <b>MVP_Eng_Dados.ipnyb</b>: Notebook com a análise exploratória e pipeline de processamento dos dados.
- [Global AI Job Market & Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025).


## 👨‍💻 Tecnologias Utilizadas

- [Python 3.12.8 (Windows 64-bit)](https://www.python.org/ftp/python/3.12.8/python-3.12.8-amd64.exe): Linguagem de programação utilizada.

- [Spark](https://spark.apache.org/): é um mecanismo multilíngue para executar engenharia de dados, ciência de dados e aprendizado de máquina em máquinas ou clusters de nó único.

- [Databricks](https://www.databricks.com/): Databricks é uma plataforma unificada baseada em nuvem para engenharia de dados, ciência de dados e machine learning, construída sobre o Apache Spark. Ela permite que equipes colaborem de forma eficiente na construção, treinamento e implantação de modelos de IA e análise de grandes volumes de dados.


## 📄 Bibliotecas utilizadas

**Análise de dados**
1. [Pandas](https://pandas.pydata.org/): Biblioteca de software criada para a linguagem Python para manipulação e análise de dados. Em particular, oferece estruturas e operações para manipular tabelas numéricas e séries temporais.

2. [NumPy](https://numpy.org/): Biblioteca para a linguagem de programação Python, que suporta o processamento de grandes, multi-dimensionais arranjos e matrizes, juntamente com uma grande coleção de funções matemáticas de alto nível para operar sobre estas matrizes.

3. [PySpark](https://spark.apache.org/docs/latest/api/python/index.html):biblioteca Python para Apache Spark, que permite processar grandes volumes de dados de forma distribuída e eficiente. Ele oferece APIs para manipulação de dados, machine learning e streaming, integrando a facilidade do Python com a capacidade do Spark.

**Visualização em gráficos**

1. [Matplotlib](https://matplotlib.org/): uma biblioteca de visualização de dados em Python que permite criar gráficos estáticos, interativos e animados de forma simples e flexível. É amplamente usada para gerar plots, histogramas, gráficos de dispersão, entre outros.

2. [Seaborn](https://seaborn.pydata.org/): uma biblioteca de visualização de dados em Python baseada no Matplotlib, projetada para criar gráficos estatísticos mais atraentes e informativos com menos código. Ela oferece temas integrados, paletas de cores e funções para visualizar relações complexas entre variáveis.



**Suporte a Datasets** 
1. [KaggleHub](https://pypi.org/project/kagglehub/0.1.4/): Biblioteca para acessar datasets do Kaggle diretamente via Python, sem a necessidade de download manual pelo site. Facilita a integração de competições e bases de dados no fluxo de trabalho de ciência de dados.



## ⬇️ Instruções para execução do projeto

1. Clone este repositório em sua máquina local:

    ```
    git clone https://github.com/Vibranovski/Engenharia_Dados
    ```

3. Abra o arquivo no Databricks ou em um ambiente local com suporte a Jupyter Notebooks.

4. Execute as células do notebook para reproduzir o trabalho de análise e processamento dos dados.

## ☁️ Executando em cloud

O vídeo apresentando o sistema rodando em cloud está disponível em: <>.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://res.cloudinary.com/dujx0hv4e/image/upload/v1761245014/video_e2l6hc.png" alt="video"></img></a>


## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="#">Global AI Job Market & Salary Trends 2025</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="#">Daniel Vibranovski Costa.
</a> is 
licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## 🎓 Referências

### Artigos e papers clássicos

[1] CODD, E. F. A relational model of data for large shared data banks. Communications of the ACM, v. 13, n. 6, p. 377–387, 1970.

[2] DEAN, J.; GHEMAWAT, S. MapReduce: simplified data processing on large clusters. Communications of the ACM, v. 51, n. 1, p. 107–113, 2004.

### Livros fundamentais de bancos de dados

[1] ELMASRI, R.; NAVATHE, S. B. Sistemas de bancos de dados. 7. ed. São Paulo: Pearson Education do Brasil, 2019.

[2] SILBERSCHATZ, A.; KORTH, H. F.; SUDARSHAN, S. Sistema de bancos de dados. 7. ed. Rio de Janeiro: LTC, 2020.

### Bancos de dados distribuídos

[1] ÖZSU, M. T.; VALDURIEZ, P. Principles of Distributed Database Systems. 4. ed. New York: Springer, 2019.

## Data warehouse e modelagem dimensional (DW/BI)

[1] KIMBALL, R.; ROSS, M. The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling. 3. ed. Indianapolis: Wiley, 2013.

[2] INMON, W. H. Como construir o Data Warehouse. Rio de Janeiro: Campus, 1997.

### Governança de dados (framework e prática)

[1] DAMA INTERNATIONAL. DAMA-DMBOK: Data Management Body of Knowledge. 2. ed.New York: Technics Publications, 2017.

[2] LADLEY, J. Data Governance: How to Design, Deploy, and Sustain an Effective Data Governance Program. San Diego: Academic Press, 2019.

### Data lakes e Big Data (fundamentos e arquitetura)

[1] NOGUEIRA, I. D.; ROMDHANE, M.; DARMONT, J. Modeling data lake metadata with a data vault. arXiv preprint arXiv:1807.04035, 2018.

[2] GRÖGER, C. Building an industry 4.0 analytics platform. Datenbank-Spektrum, v. 18, p.5–14, 2018.


## 🙏 Agradecimentos

Agradeço à PUC-RIO e aos meus professores pela oportunidade de fazer esse MVP a partir da Sprint: Machine Learning & Analytics do curso de Pós Graduação em Ciência de Dados e Analytics da PUC-RIO.
