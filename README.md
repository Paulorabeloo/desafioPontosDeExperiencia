## Descrição

Você é um herói em um mundo mágico repleto de monstros e desafios. Sua missão agora é enfrentar inimigos e ganhar pontos de experiência (XP) para se tornar mais forte. A cada vitória, você ganha XP e se aproxima de se tornar um lendário campeão.

### Tarefa

Escreva um programa simples em JavaScript que simule o ganho de XP após derrotar um monstro. O programa deve calcular e exibir a quantidade de XP ganhos com base no nível do monstro e na dificuldade da batalha.

### Cálculo do XP:

Para calcular a quantidade de XP ganhos, o programa precisa considerar o nível do monstro (num1) e a dificuldade da batalha (num2). A fórmula a ser usada é:

XP Ganho = num1 × num2 × 100
XP Ganho=num1×num2×100

- num1: Nível do monstro. Quanto maior o nível, mais XP você ganhará ao derrotá-lo.
- num2: Dificuldade da batalha, variando de 1 a 100. Quanto maior a dificuldade, mais XP será ganho.
100: Um multiplicador constante que escala a recompensa de XP.

### Entrada

O nível do monstro (um número inteiro).
A dificuldade da batalha (um número inteiro de 1 a 100).

### Saída

Imprima a quantidade de XP ganhos após a batalha no formato:

Copiar código
Você ganhou X XP!
Onde X é o valor calculado pela fórmula.
