---
description: >-
  Experiências de ensino de programação voltado para a Web nas disciplinas
  finais do Curso Técnico de Telecomunicações Integrado ao Ensino Médio.
---

# Jogos Web com Javascript

## ARC 2019.2

Em 2019, a turma de Administração de Redes de Computadores (ARC) projetava um dispositivo de atuação ampla: um walkie-talkie modular para atender a vários esportes. Além da base comum, seriam desenvolvidos módulos como botões de emergência, comunicadores de rádio e outros para atividades como ciclismo, caminhada em trilhas e outros. Porém, apesar da boa ideia, era não apenas ambiciosa, mas onerosa. Além disso, faltava algo... Sabe quando faltam os brilhos nos olhos? Pois bem, na metade do projeto adotamos um caminho radical: abandonamos o projeto todo, todo mesmo, e decidimos programar jogos Web com Javascript. Escolhido o _framework_ [Phaser](https://phaser.io) (versão 3), partimos para a concepção do jogo, arte visual e sonora e, claro, codificação. Para ajudar, foi montado um plano de metas para auxiliar na gestão do projeto:

![Plano de metas](../assets/jogo-6080821-20192.drawio.png)

## ARC 2020.2

No ano seguinte, no segundo semestre de 2020 ([2020.2](https://github.com/boidacarapreta/arc20202/)) o projeto ganhou em forma e conteúdo. Na forma, foi definido um calendário de [9 entregas quinzenais](https://github.com/boidacarapreta/arc20202/milestones?direction=asc\&sort=due\_date\&state=closed) - com listas de vídeos de aula - e [quadro de tarefas](https://github.com/boidacarapreta/arc20202/projects/1?fullscreen=true). No conteúdo, incorporou conceitos de TIP (graças às metodologias ágeis adotadas, como Scrum e Kanban, foi possível modificar o projeto original durante a sua execução), ampliando o escopo do projeto original: o suporte a voz, em tempo real, entre os 2 jogadores. Além disso, para demonstrar o conceito de aplicação cliente-servidor, foi criado um [código variante](https://github.com/boidacarapreta/arc20202/tree/tip) que integra, inclusive, um (outro conceito inicial de) jogo feito com a ferramenta [Twine](https://twinery.org/). Assim, embora ambos os jogos não foram concluídos, apresentam as funcionalidades mínimas de jogo multijogador com audioconferência, seja um jogo 2D, ao estilo RPG, como baseado em roteiro não linear ([_choose your story_](https://chooseyourstory.com/)).

## CAB 2020.2

Twine, aliás, que foi base também de um jogo baseado em roteiro não linear para a disciplina de Cabeamento Estruturado (CAB) [no mesmo semestre](https://github.com/boidacarapreta/cab20202). Aqui, o jogo atendeu a leitura dos conceitos e aplicação em um jogo de escolha de caminhos e resolução de problemas. Assim como ARC e TIP, o projeto teve conceitos de Scrum e Kanban: [quadro de tarefas](https://github.com/boidacarapreta/cab20202/projects/1?fullscreen=true) e [7 entregas quinzenais](https://github.com/boidacarapreta/cab20202/milestones?direction=asc\&sort=due\_date\&state=closed) com os [vídeos das aulas](https://www.youtube.com/watch?v=5A2EiefHOt0\&list=PLje9mMro7hT1Zp9Fd4UYo6quwJ4xUAvxd\&index=1). O formato adotado em ARC+TIP foi adotado também em CAB com o mesmo sucesso - com todo o conteúdo disponível para o público em geral: [https://ederson-torresini.github.io/cab20202/](https://ederson-torresini.github.io/cab20202/).

## ARC + TIP 2021.2

O segundo semestre de 2021 (2021.2) repetiu aquela a mesma fórmula: foi [desenvolvido (o conceito inicial de) um jogo Web para 2 jogadores com suporte a áudio em tempo real](https://github.com/boidacarapreta/integrado20212/). Muito foi aproveitado em termos de conteúdo, em especial código-fonte e vídeos. Os [vídeos das aulas](https://www.youtube.com/watch?v=YhmVsBq2cnk\&list=PLje9mMro7hT2YXZ-tYs55bQRftDPAWDKP) também ficaram disponíveis para o público em geral.

A novidade foi uma [apostila interativa](https://ederson-torresini.github.io/integrado20212/cliente/).

## ARC + TIP 2022.1

Em [2022.1](https://github.com/boidacarapreta/adcipt20221), mantivemos o formato do projeto. Porém, desta vez as aplicações cliente e servidor foram hospedadas separadamente: GitHub Pages e Heroku, além de suporte a salas de partidas simultâneas. Isso aumentou a complexidade de implementação desde 2020.2 (CORS, PWA etc.): com [versões para computador de mesa e móveis](https://github.com/boidacarapreta/adcipt20221/releases).

## ARC + TIP 2023.1

Em [2023.1](https://github.com/boidacarapreta/adcipt20231), o formato do projeto foi mantido (kanban e *milestones*). Porém, houve uma grande restruturação de código Javascript (uso de conceitos de orientação a objetos, como herança), de forma a permitir várias funcionalidades, tais como: canais de áudio ao longo de todo o jogo, sincronização de mudança de fases etc. Por causa disso, foi melhorada a documentação do [jogo modelo](https://github.com/boidacarapreta/adcipt20231/blob/main/jogo-modelo.md), incluindo trocas de mensagens entre jogadores e fluxogramas das cenas. Com isso, foi possível desenvolver uma aplicação [exclusiva para dispositivos móveis](https://github.com/boidacarapreta/adcipt20231/releases/tag/v1.0).

Também foi criada uma [aplicação da feira dos jogos](https://ederson-torresini.github.io/adcipt20231/), realizada no final do semestre.

## ARC + TIP 2023.2

Em [2023.2](https://github.com/ederson-torresini/adcipt20232), mais uma edição do formato bem sucedido do semestre passado. Neste semestre, foi aprovado um [projeto de ensino](https://github.com/feira-de-jogos/docs) no IFSC para o desenvolvimento de *hardware* para a feira de jogos. A [feira de jogos](https://www.youtube.com/watch?v=oHZfTP4w-qE&list=PLje9mMro7hT2DWAHDZ6ckM6iHwYJB3kEH), assim, contou com a participação do projeto de ensino em sua primeira versão:

- Os visitantes são convidados a criar uma conta no Banco Central da Feira de Jogos, online e com moeda 100% virtual.
- Os visitantes da feira jogam os jogos dos alunos. Se conseguirem terminar os jogos, podem converter esse progresso em moedas virtuais.
- Com o crédito no Banco Central, eles podem escolher entre:
  - Comprar comida na máquina de vendas (*vending machine*).
  - Alugar tempo na *lanhouse*. Os consoles disponíveis foram: Odyssey, Atari e SNES.
