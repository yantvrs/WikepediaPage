# Requisito #04 - Geração do Grafo no Gephi 📊🌐

## Descrição

Neste requisito, a tarefa é gerar uma figura no Gephi destacando o k-core e o k-shell da rede. Esses atributos referem-se a conceitos específicos relacionados à conectividade e centralidade dos nós em uma rede.

### 1. **k-core:**
   - **Definição:** O k-core de um grafo é uma subestrutura em que todos os nós têm pelo menos grau k, ou seja, cada nó no k-core está conectado a pelo menos k outros nós dentro do k-core.
   - **Aplicação ao Grafo:** No caso em questão, o k-core com um valor de 204 indica que os nós desse subgrafo estão altamente conectados, cada um tendo pelo menos 204 conexões dentro desse grupo específico.
   - **Interpretação Adicional:** Um alto valor de k-core sugere uma forte coesão entre os nós, formando um núcleo central altamente conectado na rede.

### 2. **k-shell:**
   - **Definição:** O k-shell de um grafo é uma camada específica onde os nós têm pelo menos grau k, mas não necessariamente todos os nós precisam ter o mesmo grau.
   - **Aplicação ao Grafo:** O k-shell com um valor de 195 indica que os nós nessa camada específica têm pelo menos 195 conexões, mas a distribuição exata dos graus pode variar.
   - **Interpretação Adicional:** A presença de um k-shell evidencia diferentes camadas de conectividade na rede, indicando áreas com um nível significativo de interligação.

### Visualização no Gephi:

![Requisito 4](https://github.com/yantvrs/WikepediaPage/blob/main/Requisito_4/requisito4.png)

A combinação destes dois conceitos permite uma análise mais profunda da estrutura da rede. Ao representar o k-core em vermelho, o k-shell em azul e os nós não pertencentes a nenhum desses grupos em preto, o grafo proporciona uma visualização clara das regiões altamente conectadas e centralizadas, destacando áreas específicas de importância na rede.

### Observações Finais:
   - **Nós em Preto:** Representam os nós que não fazem parte nem do k-core nem do k-shell, indicando áreas menos densamente conectadas na rede.
   - **Cores Distintas:** O uso de cores diferentes facilita a identificação visual das diferentes camadas, tornando a análise mais intuitiva.
   - **Importância da Análise:** A visualização do k-core e k-shell é fundamental para compreender a estrutura da rede, destacando padrões de conectividade e áreas-chave de influência.
