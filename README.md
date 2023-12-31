# Super Capi Fighters

![Logo](https://drive.google.com/uc?id=1RSpr67LFWhj-3PNCpu9DjL18iuv_TO1x)

## Sobre nós

### Desenvolvedores

O jogo em questão foi desenvolvido pelos alunos José Júlio Alves Campolina, Lucas Vieira dos Santos e Samuel Raimundo Lopes Pinto.

### Motivação

Trata-se do trabalho final da disciplina INF 216 - Projeto e Implementação de Jogos Digitais, ofertada como disciplina optativa no segundo semestre do ano de 2023 no curso de Ciência da Computação da Universidade Federal de Viçosa.

A disciplina foi ministrada pelo professor Lucas Nascimento Ferreira

## Objetivo do Jogo

O Super Capi Fighters é um jogo de luta baseado em personagens do universo de Dragon Ball. Atualmente, há apenas dois personagens, onde o Player 1 (esquerda) irá enfrentar o Player 2 (direita), sendo Goku e Vegeta os personagens disponíveis até então.

Como qualquer jogo de luta, o objetivo final é finalizar a barra de vida do oponente antes dele finalizar a sua. Para isso, pode-se utilizar recursos como socos e chutes, além de se defender para evitar tomar o dano completo de um ataque.

## Mecânicas

![Mecânica](https://drive.google.com/uc?id=1MorWlAphH-L7MGpITEdbidw2m6LEhC2S)

### Movimentação

Um dos pontos implementados a serem testados são as movimentações de ambos os jogadores. Importante pontuar que para simplificar as implementações, optamos por não permitir que o Player 1 e Player 2 invertam os lados.

### Animação das Sprites

Verificar se as animações estão fluidas, sem serem interrompidas e coerentes com os movimentos desejados.

### Detecção de Colisão

Verificar se as colisões estão coerentes, fazem sentido com o objetivo de jogo de funcionando corretamente. Optamos por deixar visíveis a hitbox dos ataques.

## Condição de Vitória

Atualmente, vence o usuário que derrotar primeiro o inimigo. Ao ser derrotado, o usuário terá uma animação de "morte" e não poderá mais se mover.

Além disso, ainda não implementamos HUD para visualizar a vida dos personagens. Importante pontuar que personagens começarão a luta com 100 de HP.

### Dano por ataque

> Ataque não bloqueados: 10 de dano

> Ataques bloqueados: 5 de dano

## Controles

Atualmente, o jogo possui as mecânicas de movimentação horizontal, pular, agachar, bloquear e os ataques soco e chute. Os comandos de cada um dos players estará descrito abaixo:

### Player 1 (Goku)

- **W** → Pular
- **A** → Andar para a esquerda
- **S** → Agachar
- **D** → Andar para a direita
- **E** → Bloquear
- **R** → Soco
- **T** → Pular

### Player 2 (Vegeta)

- **Seta para cima** → Pular
- **Seta para esquerda** → Andar para a esquerda
- **Seta para baixo** → Agachar
- **Seta para a direita** → Andar para a direita
- **Numpad 1** → Bloquear
- **Numpad 2** → Soco
- **Numpad 3** → Pular
