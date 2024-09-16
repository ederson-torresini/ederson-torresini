# Maquete viva

E se o curso de Ensino Médio Integrado em Telecomunicações pudesse ser apresentado em uma única disciplina? Esta é a proposta de Introdução às Telecomunicações (ITL). Foi elaborado, então, um modelo de projeto a ser aplicado regularmente: uma maquete viva composta de sistemas elétrico, telefonia e redes de computadores - e pensar o futuro das telecomunicações.&#x20;

## ITL 2022.1

No primeiro semestre 2022 (2022.1) foi realizada a primeira edição do projeto. O resultado foi bastante expressivo para os alunos: uma visão mais sistêmica de telecomunicações e do próprio curso. Embora não foi possível implementar a economia na cidade, com as vendas de espaços privados como casas e apartamentos, a maquete foi entregue em sua totalidade: cada bairro tinha um circuito independente de energia elétrica controlado remotamente. O código fonte está disponível:

* Mesa de controle:
  * Raspberry Pi: [código em Python para aquisição da entrada de dados pelo Xbox Controller](https://github.com/boidacarapreta/itl20221).
  * Micro:bit: [código em blocos para transmissão dos dados aos bairros](https://ederson-torresini.github.io/itl20221-mesa-de-controle/).
* Bairros:
  * Micro:bit: [código para o bairro 5 a ser usado como modelo](https://ederson-torresini.github.io/itl20221-bairro-5/).
  * Micro:bit: [teste de tensão entre Micro:bit e circuito do bairro](https://ederson-torresini.github.io/itl20221-teste-de-tensao/).

Também está disponível um [modelo simulado com a mesa de controle e dois bairros de portes diferentes](https://www.tinkercad.com/things/l8LGc3b3HMY?sharecode=zevMMf\_lV\_8XAn8LCEJzz\_A8g1mEmMNsX24cGnyaRso) (4 e 6 postes de luz) e [algumas fotos das aulas](https://www.instagram.com/maquete\_ifsc2022/).

## ITL 2022.2

No segundo semestre de 2022, houve algumas mudanças significativas no modelo de projeto anterior. A principal foi a troca de telefonia por mais tempo dedicado a programação com Micro:bit, o que gerou um [repositório com as atividades em sala](https://github.com/boidacarapreta/itl20222/commits/aulas). A maquete também contou com um ponto de acesso Wi-Fi provido pela Raspberry PI (com a aplicação [`hostapd`](http://w1.fi/hostapd/) como serviço), código esse também [publicado](https://github.com/boidacarapreta/itl20222).

Também estão disponíveis [algumas fotos das aulas](https://www.instagram.com/maquetedetele/).

## ITL 2023.1

Nesta terceira edição do projeto, o escopo da maquete foi reduzido para dar mais ênfase às tecnologias. Ao invés de uma cidade, foi projetado um bairro com casas inteligentes. Na parte elétrica, houve mais foco dentro das casas que nas linhas de transmissão. Na telefonia, foi construído um sistema interno de interfonia entre as residências, com o uso de centrais PBX, com o uso de terminais (telefones) convencionais. Em redes de computadores, foi possível desenvolver em sala [vários pequenos projetos com Micro:bit](https://github.com/boidacarapreta/itl20231/commits/master). E, para o [projeto final](https://github.com/boidacarapreta/itl20231/blob/dev/projeto-da-disciplina.md), foi concebido um sistema baseado no protocolo [MQTT](https://mqtt.org) e [controle remoto](https://github.com/boidacarapreta/itl20231/tree/dev/ITL\_CONTROLE) usando um [aplicativo móvel para celular](https://github.com/boidacarapreta/itl20231/tree/dev/ITL\_Game), aos moldes de uma aplicação IoT regular.

As mudanças se mostraram positivas, e o resultado foi acima do esperado: um bairro controlado por um [jogo para celular](https://ederson-torresini.github.io/itl20231/ITL\_Game/): o personagem caminha pelo bairro, entra em uma casa, acessa o computador da sala e pode controlar remotamente os circuitos elétricos para ativar ou desativá-los via MQTT.
