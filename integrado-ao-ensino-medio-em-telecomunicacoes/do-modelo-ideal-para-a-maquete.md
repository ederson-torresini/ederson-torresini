---
description: Texto compartilhado entre docentes e alunos no início das aulas.
---

# Do modelo ideal para a maquete

## Metodologia baseada em projeto

Na disciplina de Introdução às Telecomunicações, é usada a metodologia baseada em projeto. Essa metodologia prevê um produto final, a ser desenvolvido ao longo de todo o semestre com entregas parciais regulares.

## O projeto

O projeto escolhido pelo corpo docente é a maquete de uma cidade para o entendimento, sob um ponto de vista histórico, das telecomunicações, em especial os sistemas telefônicos e de redes de computadores. Cada maquete é uma placa de madeira de aproximadamente 1 x 1 m, e corresponde a um bairro da cidade do projeto, a ser mantida por uma subprefeitura. Os bairros, ao longo da disciplina, devem estabelecer conectividade com os outros bairros, formando uma cidade única no final.

### Fonte de recurso

Uma possível fonte de recurso de curto a médio prazo é a venda de lotes residenciais nos bairros da cidade. Com isso, será possível viabilizar a maquete nos meses iniciais, pois se trata de um investimento na planta.

### Requisitos

Dentre os requisitos funcionais básicos, há:

* **Mobilidade**: a cidade deve ser projetada para atender satisfatoriamente a mobilidade urbana.
* **Acessibilidade**: o projeto e implementação da cidade deve contemplar os princípios de acessibilidade urbana.
* **Sustentabilidade**: as fontes de energia devem ser limpas e renováveis.

Referências

