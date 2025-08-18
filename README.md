# Telecom X - Análise de Evasão de Clientes
## Alura + Oracle | Oracle Next Education | Tech Foundation
### Especialização Data Science

Respositório com a solução do desafio _Telecom X_ do **Programa ONE**.

## 🎯 Sobre o Desafio 🎯
Você foi contratado como assistente de análise de dados na **Telecom X** e fará parte do projeto **"Churn de Clientes"**. A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.
Seu desafio será **coletar, tratar e analisar os dados**, utilizando **Python** e suas principais bibliotecas para extrair insights valiosos. A partir da sua análise, os demais colegas da  equipe de Data Science poderá avançar para modelos preditivos e desenvolver estratégias para reduzir a evasão.

## 👨🏽‍💻 O que foi praticado: 👨🏽‍💻
✅ **Importar e manipular** dados de uma API de forma eficiente.  
✅ **Aplicar os conceitos de ETL** (Extração, Transformação e Carga) na preparação dos dados.  
✅ **Criar visualizações de dados** estratégicas para identificar padrões e tendências.  
✅ **Realizar uma Análise Exploratória de Dados (EDA)** e gerar um relatório com insights relevantes.  

## 🛠 Recursos Utilizados 🛠
Ferramentas, linguagens, bibliotecas e outros recursos usados na resolução do desafio:

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white)

# 🔎 Análises 🔍
As análises realizadas teve como objetivo avaliar informações como **faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais e menos vendidos e frete médio**.

## 💰 Faturamento Total de Cada Loja 💰
Calcular o **faturamento total de cada loja**, somando os valores da coluna **Preço** de cada loja para estimar o faturamento.

<Colocar imagem do gráfico>

**Análise:** O gráfico ilustra o faturamento total de cada loja. A Loja 1 lidera com o maior faturamento, totalizando R$ 1.534.509,12, seguida pela Loja 2 com R$ 1.488.459,06, Loja 3 com R$ 1.464.025,03 e, por último, a Loja 4 com R$ 1.384.497,58. Assim, podemos concluir que a Loja 1 obteve o melhor desempenho em faturamento, enquanto a Loja 4 apresentou o menor.

## 🛒 Vendas por Categoria 🛒
Calcular a **quantidade de produtos vendidos por categoria** em cada loja. A ideia é agrupar os dados por categoria e contar o número de vendas de cada tipo, mostrando as **categoria mais populares** de cada loja.

<Colocar imagem do gráfico>

**Análise:** O gráfico ilustra a participação de cada categoria de produtos no faturamento de cada loja. O objetivo foi identificar as categorias que mais contribuem para o faturamento e aquelas com menor impacto. Observou-se que a categoria de móveis é a principal responsável pelo faturamento em todas as lojas. Por outro lado, a contribuição das categorias de utilidades domésticas e instrumentos musicais apresentou flutuações, indicando variações em seu desempenho.

## 🌟 Média de Avaliação por Loja 🌟
Calcular a média das avaliações dos clientes para cada loja, com o objetivo de **entender a satisfação dos clientes com os produtos vendidos**.

<Colocar imagem do gráfico>

**Análise:** O gráfico ilustra a avaliação média da satisfação dos clientes em relação a cada loja, mensurada em uma escala de 1 a 5. A Loja 3 lidera em satisfação, com uma média de avaliação de 4,05, seguida pela Loja 2 com 4,04, Loja 4 com 4,00 e, por último, a Loja 1, com 3,98. Assim, podemos concluir que a Loja 3 obteve a melhor avaliação entre os clientes, enquanto a Loja 1 apresentou a pior, embora a diferença seja de apenas 0,07.
O gráfico apresenta uma linha que representa a média da avaliação geral entre as lojas, permitindo observar quais estão acima ou abaixo da média de satisfação de todas as lojas.

## 📈 Produtos Mais e Menos Vendidos 📉
Identificar quais produtos foram os mais vendidos e os menos vendidos em cada loja.  Ao final, visualizar os resultados de forma que fique claro quais produtos se destacaram nas vendas de cada loja.

<Colocar imagem do gráfico>

**Análise:** O gráfico ilustra os produtos mais e menos vendidos de cada loja. Podemos observar que a variação entre o produto mais vendido e o menos vendido em cada loja é significativa. Na Loja 1, o guarda-roupas teve 60 unidades vendidas, enquanto o celular ABXY vendeu 33 unidades. Na Loja 2, o livro "Iniciando em Programação" alcançou 65 unidades vendidas, enquanto o jogo de tabuleiro vendeu apenas 32. Na Loja 3, o kit de banquetas teve 57 unidades vendidas, enquanto o bloco de montar vendeu somente 35. Por fim, na Loja 4, a cama box vendeu 62 unidades, enquanto a guitarra teve 33 unidades vendidas.

## 🚛 Frete Médio por Loja 🚛
Calcular o custo médio de frete para cada loja. O objetivo é entender quanto, em média, está sendo gasto com frete para cada uma das lojas.

<Colocar imagem do gráfico>

**Análise:** O gráfico ilustra o custo médio com frete em cada loja. Considerando a ordem a partir do maior custo médio, a Loja 1 apresenta um custo de R$ 34,69, seguida pela Loja 2 com R$ 33,62, Loja 3 com R$ 33,07 e, por último, a Loja 4, com o menor custo médio, de R$ 31,28. O gráfico também apresenta uma linha que representa o custo médio do frete considerando todas as lojas, permitindo observar quais estão acima ou abaixo da média geral do custo de frete. 

