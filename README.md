# Antagonismo político nos discursos de parlamentares brasileiros
Bancos de dados, scripts e análises relacionados à minha tese em Ciência Política pela Universidade Federal do Paraná (UFPR).

**Looking for the English version? 🤔 Scroll down! It’s right below.**


![License](https://img.shields.io/badge/license-CC--BY--NC--SA%204.0-9cf.svg?style=flat)  
![Language](https://img.shields.io/badge/language-R%20%7C%20Python-007acc?style=flat)  
![Data size](https://img.shields.io/badge/data%20size-726k%20tweets-f7b731?style=flat)  
![Status](https://img.shields.io/badge/status-Completed-4caf50?style=flat)  
![Academic](https://img.shields.io/badge/use-Academic%20Research-6a1b9a?style=flat)


## 📘 Resumo
Este repositório reúne os dados e análises da pesquisa de doutorado intitulada **"Conflito político e democracia: uma análise das manifestações estratégicas de antagonismo dos parlamentares brasileiros no Twitter"**. O texto completo está disponível [aqui](https://acervodigital.ufpr.br/xmlui/handle/1884/95033).

O estudo investiga como parlamentares brasileiros constroem narrativas de antagonismo estratégico no Twitter — ou seja, como criam e reforçam a imagem de inimigos políticos como tática de disputa simbólica — em um contexto de **mal-estar democrático**.

A análise parte da seguinte pergunta:

> **Como se constrói e a quem se direciona o antagonismo nos tweets de deputados(as) e senadores(as)? E como isso se relaciona com a crise democrática no Brasil?**

### 🧪 Metodologia
- **Período analisado:** 2019 a 2022 (governo Bolsonaro)  
- **Base de dados:** 726.533 tweets publicados por 527 parlamentares com mandato no período  
- **Etapas da análise:**
  1. Análise de conteúdo automatizada (CHD) com **Iramuteq**
  2. Análise de conteúdo categorial com base em **amostra estratificada** (1.843 tweets)
 
### 🧩 Estratégias de antagonismo identificadas
A análise se baseou em sete estratégias extraídas da literatura:

- **Construção de alteridade**
- **Conspiração**
- **Estigmatização**
- **Ofuscamento**
- **Isca**
- **Reclamação**
- **Beligerância**

### 🎯 Hipóteses testadas
1. “Petistas” e “esquerdistas” serão os inimigos mais frequentes, especialmente entre parlamentares de direita  
2. O antagonismo será frequentemente voltado contra instituições democráticas (STF, imprensa, sistema eleitoral)  
3. Direita e esquerda usarão estratégias antagônicas com frequência semelhante, mas com **alvos diferentes**  
4. O antagonismo aumentará em ano eleitoral (2022)

### 📈 Principais resultados
- As estratégias mais utilizadas foram **conspiração** e **estigmatização**  
- Parlamentares de **extrema-direita** foram os mais antagônicos  
- **O ano eleitoral não apresentou aumento estatisticamente significativo** na presença de antagonismo  
- Houve evidências claras de **ataques sistemáticos a instituições democráticas**

### 🎲 Acesso aos dados
O banco geral (zipado) pode ser acessado [aqui](https://drive.google.com/file/d/1qnrSXQTGxmx2vCcvAdv5ahs_QdH41tV8/view?usp=sharing). A coleta foi feita com o [pacote _rtweet_ para linguagem R](https://github.com/sinderskir/tese-antagonismo/blob/15821240401d9ebea34b9ce28b06d0419ca1e9c6/coletas_tese.R) entre janeiro e fevereiro de 2023, antes que a política de acesso à API do Twitter/X fosse alterada, limitando consideravelmente o uso de dados da plataforma em pesquisas.

A triagem dos _tweets_ que continham as palavras-chave encontradas na Classificação Hierárquica Descendente (CHD), rodada pelo Iramuteq, foi feita usando o script [organizacao_corpus](https://github.com/sinderskir/tese-antagonismo/blob/main/organizacao-corpus.ipynb). Os termos utilizados para essa análise estão disponíveis no arquivo [termos-relevantes](https://drive.google.com/file/d/1g0ikJNah9NC82k-QdkUV7HPoiYobddQS/view?usp=sharing).

A amostra estratificada multivariada para a análise de conteúdo clássica, criada a partir do banco geral, foi criada com [este script](https://github.com/sinderskir/tese-antagonismo/blob/main/montagem-amostra.ipynb), usando a biblioteca pandas para Python.

### 📬 Contato
Em caso de dúvidas, sugestões ou interesse em colaboração, sinta-se à vontade para me enviar um e-mail: 📧 [rafaelasinderski@gmail.com](mailto:rafaelasinderski@gmail.com)

________________________________________________________________________

# Political Antagonism in the Discourse of Brazilian Parliamentarians  
Databases, scripts, and analyses related to my Ph.D. dissertation in Political Science at the Federal University of Paraná (UFPR).

## 📘 Summary  
This repository gathers the data and analyses from the doctoral research titled  
**"Political conflict and democracy: an analysis of strategic antagonism by Brazilian parliamentarians on Twitter."**  
The full text is available [here](https://acervodigital.ufpr.br/xmlui/handle/1884/95033).

The study investigates how Brazilian members of Congress construct narratives of **strategic antagonism** on Twitter — that is, how they create and reinforce the image of political enemies as a symbolic tactic — in a context of **democratic discontent**.

The research is guided by the following question:

> **How is antagonism strategically constructed and to whom is it directed in tweets by federal deputies and senators? And how does this relate to the democratic crisis in Brazil?**

### 🧪 Methodology  
- **Period analyzed:** 2019 to 2022 (Bolsonaro administration)  
- **Dataset:** 726,533 tweets published by 527 active parliamentarians during the period  
- **Analysis steps:**
  1. Automated content analysis (CHD) using **IRaMuTeQ**
  2. Categorical content analysis based on a **stratified sample** (1,843 tweets)

### 🧩 Identified antagonism strategies  
The analysis was based on seven strategies derived from the literature:

- **Construction of alterity**  
- **Conspiracy**  
- **Stigmatization**  
- **Obfuscation**  
- **Baiting**  
- **Complaint**  
- **Belligerence**

---

### 🎯 Hypotheses tested  
1. “Petistas” (supporters of the Workers’ Party) and “leftists” would be the most frequently targeted enemies, especially by right-wing parliamentarians  
2. Antagonism would often target democratic institutions (e.g., Supreme Court, press, electoral system)  
3. Left and right would show similar levels of antagonism, but with **different targets**  
4. Antagonistic discourse would be **more intense during the 2022 election year**

---

### 📈 Key findings  
- The most frequent strategies were **conspiracy** and **stigmatization**  
- **Far-right politicians** were the most antagonistic  
- The election year **did not show a statistically significant increase** in antagonistic discourse  
- There is strong evidence of **systematic attacks on democratic institutions**

### 🎲 Data access  
The complete (zipped) database is available [here](https://drive.google.com/file/d/1qnrSXQTGxmx2vCcvAdv5ahs_QdH41tV8/view?usp=sharing).  
Data collection was performed using the [**_rtweet_ package for R**](https://github.com/sinderskir/tese-antagonismo/blob/15821240401d9ebea34b9ce28b06d0419ca1e9c6/coletas_tese.R) between January and February 2023, prior to changes in Twitter/X API policies that significantly limited data access for research purposes.

The filtering of tweets containing keywords identified through the Descending Hierarchical Classification (CHD) in IRaMuTeQ was carried out using the script [organizacao_corpus](https://github.com/sinderskir/tese-antagonismo/blob/main/organizacao-corpus.ipynb).  
The terms used in this analysis are listed in the file [termos-relevantes](https://drive.google.com/file/d/1g0ikJNah9NC82k-QdkUV7HPoiYobddQS/view?usp=sharing).

The multivariate stratified sample for the classic content analysis, created from the full dataset, was generated using [this script](https://github.com/sinderskir/tese-antagonismo/blob/main/montagem-amostra.ipynb) with the **pandas** library in Python.

### 📬 Contact  
If you have any questions, suggestions, or are interested in collaboration, feel free to send me an email:  
📧 [rafaelasinderski@gmail.com](mailto:rafaelasinderski@gmail.com)
