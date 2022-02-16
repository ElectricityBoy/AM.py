<img src="https://media3.giphy.com/media/j0kP7fOkKQlYsXTO2r/giphy.gif" align="right" width = "150"/>

# GRUPO DE ESTUDOS - Aprendizagem de Máquina
> ArtIEEEficiais - IEEE UFBA
### Súmario

**[Introdução](#Introdução)**<br>

### Encontros

- [x] Revisão de Git/GitHub e MarkDown - 09/02
- [ ]   ArtIEEEficiais: Uma breve Introdução e Revisão - 14/02
- [ ]  Classificação - 16/02
- [ ] Treinando Modelos - 21/02
- [ ] Mini-Projeto 1 - 23/02
- [ ] Máquinas de Vetores de Suporte - 28/02 
- [ ] Arvores de Decisão - 02/03
- [ ] Ensemble e Arvores Aleatórias - 07/03
- [ ]  Redução de Dimensionalidade - 09/03
- [ ]  Projeto Final - 16/03

# Introdução

A **Aprendizagem de Máquina** é a ciência da programação de computadores para que eles possam aprender com os dados. 

- Eles são comumente utilizados em problemas para os quais as soluções exigem um trabalho muito manual ou possui uma longa lista de regras.
- Problemas complexos para os quais não existe uma boa solução quando utilizmos uma abordagem tradicional.
- Compreensão de problemas complexos e com grande quantidade de dados.

## **Tipos de Sistemas do Aprendizagem de Máquinas**

Existem muitos tipos diferentes de sistemas de aprendizado de máquina, por isso é utilizado grandes classificações para facilitar na escolha.

- **[Aprendizado Supervisionado/Não Supervisionado](#Introdução)**<br>
- **[Aprendizado Online e em Lote](#Introdução)**<br>
- **[Aprendizado Baseado em Instância Versus Aprendizado Baseado em Modelo](#Introdução)**<br>

### **Aprendizado Supervisionado/Não Supervisionado**
Os sistemas de aprendizagem podem ser classificados de acordo com a quantidade e o tipo de supervisão que recebem durante o treinamento. Sendo eles:

### **Aprendizado Supervisioado**

Esse itpo de aprendizagem é quando tentamos prever uma variavel dependente a partir de uma lista **rótulos**. Ou seja, os dados são anotados com as respostas ou classes a serem previstas.

Uma das técnicas mais conhecidas para resolver problemas de aprendizado supervisionado estão regressão linear, regressão logística, redes neurais artificiais, máquina se suporte vetorial (ou máquinas kernel), árvores de decisão, k-vizinhos mais próximos e Bayes ingênuo.


### **Aprendizagem Não Supervisionado**

Como espero, nesse tipo de aprendizagem os dados de treinamentos não são rotulados. Nesse caso, é comumente aplicado quando queremos achar uma representação mais informativa dos dados que temos. Geralmente, essa representação mais informativa é também mais simples e segmentada. 

Exemplo:

| Dados       | Forma Representativa        |
| ------------- |:-------------:
| Registros de Compras     | Perfil dos Consumidores | 
| Transações Financeiras    | Detecção de Fraudes    | 
| Dados Multidimensionais | Redução da Dimensionalidade      |

Dentre as técnicas mais conhecidas para resolver problemas de aprendizado não supervisionado estão redes neurais artificiais, Expectativa-Maximização, clusterização k-médias, máquina se suporte vetorial (ou máquinas kernel), Clusterização Hierárquica, word2vec, análise de componentes principais, florestas isoladoras, mapas auto-organizados, máquinas de Boltzmann restritas, eclat, apriori, t-SNE.

### **Aprendizagem Semi-supervisionado**

Neste tipo de aprendizagem, o algoritmo lida com dados de treinamento parcialmente rotulados, uma grande quantidade de dados não rotulados e um pouco de dados rotulados.

A maior parte dos deles são combinações de algoritmos supervisionados e não supervisionados. Ademais, são geralmente utilizados em aplicações de agrupamento e categorização de objetos.


### **Aprendizado por Reforço**

Nessa abordagem, a máquina tenta aprender por sí só qual é a melhor ação a ser tomada, dependendo das circunstâncias na qual essa ação será executada. 
O que define a ação toamada em uma determinada situação é através da estratégia escolhida, chamada de **política**,  em que dependendo da decisão tomada, espera-se que o agente consiga associar as ações que geram maior recompensa para cada situação que o ambiente apresenta, e passe a evitar as ações que geram punição ou recompensa menor. Assim,Esse processo de visualização dos melhores cenários futuros é realizado repetidamente até que a máquina seja capaz de escolher a melhor ação a ser tomada para cada um dos cénarios possíveis a serem observados. 