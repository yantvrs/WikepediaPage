# Requisito #03 - Criação dos gráficos CDP e PDF 📊🌐

## Descrição
Neste requisitos usaremos o Cumulative Density Function CDF e o Gráfico Probability Density Function (PDF) para fazer umas análises. Os desafios surgem quando lidamos com redes extensas, especialmente aquelas caracterizadas por complexidade significativa, com uma multiplicidade de arestas e vértices. Identificar determinadas características torna-se uma tarefa complexa nesse contexto. Em geral, ao depararmos com redes dessa natureza, optamos por análises alternativas que exploram aspectos mais estatísticos dessas métricas. Por isso que usaremos o CDF e o PDF.

## Gráfico Cumulative Density Function (CDF)
O CDF é uma ferramenta que busca identificar propriedades e centralidades mais complexas em uma rede, oferecendo uma visão acumulativa de probabilidades. Essa análise é realizada através da integral da área.

![CDF](https://github.com/yantvrs/WikepediaPage/blob/main/Requisito_3/images/requisito3_CDF.png)
Na análise do nosso gráfico, podemos ver que  90% dos vértices da nossa rede tem um grau aproximadamente 100 ou menos. Ou seja, 90% dos vértices tem 100 amigos ou menos. 
Podemos ver que o impacto na porcentagem total dos vértices que tem o maior quantidade de conexões é bem pouca.

## Gráfico Probability Density Function (PDF)
O PDF é outra ferramenta para análises, fornecendo a probabilidade em pontos específicos.
![PDF](https://github.com/yantvrs/WikepediaPage/blob/main/Requisito_3/images/requisito3_PDF.png)
No nosso gráfico, podemos ver aproximadamente 2,5% dos nós/vértices, 5000 mil, da nossa rede tem faixa de 0 a 100 vizinhos.
Também podemos ver que uma quantidade muito baixa de vértices que a rede tem, aproximadamente 100, tem uma grande quantidade de conexões, entre 250.

