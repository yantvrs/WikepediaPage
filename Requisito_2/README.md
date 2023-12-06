# Requisito #02 - Criação dos grafos a partir do Gephi 📊🌐

## Descrição

Neste requisito, a representação visual da rede no Gephi destaca quatro perspectivas distintas, cada uma revelando facetas únicas de sua estrutura dinâmica. A seleção criteriosa dos atributos - Degree, Closeness, Betweenness e Eigenvector - orientou a filtragem dos nós exibidos em cada imagem.

## Legenda

Conjunto de cores para auxiliar no entendimento dos grafos. Quanto mais próximo de branco, menor o número do atributo, quanto mais próximo de azul, maior o número do atributo.

![Legenda de cores](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/image.png)

## Degree_Centraliy
Refere-se ao número de conexões que um nó possui na rede. Quanto maior o grau de um nó, mais conexões ele possui. Na centralidade de grau, um nó com alto grau é considerado mais central na rede.
![Degree_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/degree_centraliy.png)
### Interpretação:
- Os nós azuis, representados por Demographics Of Brazil, São Paulo, Empire Of Brazil e Immigration, foram identificados como desempenhando papéis centrais na rede. Esses elementos têm um alto grau de centralidade, sugerindo uma extensa rede de conexões. Em termos práticos, esses nós podem representar conceitos fundamentais e entidades de grande importância para o Brasil, como dados demográficos, a cidade de São Paulo, o Império do Brasil e questões de imigração.
- Os nós brancos, incluindo Fifa World Cup, Switzerland e Olympic Games, têm um grau de centralidade mais baixo. Isso indica uma quantidade menor de conexões na rede, sugerindo que esses elementos são mais periféricos. Na prática, eles podem representar eventos ou entidades relacionados ao Brasil de maneira menos central, como a Copa do Mundo da FIFA, a Suíça e os Jogos Olímpicos.



## Closeness_Centraliy
Mede a distância média de um nó para todos os outros nós na rede. Quanto mais próximo um nó está de todos os outros nós, maior é a sua centralidade de proximidade. É útil para identificar nós que podem alcançar rapidamente outros nós na rede.
![Closeness_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/closeness_centraliy.png)


## Betweenness_Centraliy
Avalia o quanto um nó atua como ponte entre outros nós na rede. Nós com alta centralidade de intermediação têm um papel crucial na comunicação entre diferentes partes da rede. São como "pontes" importantes para o fluxo de informações.
![Betweenness_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/betweenness_centraliy.png)


## Eigenvector_Centraliy
Considera a importância de um nó levando em conta a importância dos seus vizinhos. Nós com alta centralidade de autovetor são influentes, não apenas por terem muitas conexões, mas também por estarem conectados a outros nós importantes. É uma medida de influência global na rede.
![Eigenvector_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/eigenvector_centraliy.png)

