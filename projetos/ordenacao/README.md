## Análise empírica - Ordenação

Ao longo desta unidade, vocês implementaram os algoritmos de ordenação por comparação mais tradicionais: *selection, insertion, merge* e *quick sort*. 

Em sala, analisamos a complexidade teórica dos algoritmos de ordenação aplicados a vetores. Neste exercício puramente experimental, você analisará empiricamente a performance desses algoritmos neste contexto.

## Design do experimento

São fornecidos três [subconjuntos de entradas](instancias.tar.gz), diferindo quanto ao grau de ordenação das mesmas:

* *Subconjunto 1*: listas 10% ordenadas (**90% de entropia**).
* *Subconjunto 2*: listas 50% ordenadas (**50% de entropia**).
* *Subconjunto 3*: listas 90% ordenadas (**10% de entropia**).

Cada subconjunto apresenta listas de diferentes tamanhos gerados aleatoriamente utilizando diferentes sementes. Assim, será possível analisar os efeitos do tamanho e do tipo do subconjunto, tendo em mãos uma amostragem de tamanho razoável para propósitos estatísticos.

Especificamente, para cada subconjunto de entrada, execute todos os algoritmos e calcule o tempo médio que cada algoritmo gasta para cada tamanho presente no subconjunto. Assim, você poderá efetuar os seguintes tipos de análise:

* Análise do tempo de execução de cada algoritmo.
* Análise comparativa entre o seu conjunto de implementações e a implementação padrão de ordenação fornecida pela linguagem escolhida (C ou C++).

## Orientações

A análise deverá ser fornecida como um relatório. Torne-o conciso, porém interessante. Os seguintes tipos de análise são sugeridos:

* Para cada subconjunto de entradas, faça um gráfico demonstrando o crescimento do tempo de execução médio ao longo do aumento dos tamanhos das entradas.
* Para um determinado tamanho de entrada, faça um gráfico demonstrando a variação (potencialmente o crescimento) do tempo de execução médio ao longo do aumento do grau de entropia dos vetores (diferentes subconjuntos).
* Ao comparar com o método padrão fornecido pela linguagem escolhida, explique o funcionamento deste método e porque ele é (in)eficiente.

## Prazos

Uma vez que este exercício exigirá um maior esforço computacional, seu prazo será maior do que o dos demais.
* *Deadline #1* (pontuação **integral**): Domingo, 08/10/2017
* *Deadline #2* (pontuação **parcial**): Domingo, 15/10/2017

