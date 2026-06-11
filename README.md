# Jogo de Xadrez em C#

Projeto desenvolvido em C# com foco na aplicação prática dos principais conceitos de Programação Orientada a Objetos (POO), simulando uma partida completa de xadrez em ambiente console.

## Sobre o Projeto

Este projeto foi desenvolvido durante meus estudos de C# e Programação Orientada a Objetos, tendo como objetivo aplicar conceitos fundamentais da linguagem por meio da implementação das regras e mecânicas de uma partida de xadrez.

A aplicação permite que dois jogadores realizem uma partida completa diretamente pelo console, incluindo validações de movimentos, captura de peças, controle de turnos e regras especiais do jogo.

## Tecnologias Utilizadas

* C#
* .NET
* Programação Orientada a Objetos
* Git
* GitHub

## Funcionalidades

* Tabuleiro de xadrez completo (8x8)
* Controle de turnos
* Movimentação de todas as peças
* Validação de movimentos permitidos
* Captura de peças
* Controle de peças capturadas
* Identificação de xeque
* Identificação de xeque-mate
* Implementação do roque (castling)
* Implementação da captura En Passant
* Tratamento de jogadas inválidas

## Conceitos Aplicados

### Programação Orientada a Objetos

* Abstração
* Encapsulamento
* Herança
* Polimorfismo
* Composição

### Estruturas e Recursos da Linguagem

* Classes Abstratas
* Enumerações
* Coleções (HashSet)
* Exceções Personalizadas
* Modificadores de Acesso
* Propriedades e Métodos

### Modelagem de Domínio

O sistema foi estruturado em camadas responsáveis por representar:

* Tabuleiro
* Posições
* Peças
* Regras da partida
* Regras de movimentação
* Controle de estado do jogo

## Estrutura do Projeto

```text
tabuleiro/
├── Tabuleiro
├── Posicao
├── Peca
├── Cor
└── TabuleiroException

xadrez/
├── PartidaDeXadrez
├── PosicaoXadrez
├── Rei
├── Dama
├── Torre
├── Bispo
├── Cavalo
└── Peao
```

## Aprendizados Obtidos

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em:

* Modelagem orientada a objetos
* Estruturação de aplicações em C#
* Implementação de regras de negócio complexas
* Uso de herança e polimorfismo
* Tratamento de exceções
* Organização e reutilização de código

## Melhorias Futuras

* Interface gráfica
* Histórico de jogadas
* Modo jogador contra computador
* Salvamento e carregamento de partidas
* Exportação do histórico de movimentos

## Autor

Danilo Silva

Profissional de Tecnologia da Informação em transição para a área de desenvolvimento de software, aplicando conhecimentos em C#, .NET e Programação Orientada a Objetos através de projetos práticos.
