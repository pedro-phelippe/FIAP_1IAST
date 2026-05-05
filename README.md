# FIAP_1IAST
Trabalhos do Curso IA Scientist 1IAST

## Tech Challenge Fase 1 
Criação: 2/4/2026

Prazo de entrega: 5/4/2026


### Referencia:
https://github.com/AnaRaquelCafe/POSTECH_AI_SCIENTIST/tree/main

### Grupo:
+ Cecília Fujita Abrahão
ceciliafujita@gmail.com

+ Natalia Pereira de Lima
delima.nataliapereira@gmail.com

+ Pedro Phelippe Lima da Silva
pedro.phelippe123@gmail.com



## Case NPS Preditivo

### Descrição do Projeto
https://github.com/ceciliafujita/FIAP_1IAST#:~:text=1IAST%20%2D%20Fase%201%20%2D%20Tech%20Challenge%20(1).pdf

### Objetivo do Projeto
O Case trata de um e-commerce que tem crescido e está querendo entender o porque do aumento expressivo de tantos detratores.
O objetivo é fazer uma análise detalhada da base de dados e gerar insights que explicam essa queda da nota do NPS e que ajudem a propor soluções. 
A descrição do problema e a respostas das primeiras perguntas estão no documento descritivo do projeto https://github.com/ceciliafujita/FIAP_1IAST#:~:text=8%20minutes%20ago-,TECH%20CHALLENGE.pdf,-Add%20files%20via.

### Base de Dados
https://github.com/ceciliafujita/FIAP_1IAST/blob/main/desafio_nps_fase_1.csv
#### Descrição da base de dados 
A base disponibilizada no link acima tem 2500 linhas de dados e 19 colunas. A base demostra a jornada de uma única compra de 2500 clientes únicos. Não tem campos nulos e tem um valor de nps_score medido no final dessa jornada.
Os demais detalhes sobre ela podem ser encontradas no início do notebook.

### Notebook
https://github.com/ceciliafujita/FIAP_1IAST/tree/main#:~:text=IAST1_TechChallenge_Fase1.ipynb

### Metodologia utilizada
Foram feitas análises exploratórias sobre os dados, uma matriz de correlação entre as variáveis e estudo sobre essas correlações para entender quais variáveis possuíam maior vínculo. O Atraso na entrega aresentou a correlação mais forte e negativa com a satisfação do cliente.
Fizemos uma distribução de notas do NPS por dias de atraso e uma distribuição da classificação do NPS (detrator, promotor e neutro) por dias de atraso para visualizar como o score se comportava à medida que o tempo aumentava. 
Por último, usamos uma regressão linear que nos ajuda a ver a probabilidade de um cliente se tornar detrator devido ao tempo de atraso e identificar o dia crítico onde a insatisfação supera 50%.

### Como reproduzir os resultados
O estudo foi gerado no Colab (https://colab.research.google.com/) e se encontra no notebook citado acima. Para reproduzir os dados, basta abrir pelo git o notebook no Colab e copiar a base de dados na raiz principal. Todas as análises poderão ser visualizadas e processadas normalmente. 


## Apresentação

### Respostas 1 e 2 do Case
https://github.com/ceciliafujita/FIAP_1IAST/blob/main/TC%20-%20Fase1%20-%20Respostas.pdf

### Canvas
https://www.canva.com/design/DAHIqrwKRk4/MUhQqD7W66cR2x7uAe9yhg/edit

#### PDF do Canvas
https://github.com/ceciliafujita/FIAP_1IAST/blob/main/TC%20-%20Fase1%20-%20Apresentac%CC%A7a%CC%83o.pdf

#### Apresentação
https://www.canva.com/design/DAHIqrwKRk4/QFeVC0wSz-C78ZTLzdqvSg/view?utm_content=DAHIqrwKRk4&utm_campaign=designshare&utm_medium=link&utm_source=recording_view
 




