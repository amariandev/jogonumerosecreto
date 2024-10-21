# Jogo do Número Secreto

Este projeto é um jogo simples onde o objetivo é adivinhar um número secreto sorteado aleatoriamente pelo sistema. Utilizei **HTML5**, **CSS3** e **JavaScript** para desenvolver a interface e a lógica do jogo, proporcionando dicas ao usuário a cada tentativa.

## Funcionalidades

- **Sorteio do Número Secreto**: Utilizando o método `Math.random()`, o sistema sorteia um número aleatório dentro de um intervalo predefinido.
  
- **Dicas ao Jogador**: A lógica de programação avalia o palpite do jogador e oferece dicas como "maior" ou "menor" para orientar suas próximas tentativas.

- **Interface Dinâmica**: O campo de entrada se ajusta conforme o jogo, e o botão de enviar palpite muda para "Novo Jogo" quando o jogador esgota suas tentativas ou acerta o número.

## Tecnologias Utilizadas

- ![HTML5](https://img.icons8.com/color/48/000000/html-5.png) **HTML5**: Estrutura do jogo e disposição dos elementos.
- ![CSS3](https://img.icons8.com/color/48/000000/css3.png) **CSS3**: Estilização da interface, tornando o jogo visualmente atraente.
- ![JavaScript](https://img.icons8.com/color/48/000000/javascript.png) **JavaScript**: Implementação da lógica do jogo, sorteio de número aleatório e dicas ao jogador.

## Como Funciona o Jogo

1. O sistema sorteia um número secreto entre um intervalo de 1 a 10.
2. O jogador tem várias tentativas para adivinhar o número.
3. Após cada palpite, o jogo oferece uma dica:
   - **Maior**: Se o número secreto for maior que o palpite.
   - **Menor**: Se o número secreto for menor que o palpite.
4. Se o jogador errar todas as tentativas, o jogo exibe a mensagem de fim de jogo e oferece a opção de iniciar uma nova partida.

## Como Executar o Jogo

1. Clone este repositório:
   ```bash
   git clonehttps://github.com/amariandev/jogonumerosecreto.git
