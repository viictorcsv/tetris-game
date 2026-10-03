# Jogo Tetris Clássico com JavaScript

Uma implementação do clássico jogo Tetris utilizando HTML5, CSS3 e JavaScript puro. Este projeto foi criado como uma forma de praticar a manipulação do DOM, a lógica de jogos e a programação orientada a objetos.

![Imagem do Jogo Tetris](https://github.com/user-attachments/assets/9b97e9fe-6c15-46e5-b819-6690d85077b8)

## Funcionalidades

-   **Movimentação Completa:** Mova as peças para a esquerda, direita e para baixo.
-   **Rotação de Peças:** Gire as peças para encaixá-las da melhor forma.
-   **Sistema de Pontuação:** Ganhe pontos ao completar linhas. A pontuação aumenta exponencialmente com mais linhas completadas de uma só vez.
-   **Próxima Peça:** Visualize a próxima peça para planejar seus movimentos.
-   **Aumento de Velocidade:** Acelere a queda da peça atual.
-   **Tela de "Fim de Jogo":** O jogo termina quando as peças chegam ao topo.
-   **Reiniciar o Jogo:** Pressione "Enter" para começar uma nova partida.

## Como Jogar

O objetivo é simples: complete linhas horizontais com os blocos que caem (Tetriminos). Quando uma linha é completada, ela desaparece e você ganha pontos. O jogo termina se a pilha de blocos atingir o topo da tela.

### Controles

-   **Seta para a Esquerda:** Mover a peça para a esquerda.
-   **Seta para a Direita:** Mover a peça para a direita.
-   **Seta para Cima:** Girar a peça.
-   **Seta para Baixo:** Acelerar a queda da peça.
-   **Enter:** Reiniciar o jogo após o "Fim de Jogo".

## Como Executar Localmente

Para executar o projeto na sua máquina, siga estes passos:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/viictorcsv/tetris-game.git
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd tetris-game
    ```

3.  **Abra o arquivo `index.html`:**
    Basta abrir o arquivo `index.html` no seu navegador de preferência. Não é necessário nenhum servidor local ou instalação de dependências.

## Estrutura dos Arquivos

O projeto está organizado da seguinte forma para manter o código limpo e modular:

```
.
├──  index.html      # Estrutura principal da página
├──  style.css       # Estilização visual do jogo
├──  script.js       # Lógica do jogo (movimentação, pontuação, etc.)
├──  rotations.png   # Imagem de sprite com as peças do jogo
├──  README.md       # Este arquivo
```

## Tecnologias Utilizadas

-   **HTML5:** Para a estrutura e elementos da página, como o `<canvas>`.
-   **CSS3:** Para a estilização, layout e design responsivo.
-   **JavaScript (ES6+):** Para toda a lógica e interatividade do jogo.