* Vídeos: [Canal da disciplina no YouTube](https://www.youtube.com/watch?v=quI-zGehZEM\&list=PLje9mMro7hT2vbYqvnxwJM6f3ktvskNCu\&index=1).
* Notícias:
  * [Estrutura gigante em forma de anel é proposta para cercar o Burj Khalifa de Dubai](https://www.archdaily.com.br/br/987946/estrutura-gigante-em-forma-de-anel-e-proposta-para-cercar-o-burj-khalifa-de-dubai).

## A equipe

A subprefeitura é composta por:

* **Subprefeito**: o gestor (cada aluno assumirá o papel por um mês).
* **Comunicador**: responsável pela produção textual e audiovisual a ser apresentado ao corpo docente e comunidade em geral.
* **Arquiteto**: define o projeto arquitetônico do bairro e ligação com os outros da cidade. Engenheiro: constrói e implanta sistemas de telecomunicações.
* **Pedreiro**: constrói e implanta vias públicas e construções públicas e privadas.

Cada aluno pode assumir um ou mais papéis. A única exceção é o subprefeito: a cada mês um aluno assumirá esse papel, e será o ponto de comunicação com o corpo docente.

## O progresso

São usadas algumas ferramentas para acompanhar o progresso do projeto. No cerne, o _kanban_. Cada equipe tem uma cartolina com 3 colunas:

* **A Fazer**: todas as tarefas necessárias para a entrega do produto final.
* **Fazendo**: as tarefas em desenvolvimento.
* **Feito**: as tarefas já concluídas e validadas pelo corpo docente.

As tarefas, lembrando, são atômicas: devem ter início, meio e fim claro e com duração curta - para ser concluída em tempo hábil uma vez iniciada.

### Temática mensal

Para melhor compreensão do projeto como um todo, a cada mês é adotada uma temática, de forma que o projeto se desenvolva progressivamente. As entregas mensais são sempre duas:&#x20;

1. **Relatório de progresso**: a ser entregue ao corpo docente para avaliação técnica
2. **Produto audiovisual**: preferencialmente vídeo, a ser disponibilizado à comunidade acadêmica.

#### Mês 1, energia elétrica

Definição das equipes e construção da maquete com suporte a energia elétrica pública (iluminação pública) e privada (residências), além de suas várias matrizes (térmica, eólica etc.).

Conceitos envolvidos:

* Mensagem.
* Codificação.

Experimentos:

* Interruptor físico para acionamento da iluminação pública.
* Usina eólica com manivela.
* Comunicação Morse com lanterna (aplicativos para celular).

Para auxiliar no entendimento:

* Aplicativos e jogos: TheoTown, SimCity, Cities: Skylines (pago), Minecraft (pago), Go.
* Livros: Filmes: documentários sobre corrente alternada e contínua.
* Visitas técnicas: sites das operadoras de telefonia móvel.

#### Mês 2, telefonia, analógico

Uso da infraestrutura estabelecida no mês 1 para incorporar um sistema telefônico para comunicação por mensagem (Morse, telegrama etc.) e voz.

Conceitos envolvidos:

* Sinal.
* Modulação.
* Harmônicas.
* Filtros.

Experimentos:

* Comunicação Morse com circuitos elétricos para controle remoto da iluminação pública com Arduino NodeMCU e/ou comunicação entre os bairros da cidade.

Para auxiliar no entendimento:

* Aplicativos e jogos: Laser Overload (1, 2).
* Livros: livros de época.

#### Mês 3, redes de computadores, digital

Uso do sistema telefônico para implantação do sistema de redes de computadores.

Conceitos envolvidos:

* Números binários.
* Encapsulamento da informação em pacotes.
* Multiplexação.

Experimentos:

* Programação com Arduino (NodeMCU) para controle da iluminação pública com sensores (de luminosidade) e atuadores.
* Complementar ao experimento anterior, o uso de AP + Arduino NodeMCU + Raspberry Pi para controle remoto da iluminação pública usando MQTT.
* O ideal, para finalizar, é usar controle remoto de videogame, mais especificamente um XBox Controller com USB para mapear os botões com operações de controle da cidade, cada vez mais inteligente. Ou seja, a mesa de operações da cidade é o controle do videogame.
* Sistema de redes de computadores entre os bairros para troca de mensagens ASCII sobre a pilha TCP/IP.

Para auxiliar no entendimento:

* Aplicativos e jogos: 2048, LightBot, Sudoku, Code.org.
* Filmes: série do Manual do Mundo sobre o computador, Matrix.
* Músicas: disco Blade Runner (Vangelis).
* Visitas técnicas: prestadoras de serviço de hospedagem em nuvem.

#### Mês 4, futuro

Projeções para os próximos 4 anos na área de telecomunicações.&#x20;

Conceitos envolvidos:

* Internet das Coisas.
* Inteligência artificial.
* _Blockchain_.

Experimentos:

* Usar o XBox Controller para expandir as funcionalidades.
* Adicionar central telefônica IP (Asterisk) para adicionar controle remoto usando URA e DTMF traduzido para comandos via MQTT.
* Agricultura 4.0 em hortas comunitárias.
* Sistemas de transmissão sem fio (satélite, móvel etc.).

Para auxiliar no entendimento:

* Aplicativos e jogos: IFTTT, TerraGenesis.
* Filmes: subgênero _solarpunk_.
* Visitas técnicas: parques de empresas de tecnologia, como incubadoras e aceleradoras.

### Entregas parciais

O projeto é desenvolvido em ciclos. A cada duas semanas, é feita uma reunião de planejamento, onde é acordada a entrega parcial: quais tarefas devem ser realizadas e o que deve estar pronto ao final desse período, quando há uma reunião de avaliação para validar as tarefas realizadas e entregues.

#### Entrega 1

* Montagem da equipe.
* Canais de comunicação com a comunidade.
* Peça publicitária: promessas de campanha (política).
* Base e fundações do bairro.
* Vias públicas.

#### Entrega 2

* Espaço físico para sistema de energia elétrica: subestação e transmissão.
* Subestação de energia elétrica.
* Iluminação pública e privada.

#### Entrega 3

* Espaço físico para sistema de telefonia: operadora e transmissão.
* Comunicação entre bairros com telegrafia.

#### Entrega 4

* Implantação da operadora de telefonia. Produção dos terminais telefônicos públicos (orelhão) e/ou residenciais.

#### Entrega 5

* Espaço físico para provedor de Internet.
* Automação por microcontroladores (sensores e atuadores e rede IP).

#### Entrega 6

* Serviços de conectividade por microcomputadores.
* Serviço Web: consumo de recursos.

#### Entrega 7

* Conectividade: livre para a equipe decidir (sugestão: satélites, telefonia móvel).

#### Entrega 8

* Serviços: livre para a equipe decidir (sugestão: Internet das Coisas, 5G, IA etc.)
