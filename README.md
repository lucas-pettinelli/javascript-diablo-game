# Diablo Game Javascript Edition

🇧🇷 Um emocionante jogo da memória desenvolvido em JavaScript, inspirado no universo épico do jogo Diablo da Blizzard. Este projeto não apenas desafia sua memória, mas também incorpora uma tela de login para personalização da experiência. As cartas dos personagens são criadas dinamicamente através de arrays, e o jogo conta com funcionalidades como manipulação de dados com temporizador, checagem de entrada de dados, checagem de fim de jogo e combinação de cartas..&nbsp; <br>
<br>
🏴󠁧󠁢󠁥󠁮󠁧󠁿 An exciting memory game developed in JavaScript, inspired by the epic universe of Blizzard's Diablo game. This project not only challenges your memory but also incorporates a login screen for customizing the experience. Character cards are created dynamically through arrays, and the game has features such as data manipulation with a timer, data entry checking, end-of-game checking and card combination.. &nbsp;

## Funcionalidades

- Tela de Login:
  - Os jogadores podem se autenticar com um nome de usuário para personalizar a experiência com nome no mínimo de 3 caracteres, é utilizado uma validação de entrada de dados com removeAtribute e setAtribute.
  
- Criação Dinâmica de Cartas:
  - As cartas dos personagens são geradas dinamicamente a partir de arrays de dados e embaralhadas no load com Math.random.

- Manipulação de Dados com Temporizador:
  - Utilização de um temporizador para controlar o tempo decorrido durante o jogo iniciando o janela da página web com a função startTimer.

- Checagem de Fim de Jogo:
  - Verificação automática do término do jogo quando todas as cartas forem combinadas com firstCard e secondCard junto da função revealCard se todas forem iguais ao número de cartas da Array.

- Combinação de Cartas:
  - Implementação da lógica que verifica se as cartas selecionadas correspondem na função revealCard.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Como Usar

1. Clone este repositório em seu ambiente local.
```
git clone https://github.com/lucas-pettinelli/diablo-game-js.git
```
3. Abra o arquivo `index.html` em seu navegador preferido.

Sinta-se à vontade para explorar o código-fonte e personalizar conforme suas necessidades!

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias.

## Licença

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)&nbsp;
