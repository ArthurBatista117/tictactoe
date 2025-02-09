# tictactoe
 

Este repositório contém a implementação do jogo da velha (Tic-Tac-Toe) com um algoritmo de inteligência artificial baseado no Minimax. A interface do jogo não foi desenvolvida por mim, mas a lógica do Minimax foi completamente implementada por mim e está separada em um arquivo próprio.

Funcionalidades

Jogo da velha tradicional (3x3).

Implementação do algoritmo Minimax para um jogador IA.

A interface e a lógica do jogo estão separadas em arquivos distintos.

Estrutura do Projeto

/tictactoe
│── runner.py  # Arquivo responsável pela interface do jogo (não implementado por mim)
│── tictactoe.py    # Implementação do algoritmo Minimax (implementado por mim)

Como Executar

Certifique-se de ter o Python instalado na sua máquina.

Clone este repositório:

git clone [https://github.com/seu-usuario/tictactoe-minimax.git](https://github.com/ArthurBatista117/tictactoe)

Navegue até a pasta do projeto:

cd tictactoe

Execute o arquivo principal:

python runner.py

Como Funciona o Algoritmo Minimax

O algoritmo Minimax é uma técnica de tomada de decisão usada em jogos de dois jogadores. Ele funciona avaliando todas as jogadas possíveis e escolhendo a que maximiza as chances de vitória para a IA, assumindo que o oponente também joga da melhor forma possível. O algoritmo segue os seguintes passos:

Gera todas as jogadas possíveis no tabuleiro.

Avalia cada jogada atribuindo um valor (vitória, derrota ou empate).

Escolhe a jogada com o melhor resultado possível para a IA.

Contribuição

Se quiser contribuir, fique à vontade para abrir issues ou pull requests!

Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
