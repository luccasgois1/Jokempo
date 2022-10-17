# Jokempo
Jogo de Jokempo com Diferentes linguagens

**Esquema do jogo:**
1. Objetos:

1.1. Player:
- Escolhe Pedra, Papel ou Tesoura
- Escolhe se deseja sair do jogo

1.2. Algoritmo de Otimização:
- Recebe jogadas do Player enviadas da Machine
- Retorna a jogada otima utilizando os processos internos do algoritmo

1.3. Machine:
- Memoriza jogadas do Player
- Gera jogadas aleatorias
- Gera jogadas otimizadas usando o algoritmo de otimização

2. Jogo:

2.1. One Player (Player x Machine)
- Gera Player 1 e Machine
- Player 1 escolhe jogada
- Verificar se Player 1 quer sair do jogo
- Machine gera jogada (Em paralelo?)
- Mostra resultado
- Volta a escolha do Player 1

2.2. Two Players (Player x Player)
- Gera Player 1 e Player 2
- Player 1 escolhe jogada
- Verificar se Player 1 quer sair do jogo
- Player 2 escolhe jogada
- Verificar se Player 2 quer sair do jogo
- Mostra resultado
- Volta a escolha do Player 1
