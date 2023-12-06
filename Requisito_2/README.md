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
### Interpretação:
- Os nós azuis, representados por United Nations Department Of Economic And Social Affairs, Beira Alta Province, Recife e Miller Atlas, se destacam com uma Closeness Centrality maior. Isso indica que esses nós estão, em média, mais próximos de todos os outros nós na rede. Na prática, esses elementos podem ser considerados como pontos centrais que podem alcançar rapidamente outros nós na rede. Eles desempenham um papel crucial na conectividade eficiente do grafo.
- Os demais nós, que estão mais próximos da cor branca, têm uma Closeness Centrality menor. Isso sugere que esses nós estão, em média, mais distantes dos outros na rede. Embora possam ter conexões, sua capacidade de atingir rapidamente outros nós pode ser menor em comparação com os nós azuis.
- Essa análise fornece insights sobre a eficiência na capacidade de alcance dos nós na rede, destacando aqueles que são centralmente posicionados para uma rápida interação com outros nós.

## Betweenness_Centraliy
Avalia o quanto um nó atua como ponte entre outros nós na rede. Nós com alta centralidade de intermediação têm um papel crucial na comunicação entre diferentes partes da rede. São como "pontes" importantes para o fluxo de informações.
![Betweenness_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/betweenness_centraliy.png)
### Interpretação:
- O nó Brazil, em azul, destaca-se com uma Betweenness Centrality mais alta. Isso indica que este nó atua como uma ponte crucial entre outros nós na rede. Na prática, o Brazil desempenha um papel significativo na comunicação e no fluxo de informações entre diferentes partes da rede. Sua posição sugere uma importância central na interconexão de outros elementos.
- Os nós Rio De Janeiro e Fifa World Cup têm uma centralidade de intermediação significativa, embora não estejam em azul. Isso sugere que eles também desempenham papéis importantes como pontes na comunicação entre diferentes partes da rede. Apesar de não atingirem a mesma importância que o Brazil, ainda são elementos-chave para o fluxo de informações.
- Os demais nós, que estão mais próximos da cor branca, têm uma Betweenness Centrality menor. Isso indica que eles têm menos influência como pontes na comunicação entre outros nós. Apesar de suas conexões, sua participação no fluxo de informações entre diferentes partes da rede pode ser menos pronunciada.
- Essa análise destaca a importância do Brazil como uma ponte central na rede, enquanto o Rio De Janeiro e a Fifa World Cup também desempenham papéis intermediários significativos na comunicação entre diferentes partes do grafo.

## Eigenvector_Centraliy
Considera a importância de um nó levando em conta a importância dos seus vizinhos. Nós com alta centralidade de autovetor são influentes, não apenas por terem muitas conexões, mas também por estarem conectados a outros nós importantes. É uma medida de influência global na rede.
![Eigenvector_Centraliy](https://github.com/yantvrs/Data_structure_2/blob/main/U2T3/Requisito_2/images/eigenvector_centraliy.png)
## Interpretação:
- O nó Brazil, em azul, destaca-se com uma Eigenvector Centrality mais alta. Isso indica que este nó não é apenas influente devido ao número de suas conexões, mas também por estar conectado a outros nós importantes na rede. Em termos práticos, o Brazil exerce uma influência global significativa na rede, sendo central e conectado a outros elementos de importância.
- Os demais nós, que estão mais próximos da cor branca, têm uma Eigenvector Centrality menor. Isso sugere que, apesar de suas conexões, a influência global desses nós pode ser menor em comparação com o Brazil. Eles podem não estar tão fortemente conectados a outros nós influentes na rede.
- Essa análise destaca o papel central e a influência global do nó Brazil na rede, enquanto os outros nós podem ter uma influência mais limitada em comparação.