## 📋 Relatório Final 📋

### ✅ Objetivo ✅

Este relatório analisa o desempenho de quatro lojas com base nos dados fornecidos (Faturamento, Categoria com maior e menor desempenho, Avaliação Média, Produto mais e menos vendido e Frete Médio, como pode ser visto na tabela abaixo) para determinar qual loja deve ser vendida, considerando o menor desempenho geral, com o objetivo de obter recursos para investimento em outro empreendimento.

| Loja | Faturamento | Categoria ➕ | Categoria ➖ | Avaliação Média | Produto ➕ | Produto ➖ |  Frete Médio |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Loja 1 | R$ 1.534.509,12 | Móveis (19,7%) | Utilidades Domésticas (7,2%) | ⭐ (3,98) | Guarda-roupas (60) | Celular (33) | R$ 34,69 |
| Loja 2 | R$ 1.488.459,06 | Móveis (18,7%) | Utilidades Domésticas (7,7%) | ⭐ (4,04) | Iniciando em Programação (65) | Jogo de Tabuleiro (32) | R$ 33,62 |
| Loja 3 | R$ 1.464.025,03 | Móveis (21,2%) | Instrumentos Musicais (7,5%) | ⭐ (4,05) | Kit Banquetas (57) | Blocos de Montar (35) | R$ 33,07 |
| Loja 4 | R$ 1.384.497,58 | Móveis (20,4%) | Instrumentos Musicais (7,2%) | ⭐ (4,00) | Cama Box (62) | Guitarra (33) | R$ 31,28 |


### 🏆 Conclusão 🏆

Com base na análise, a **Loja 4** é a recomendação para ser vendida.

**Justificativa:**

**Menor Faturamento:** A Loja 4 apresenta o menor faturamento (R$ 1.384.497,58), o que indica menor desempenho financeiro em comparação com as demais lojas. Essa diferença é significativa (R$ 150.011,54 em relação à Loja 1), sugerindo menor potencial de geração de receita.

**Avaliação Média Intermediária:** Embora a avaliação média (4,00) seja ligeiramente superior à da Loja 1 (3,98, ou seja, diferença de apenas 0,02), ela está abaixo das Lojas 2 e 3, indicando que não se destaca em satisfação do cliente.

**Compensações Insuficientes:** Apesar do menor frete médio (R$ 31,28), que seria uma vantagem, e da boa participação da categoria Móveis (20,4%), esses pontos não compensam o baixo faturamento, especialmente considerando que o objetivo é maximizar o retorno financeiro para investir em outro empreendimento.

**Comparação com Outras Lojas:**

* **A Loja 1**, apesar da menor avaliação e frete mais alto, tem o maior faturamento, indicando maior potencial de retorno.
* **A Loja 2**, embora tenha fraquezas em diversificação, apresenta maior venda do produto principal e boa avaliação média.
* **A Loja 3**, se destaca pela maior avaliação média e diversificação, com faturamento próximo ao da Loja 2.

Portanto, a Loja 4 é a que apresenta o menor desempenho geral, principalmente devido ao faturamento significativamente mais baixo e a satisfação do cliente é a terceira entre as quatro lojas. Isso indica que a loja pode ter dificuldades em atrair e reter clientes, o que pode impactar negativamente o retorno sobre o investimento, tornando-a a candidata ideal para venda, permitindo que os recursos sejam redirecionados para investimentos mais promissores.

---

# Extra! Análise de Desempenho Geográfico
O desafio consiste em explorar as coordenadas geográficas dos dados de vendas e identificar padrões relacionados à localização das compras. Para isso, foi criado um mapa de calor que permite compreender como as vendas variam conforme a localização geográfica.

<Colocar imagem do gráfico>

O mapa de calor permite visualizar a distribuição das vendas por local, facilitando a identificação de padrões e tendências. No caso, o imagem mostra a quantidade total de produtos comprados em diferentes locais, permitindo várias análises, como:
* **Locais com maior vendas:** Identificar os locais com o maior número de produtos comprados, como São Paulo (SP) sendo o principal comprador. Isso pode indicar onde a demanda é mais alta.
* **Locais com Menor Vendas:** Analisar os locais com menor número de produtos comprados, como Roraima (RR), Acre (AC) e Amapá (AP). Isso pode sugerir áreas com menor penetração de mercado ou interesse nos produtos. Isso pode gerar oportunidade, se considerar estratégias de marketing ou promoções para aumentar as vendas nessas áreas.
* **Regiões com Alto Desempenho:** Comparar o desempenho de diferentes regiões (Norte, Nordeste, Sul, Sudeste, Centro-Oeste) para entender onde as vendas são mais fortes. Por exemplo, o Sudeste tem um desempenho superior em comparação com outras regiões, podendo influenciar na criação de centro de distribuição.
* **Foco em Expansão:** Com base nas análises, recomendar áreas para expansão de negócios ou aumento de marketing.

Essas análises podem fornecer *insights* valiosos para a tomada de decisões estratégicas, ajudando a otimizar as operações de vendas e marketing.
