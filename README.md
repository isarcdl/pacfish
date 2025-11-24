
Pac-Fish é um jogo inspirado em Pac-Man, porém ambientado no fundo do mar. O jogador controla um peixe que deve percorrer um labirinto coletando bolinhas enquanto foge de tubarões que patrulham e perseguem. O jogo foi desenvolvido em Python utilizando a biblioteca Pygame, e inclui animações, câmera dinâmica, telas de início, vitória e game over, além de um sistema de pontuação, vidas e registro dos melhores tempos.

Para jogar, o usuário utiliza as setas do teclado para mover o peixe nas quatro direções. O jogo começa ao apertar a tecla espaço e pode ser reiniciado com a tecla R após uma derrota ou vitória. O objetivo é coletar todas as bolinhas do mapa sem perder as vidas, que diminuem sempre que o peixe colide com um dos tubarões.

Os tubarões possuem comportamento inteligente: cada um deles nasce na toca, fica preso por alguns segundos, passa por um breve período de “stun” e depois começa a se mover. Eles utilizam o algoritmo BFS para calcular caminhos no labirinto e perseguem o jogador somente quando ele está dentro de um raio específico definido em tiles. Caso contrário, movimentam-se de forma aleatória, simulando patrulha. A movimentação deles também considera direção e animação para que virem corretamente para o lado em que estão indo.

O mapa do jogo é baseado em um layout fixo composto por paredes e caminhos. As bolinhas são geradas automaticamente em todos os espaços caminháveis. O cenário é ampliado por uma câmera que acompanha o jogador enquanto ele se desloca, exibindo o fundo do mar e os objetos espalhados pelo mapa.

O jogo possui um sistema de pontuação que contabiliza 10 pontos por bolinha coletada, além de registrar o melhor score e os três tempos mais rápidos que o jogador já conseguiu completar o mapa. Quando todas as bolinhas são coletadas, o jogador vence, vê seu tempo e pode tentar novamente para melhorar suas marcas.

Para executar o Pac-Fish, basta ter Python instalado, juntamente com a biblioteca Pygame, e rodar o arquivo principal. Os gráficos são automaticamente ajustados ao tamanho do tile, e o peixe vira corretamente para esquerda ou direita de acordo com o movimento. O jogo é livre para estudo e modificação.

[![Assista ao vídeo](https://www.youtube.com/watch?v=BFtyI-5gzF0)
[![Assista ao vídeo](https://www.youtube.com/watch?v=q_4ifTnLWLw)

## Créditos e Referências

- Autor original: greyblue9 
- **Repositório original:**][GitHub - autor/repo](https://github.com/greyblue9/pacman-python)

## 📦 Instalação
Baixar ZIP
Clique no botão Code (canto superior direito do repositório)
Selecione Download ZIP
Extraia o arquivo em qualquer pasta do seu computador

