# Jogo da Velha com praticas em HTML, CSS, DOM e eventos

## Projeto prático criado a partir do curso intensivo de JavaScript do Básico ao Avançado (c/ Node.js e projetos) da <a href="https://www.udemy.com/"> Udemy</a>.

Durante o curso intensivo de JavaScript, o jogo da velha foi um dos primeiros projetos práticos realizados por mim. Um clássico que você provavelmente já jogou rabiscando no papel durante a aula no colégio ou no intervalo com os amigos. 😄

Nesse projeto além de usar técnicas com HTML e CSS o foco também foi principalmente treinar muito a lógica.

## Índice

- <a href="#sobre-o-jogo">Sobre o projeto</a>
- <a href="#aparência-do-jogo">Aparência do jogo</a>
- <a href="#lógica-do-jogo">Lógica do jogo</a>
- <a href="#lógica-da-jogada-da-IA"> Lógica da jogada da IA</a>
- <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a>
- <a href="#desenvolvido-por"> Desenvolvido por</a>

## Sobre o jogo 📝

O usuário tem a opção de jogar contra um outro jogador físico:

https://github.com/amandaadev/project-udemy-jogo-da-velha/assets/116441572/ee64fbf4-18c3-4b11-9e3e-fbcb94323957

Ou contra a IA:

https://github.com/amandaadev/project-udemy-jogo-da-velha/assets/116441572/2e52fcb5-512b-41b5-bf32-8eb0b22d44b6

## Aparência do jogo ✅

Sobre a aparência do jogo, resolvi fazer uma pequena modificação na cor de fundo com um tom roxo e achei legal adicionar uma animação no título "Jogo da Velha".

https://github.com/amandaadev/project-udemy-jogo-da-velha/assets/116441572/8e7938a5-651e-4ed8-a4bf-94883b318ca9

Neste exemplo, estamos criando uma animação que desliza o título de cima para baixo. A animação dura 1 segundo e logo após usa uma função de aceleração.

## Lógica do jogo 🔄

O "X" sempre inicia o game. Somente depois de realizar uma jogada válida o sistema analisa se houve uma vitória, caso não tenha, inverte o turno e segue o jogo até alguém ganhar ou dar VELHA.

## Lógica da jogada da IA 🔄

Quando você joga contra a IA (Inteligência Artificial), ela faz suas jogadas de uma maneira simples e aleatória. Aqui está como funciona:

1. Preparação: A IA utiliza o símbolo "O" para suas jogadas.

2. Escolha Aleatória: A IA verifica cada caixa do tabuleiro, uma a uma. Se a caixa estiver vazia, a IA gera um número aleatório.

3. Decisão de Jogada: Se o número gerado for pequeno o suficiente, a IA coloca a bolinha "O" nessa caixa e termina sua jogada.

4. Tentativas Repetidas: Se a IA não conseguir encontrar uma caixa vazia na primeira tentativa, ela tenta novamente até encontrar uma caixa onde possa colocar a bolinha "O".

Com isso, essa lógica simples garante que a IA sempre faça uma jogada válida, sem usar estratégias complicadas. É uma maneira fácil e divertida de adicionar um adversário automático ao nosso jogo.

## Tecnologias utilizadas 🛠

<div>
<img alt="HTML" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg"> <img alt="CSS" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg">
 <img alt="JavaScript" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg">
</div>

## 👩🏽‍💻Desenvolvido por 👩🏽‍💻

### `Amanda Hellen` durante o <strong>Curso de JavaScript do básico ao avançado (c/ Node.js e projetos)</strong> da Udemy.

## Licença 📌

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
