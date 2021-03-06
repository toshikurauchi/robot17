# Projeto final


## Objetivos

* Grupo funcionar bem como equipe
* Aprendizado de um novo conceito / técnica
* O projeto precisa ter uma finalidade clara
* Deixar uma presença online
* Fazer uma apresentação


## Entregáveis

* Artigo de 5 páginas, formato de conferência.

* Presença online: blog ou páginas

* Vídeo de um demo (ou demo online)

* Apresentação


## Datas


Atividade | data
---|---
Scrum board no trello com atribuições individuais| 05/05
Acompanhamento de scrum-board:|  semanal
Primeira avaliação peer-review de trabalho em equipe| 12/05
Demonstração para professores da disciplina e encerramento do desenvolvimento| **26/05**
Apresentações e artigo|29/05
Última avaliação peer-review de trabalho em equipe| 02/06


### Calendário

Para sua conveniência
```
Maio 2017
Do 2a 3a 4a 5a 6a Sa
   1  2  3  4   5  6
7  8  9  10 11 12 13
14 15 16 17 18 19 20
21 22 23 24 25 26 27
28 29 30 31
```


Vamos fazer atendimentos extras para que a data seja mantida.


Não faz sentido estender mais o prazo por conta dos *deadlines** das outras disciplinas.



## Escopo

Veja a [lista de temas para brainstorm](https://github.com/mirwox/robot17/blob/master/guides/brainstorm_temas.md) para ter uma idéia de escopos possíveis para o projeto.

Dentro do escopo da disciplina, um sistema robótico é composto de três eixos:
1. Sensores
2. Atuadores
3. Técnicas de IA (probabilísticas, lógicas, comportamentais, etc)

Seu projeto precisa encontrar um balanço entre as três. Não é possível aprofundar-se em todas elas em um só projeto.

Por exemplo, imagine uma missão para o Neato. Digamos que seja dirigir-se até um ponto do 4.o andar e retornar ao ponto de partida, trazendo um objeto. Um projeto como esse vai usar um pouco de cada eixo: sensores, atuadores e técnicas de IA.   É razoável que utilize somente bibliotecas prontas do ROS e crie alguns scripts customizados.  Este seria um bom escopo para projeto desta disciplina.


Vamos a um outro exemplo:  queremos melhorar a odometria do Neato usando [uma unidade de medida de inércia](https://www.youtube.com/watch?v=NUNXcr_u9pM), ou [IMU](https://www.youtube.com/watch?v=NUNXcr_u9pM). Neste caso tudo em que estamos interessados é em medidas mais precisas de posição. Isto pode ser feito com uma técnica chamada [Kalman Filter](https://www.youtube.com/watch?v=fzjEMOOBuFA), que já tem bibliotecas prontas. Entretanto aplicar o Kalman filter vai exigir conhecer muito bem um sensor específico, neste caso a unidade inercial, e trabalhar na matemática para combinar estes dados com a odometria do Neato.

Num outro extremo, veja estes [Genetic Cars](http://rednuht.org/genetic_cars_2/). São veículos sem sensores e sem atuadores, sem problemas físicos de incerteza sensorial e de controle de movimento.  Uma implementação assim poderia ser um projeto válido, desde que a técnica principal (algoritmos genéticos) fosse implementada pelo grupo, minimizando o uso de bibliotecas prontas.  Um outro exemplo de algoritmos genéticos em ação pode ser visto neste caso, [para bípedes](https://www.youtube.com/watch?v=jIjPTuekCcM).

O número de membros do grupo também influi. Um escopo mais restrito sugere grupos de 2, ao passo que um projeto com diversas partes vai exigir um escopo mais amplo.

##
