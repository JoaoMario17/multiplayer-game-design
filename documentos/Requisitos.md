# Requisitos do jogo SNAKE BATTLE

- **Quantidade de usuários por seção de jogo**

  Cada seção do jogo poderá possuir apenas dois jogadores, o jogo terá uma mecânica competitiva em que dois jogadores se enfrentaram

- **Mecânica básica do jogo**

  A mecânica do jogo é inspirada no jogo [serpente](<https://pt.wikipedia.org/wiki/Serpente_(jogo_eletr%C3%B4nico)>), que em resumo consiste no constante acumulo de pontos e o consequente crescimento físico do jogador que os acumula. Nesta adaptação duas serpentes compentem por pontos em um espaço limitado e tem como objetivo sobreviver por mais tempo que seu oponente enquanto acumulam pontos. A dificuldade de sobrevivência aumenta juntamente com o crescimento físico dos jogadores. Um jogador perde o jogo caso colida com outro jogador ou com as bordas do limite de espaço do jogo.

## Requisitos funcionais

A escrita dos requisitos funcionais será feita por meio do modelo de histórias de usuários.

- **HU01** _Criar uma nova conta de jogador_

  **Como** jogador

  **Quero** criar acessar a página de criação de conta, inserir meus dados pessoais necessários para a criação de uma nova conta e clicar no botão **criar nova conta**

  **Para** que eu possa futuramente realizar o login e ter acesso as demais funcionalidades

- **HU02** _Realizar login_

  **Como** jogador

  **Quero** informar os dados referentes a minha conta já criada e clicar no botão **fazer login**

  **Para** que eu possa então acessar o jogo e ter acesso as demais funcionalidades

- **HU03** _Alterar dados da conta_

  **Como** jogador

  **Quero** clicar no botão **alterar dados**

  **Para** fazer qualquer alteração nos dados da minha conta fornecidos durante a realização do meu cadastro

- **HU04** _Deletar conta_

  **Como** jogador

  **Quero** clicar no botão **deletar conta**

  **Para** deletar a minha conta juntamente com todo o histórico dos meus jogos armazenados pelo sistema

- **HU05** _Procurar partida_

  **Como** jogador

  **Quero** clicar no botão **procurar partida**

  **Para** encontrar um outro jogador como oponente e então iniciar uma partida do jogo

- **HU06** _Ver minhas melhores pontuações_

  **Como** jogador

  **Quero** clicar no botão **ver minhas melhores pontuações**

  **Para** vizualizar uma lista com as 10 melhores pontuações dentre o histórico de partidas joagados por mim

- **HU07** _Ver melhores pontuações_

  **Como** jogador

  **Quero** clicar no botão **ver melhores pontuações**

  **Para** vizualizar uma lista com as 100 melhores pontuações dentre o histórico de todas as partidas joagadas pelos jogadores de SNAKE BATTLE
  
  
  ## Requisitos não-funcionais
  
  - **HNF01** O Sistema será feito em JavaScript, utilizando Node/Express e Socket.io para o desenvolvimento do seu back-end.

  - **HNF02** O front-end do Sistema será feito utilizando HTML, CSS e Javascript, e para o desenho e animação das estruturas e componentes será utilizada a tag canvas.

  - **HNF03** O Sistema estará disponível nos idiomas Português e Inglês.
  
  - **HNF04** Será utilizado design responsivo para as interfaces gráficas, com foco para o sistema rodar em ambiente web.
