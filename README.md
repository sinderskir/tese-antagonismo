# Antagonismo político nos discursos de parlamentares brasileiros
Bancos de dados, scripts e análises relacionados à minha tese em Ciência Política pela Universidade Federal do Paraná (UFPR). 

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

A triagem dos _tweets_ que continham as palavras-chave encontradas na Classificação Hierárquica Descendente (CHD), rodada pelo Iramuteq, foi feita usando o script [organizacao_corpus](https://github.com/sinderskir/tese-antagonismo/blob/main/organizacao-corpus.ipynb). Os termos utilizados para essa análise estão disponíveis no arquivo [termos_relevantes](https://drive.google.com/file/d/1g0ikJNah9NC82k-QdkUV7HPoiYobddQS/view?usp=sharing).

A amostra estratificada multivariada para a análise de conteúdo clássica, criada a partir do banco geral, foi criada com [este script](https://github.com/sinderskir/tese-antagonismo/blob/main/montagem-amostra.ipynb), usando a biblioteca pandas para Python.

### 📬 Contato
Em caso de dúvidas, sugestões ou interesse em colaboração, sinta-se à vontade para me enviar um e-mail:  
 [📧](mailto:rafaelasinderski@gmail.com)
