---
description: >-
  Experiências de ensino de programação da linguagem Python nas disciplinas
  finais do Curso Técnico de Telecomunicações Integrado ao Ensino Médio.
---

# Aplicações em rede com Python

## ARC 2020.1

No primeiro semestre de 2020 (2020.1) a turma de ARC decidiu por projetar e implementar um sistema doméstico automatizado de hidroponia. Haveria um _hardware_ baseado em Arduino conectado a Internet para enviar dados de telemetria para um servidor remoto, onde o _software_ da aplicação cliente também receberia comandos para controle do sistema hidropônico.

Veja bem, eu disse "_Haveria..._". Com a pandemia, as aulas foram presenciais por apenas um mês, seguido por atividades não presenciais (ANPs) por todo o período restante (em torno de 3 meses e meio). Com isso, toda a parte de _hardware_ do projeto foi removida, e mantida parte da estrutura do _software_: telemetria ou dados enviados com regularidade para um sistema remoto conectado a um banco de dados de séries temporais (TSDB). Como documentação, foi produzido um [jogo-livro-apostila em formato multimídia](https://boidacarapreta.github.io/arc20201) (texto, código fonte em [Python](https://python.org/) e [podcast](https://anchor.fm/boidacarapreta)) - com [_**gameplay**_** completo**](https://youtu.be/039Wtug3DC0).

## ARC 2021.1

No primeiro semestre de 2021 (2021.1), houve o regresso do Python como linguagem adotada pela turma. Dessa vez, a temática de jogos foi mantida. Assim, acordamos em desenvolver jogos em modo texto através de um _chatbot_ do [Discord](https://discord.com/). O _framekwork_ adotado foi o [Errbot](https://errbot.io/). Toda a produção ao longo do semestre, desde a preparação do ambiente de desenvolvimento até o código fonte da aplicação, está publicada em [repositório público](https://github.com/boidacarapreta/arc20211). As metodologias ágeis, já parte do pacote indispensável da disciplina para a gestão do projeto, estão presentes: houve [6 entregas quinzenais](https://github.com/boidacarapreta/arc20211/milestones?direction=asc\&sort=due\_date\&state=closed) e acompanhamento por [quadro de tarefas](https://github.com/boidacarapreta/arc20211/projects/1?fullscreen=true). Os [vídeos das aulas](https://www.youtube.com/watch?v=ZTtCJd5yaPE\&list=PLje9mMro7hT38y3rPVQlX3N3MFuRXicKc) também estão disponíveis para o público em geral.

## ADC/IPT 2022.2

No segundo semestre (2022.2), mais uma retorno do projeto de Python com _chatbot_. Desta vez, os alunos tiveram mais liberdade de trabalho: podia ser jogo (ou não), podia ser em Python (ou não). Outra decisão dos alunos foi a integração das disciplinas ADC e IPT, logo o _bot_ deveria ter suporte a áudio ou vídeo em tempo real. A única solução encontrada foi abandonar qualquer _framework_ e utilizar diretamente as bibliotecas de Python ([discord.py](https://discordpy.readthedocs.io/)) e, para quem quisesse, Javascript ([discord.js](https://discordjs.guide/)). Como toda a atividade foi realizada na forma presencial, estão disponíveis o [repositorio público](https://github.com/boidacarapreta/adcipt20222) e projeto (com nova interface integrada: [_kanban_](https://github.com/users/boidacarapreta/projects/2) e [_milestones_](https://github.com/users/boidacarapreta/projects/2/views/2)).
