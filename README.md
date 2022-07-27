# Dark Souls

Implemente o nosso protótipo do "Dark Souls", seguindo os slides das aulas sobre Classe abstrata, Polimorfismo e Interface.

## Etapa 1

- Veja os slides "Classes Abstratas e Polimorfismo":

1. Crie a classe Inimigo e seus tipos: ZumbiLerdo, CavaleiroNegro e CavaleiroPrata. 
1. Crie uma classe Jogador, que recebe um Inimigo e causa dano via o método atacar(). Faça com o que quando um “jogador” ataque seja invocado o método tomarDano() do “inimigo”, retornando uma mensagem: "Jogador atacou o inimigo "+ inimigo.getNome()
1. Faça o método tomarDano() diminuir a vida do “inimigo” que foi atacado pelo “jogador”
1. Escreva os testes de unidade para todas as classes
1. Fazer a classe Principal com o método main é opcional

## Etapa 2

- Veja os slides "Classes Abstratas (parte 2)":

1. Evolua a Etapa 1 de forma que Inimigo seja uma classe abstrata, com o método atacar abstrato
1. Implemente as classes: Mago (que utiliza um cajado), Guerreiro (um machado) e Arqueiro (um arco). 
1. Cada classe que herda Jogador, deve implementar o seu método atacar(), que retorna suas respectivas mensagens
1. A classe Jogador e o método atacar() são abstratos
1. Crie os testes de unidade para testar todos os métodos das classes
1. Fazer a classe Principal com o método main é opcional

## Etapa 3

Veja os slides "Interface (parte 2)":

1. Termine de implementar o nosso protótipo do Dark Souls, evoluindo a Etapa 2
1. Considere que Mago, Sacerdote e CavaleiroPrata irão implementar Curavel
1. Escreva os testes de unidade para as novas funcionalidades
1. Fazer a classe Principal com o método main é opcional


---
Exemplo de código Java para exercitar Classe Abstrata, Interface e Polimorfismo.

Autor: Phyllipe Lima (UNIFEI)
