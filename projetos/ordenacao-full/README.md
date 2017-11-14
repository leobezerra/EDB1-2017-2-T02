## Análise empírica - Ordenação

Ao longo desta disciplina, vocês implementaram os algoritmos de ordenação por comparação e estruturas de dados mais tradicionais:
* **Ordenação por comparação**: *selection, insertion, merge* e *quick sort*
* **Estruturas de dados**: vetores e listas duplamente encadeadas

Em sala, analisamos a complexidade teórica dos algoritmos de ordenação aplicados a **TADs Lista** implementados com vetores. Além disso,
analisamos a complexidade teórica das principais operações fornecidas pelo **TAD Lista** quando implementado com vetores ou listas encadeadas.

Além disso, na unidade anterior vocês fizeram uma análise experimental sobre a performance empírica destes algoritmos de ordenação quando aplicados ao TAD Lista implementado sobre vetores.

Neste exercício puramente experimental, você verá a performance dos algoritmos de ordenação quando aplicados a **TADs Lista** implementados com
diferentes estruturas de dados.

## Design do experimento

Você deverá utilizar os mesmos exemplos de entrada da análise realizada na unidade anterior. Assim, você poderá efetuar os seguintes tipos de análise:

* Análise do tempo de execução de cada algoritmo por estrutura de dados.
* Análise comparativa entre os dois conjuntos de implementações e a implementação padrão de ordenação fornecida pela linguagem escolhida (C ou C++).

## Orientações

A análise deverá ser fornecida como um relatório. Torne-o conciso, porém interessante. Os seguintes tipos de análise são sugeridos:

* Para cada subconjunto de entradas, faça um gráfico demonstrando o crescimento do tempo de execução médio ao longo do aumento dos tamanhos das entradas.
* Para um determinado tamanho de entrada, faça um gráfico demonstrando a variação (potencialmente o crescimento) do tempo de execução médio ao longo do aumento do grau de entropia dos vetores (diferentes subconjuntos).
* Ao comparar com o método padrão fornecido pela linguagem escolhida, explique o funcionamento deste método e porque ele é (in)eficiente.

## Prazos

Uma vez que este exercício exigirá um maior esforço computacional, seu prazo será maior do que o dos demais.
* *Deadline #1* (pontuação **integral**): Terça, 21/11/2017
* *Deadline #2* (pontuação **parcial**): Domingo, 26/11/2017

