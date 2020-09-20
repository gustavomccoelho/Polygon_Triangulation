# Triangulação de polígonos

## Objetivo

O objetivo deste projeto é expor uma abordagem para o problema de triangulação de polígonos através do método de remoção de orelhas. O conteúdo do relatório se resume na explicação teórica dos métodos utilizados ao longo do algoritmo proposto e uma breve demonstração dos resultados de sua implementação, incluindo a demonstração da complexidade temporal assintótica.

## Método

A descrição teórica do método utilizado pode ser encontrada no relatório neste repositório.

## Implementação

Após a implementação do algoritmo proposto em linguagem Python, podemos apresentar os exemplos abaixo:

![polygon_1](/pictures/polygon_1.jpg)

![polygon_2](/pictures/polygon_2.jpg)

Como esperado, a complexidade do algoritmo se aproxima de um polinômio de segundo grau:

![runtime](/pictures/runtime.jpg)

## Conclusão

O algoritmo de triangulação de polígonos através de remoção de orelhas foi implementado em linguagem Python através dos métodos demonstrados neste relatório. A complexidade assintótica apresentada representa uma considerável melhoria de performance comparada à solução “força bruta”, onde a complexidade é proporcional a O_((n^4)). Há ainda outros métodos com maiores ganhos de performance, porém com maior complexidade teórica. Portanto o método proposto apresenta uma solução intermediária que pode ser útil em determinadas aplicações.
