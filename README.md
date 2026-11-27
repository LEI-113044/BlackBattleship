# BlackBattleship

### Membros

| Curso | Número | Nome |
| :--- | :--- | :--- |
| LEI | 101283 | André Durães |
| LEI | 113044 | Simão Espanha |
| LEI | 123572 | Nelssy Pina |
| LEI | 129329 | Luís de Sousa |


# Product Backlog – Batalha Naval Online

**Produto:** [Batalha Naval – PaperGames.io](https://papergames.io/en/battleship)  
**Metodologia:** Scrum  
**Total de User Stories:** 20  
**Objetivo:** Criar um Product Backlog focado nas funcionalidades principais do jogo e facilitar a elaboração de testes Black Box.

---

## 1. Épicos

| Épico | Descrição | User Stories |
|---|---|---|
| Épico 1 | Acesso à plataforma e início do jogo | US01–US02 |
| Épico 2 | Configuração e visualização do tabuleiro | US03–US07 |
| Épico 3 | Mecânica de disparos | US08–US11 |
| Épico 4 | Gestão de turnos e resultados | US12–US15 |
| Épico 5 | Multijogador e gestão de partidas | US16–US20 |

---

## 2. Product Backlog – 20 User Stories

### Épico 1 – Acesso à plataforma e início do jogo

#### US01 – Aceder à página inicial
**Como** jogador,  
**quero** aceder à página inicial do jogo,  
**para** consultar as opções disponíveis.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - A página inicial deve ser apresentada corretamente.
  - As opções principais do jogo devem estar visíveis.
  - O utilizador deve conseguir interagir com os elementos disponíveis.

#### US02 – Iniciar uma nova partida
**Como** jogador,  
**quero** iniciar uma nova partida,  
**para** começar a jogar Batalha Naval.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - Deve existir uma opção para iniciar uma partida.
  - Ao selecionar essa opção, deve ser apresentada uma nova partida.
  - O tabuleiro deve estar disponível para jogar.

---

### Épico 2 – Configuração e visualização do tabuleiro

#### US03 – Visualizar o tabuleiro
**Como** jogador,  
**quero** visualizar o meu tabuleiro,  
**para** acompanhar a posição dos meus navios.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O tabuleiro deve ser apresentado no ecrã.
  - As células devem estar organizadas numa grelha.
  - O tabuleiro deve ser visualmente percetível.

#### US04 – Visualizar uma grelha de 10x10
**Como** jogador,  
**quero** ter um tabuleiro com 10 linhas e 10 colunas,  
**para** identificar facilmente todas as posições disponíveis.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O tabuleiro deve conter 10 linhas.
  - O tabuleiro deve conter 10 colunas.
  - Devem existir 100 células no total.

#### US05 – Visualizar a frota de navios
**Como** jogador,  
**quero** visualizar os navios disponíveis,  
**para** conhecer a frota que devo utilizar na partida.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - Os navios disponíveis devem ser apresentados.
  - Cada navio deve ter uma representação visual.
  - A frota deve corresponder aos navios definidos para o jogo.

#### US06 – Posicionar automaticamente os navios
**Como** jogador,  
**quero** posicionar automaticamente os meus navios,  
**para** preparar rapidamente o meu tabuleiro.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - Deve existir uma opção de posicionamento automático.
  - Os navios devem ficar dentro dos limites do tabuleiro.
  - Os navios não devem ocupar posições inválidas ou sobrepostas.

#### US07 – Visualizar o tabuleiro adversário
**Como** jogador,  
**quero** visualizar o tabuleiro do adversário,  
**para** escolher as posições onde pretendo disparar.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O tabuleiro adversário deve estar visível.
  - As posições disponíveis devem poder ser selecionadas.
  - A localização dos navios adversários não deve ser revelada antes de serem atingidos.

---

### Épico 3 – Mecânica de disparos

#### US08 – Efetuar um disparo
**Como** jogador,  
**quero** selecionar uma posição no tabuleiro adversário e disparar,  
**para** tentar atingir um navio inimigo.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O jogador deve conseguir selecionar uma célula.
  - Deve existir uma ação para efetuar o disparo.
  - O disparo deve ser registado na posição selecionada.

#### US09 – Identificar um disparo certeiro
**Como** jogador,  
**quero** receber uma indicação quando atingir um navio,  
**para** saber que o meu disparo foi bem-sucedido.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O sistema deve identificar um disparo que atinja um navio.
  - A posição atingida deve ficar visualmente assinalada.
  - Deve ser apresentada uma indicação de acerto.

#### US10 – Identificar um disparo falhado
**Como** jogador,  
**quero** receber uma indicação quando falhar um disparo,  
**para** saber que não atingi nenhum navio.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O sistema deve identificar um disparo sem navio.
  - A posição deve ficar visualmente assinalada.
  - Deve ser apresentada uma indicação de falha.

#### US11 – Impedir disparos repetidos
**Como** jogador,  
**quero** que o sistema identifique posições onde já disparei,  
**para** evitar repetir disparos na mesma célula.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - As posições anteriormente selecionadas devem estar identificadas.
  - O sistema deve impedir um novo disparo na mesma posição.
  - Deve ser apresentada uma indicação caso o jogador tente repetir um disparo.

---

### Épico 4 – Gestão de turnos e resultados

#### US12 – Alternar os turnos
**Como** jogador,  
**quero** que os turnos sejam alternados entre os jogadores,  
**para** garantir que cada jogador joga na sua vez.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - Cada jogador deve jogar no seu respetivo turno.
  - Após um disparo válido, o turno deve ser atualizado de acordo com as regras do jogo.
  - Não deve ser possível jogar fora do próprio turno.

#### US13 – Identificar o jogador ativo
**Como** jogador,  
**quero** visualizar quem está a jogar,  
**para** saber a quem pertence o turno atual.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O jogador ativo deve estar identificado.
  - A indicação deve ser atualizada após a mudança de turno.
  - A informação deve estar visível durante a partida.

#### US14 – Identificar um navio afundado
**Como** jogador,  
**quero** receber uma indicação quando um navio adversário for afundado,  
**para** acompanhar o progresso da partida.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O sistema deve identificar quando todas as posições de um navio forem atingidas.
  - Deve ser apresentada uma indicação de navio afundado.
  - O estado do navio deve ser atualizado no jogo.

#### US15 – Identificar o vencedor
**Como** jogador,  
**quero** receber o resultado final da partida,  
**para** saber quem venceu o jogo.

- **Prioridade:** P1 – Muito Alta
- **Critérios de aceitação:**
  - O sistema deve identificar quando todos os navios de um jogador forem afundados.
  - Deve ser apresentada uma mensagem de vitória ao vencedor.
  - Deve ser apresentada uma mensagem de derrota ao outro jogador.
  - A partida deve terminar após a condição de vitória ser atingida.

---

### Épico 5 – Multijogador e gestão de partidas

#### US16 – Criar um convite para jogar
**Como** jogador,  
**quero** criar um convite através de uma ligação,  
**para** convidar outra pessoa para uma partida.

- **Prioridade:** P2 – Alta
- **Critérios de aceitação:**
  - Deve existir uma opção para criar um convite.
  - O sistema deve gerar uma ligação para a partida.
  - A ligação deve poder ser partilhada com outro jogador.

#### US17 – Entrar numa partida através de um convite
**Como** jogador,  
**quero** entrar numa partida através de uma ligação de convite,  
**para** jogar com outra pessoa.

- **Prioridade:** P2 – Alta
- **Critérios de aceitação:**
  - O jogador deve conseguir aceder à ligação.
  - A ligação deve encaminhar o jogador para a partida correspondente.
  - O jogador deve conseguir entrar numa partida disponível.

#### US18 – Identificar o adversário
**Como** jogador,  
**quero** visualizar a identificação do adversário,  
**para** saber contra quem estou a jogar.

- **Prioridade:** P2 – Alta
- **Critérios de aceitação:**
  - O nome ou identificação do adversário deve estar visível.
  - A identificação deve corresponder ao jogador ligado à partida.
  - A informação deve manter-se atualizada durante o jogo.

#### US19 – Abandonar uma partida
**Como** jogador,  
**quero** abandonar uma partida em curso,  
**para** sair do jogo quando pretender.

- **Prioridade:** P2 – Alta
- **Critérios de aceitação:**
  - Deve existir uma opção para abandonar a partida.
  - O jogador deve conseguir confirmar a saída.
  - O sistema deve atualizar o estado da partida após a saída.

#### US20 – Iniciar uma nova partida
**Como** jogador,  
**quero** iniciar uma nova partida depois de terminar a anterior,  
**para** voltar a jogar.

- **Prioridade:** P2 – Alta
- **Critérios de aceitação:**
  - Deve existir uma opção para iniciar uma nova partida após o fim do jogo.
  - O novo jogo deve apresentar um tabuleiro reiniciado.
  - Os resultados da partida anterior não devem interferir com a nova partida.


