Contexto

O atual projeto busca criar um pipeline de dados para, através de um chatbot fazer a extração, tratamento e análise de dados de uma conversa no Telegram.

Todos os prints das configurações tanto do Telegram, como nas plataformas AWS estão salvos neste [link](https://github.com/joaolucascv/pipeline-img.git) do Github.

- Chatbot
Um chatbot é um tipo de software que interage com usuários através de conversas automatizadas em plataformas de mensagens. Uma aplicação comum de chatbots é o seu uso no atendimento ao cliente, onde, de maneira geral, ajudam clientes a resolver problemas ou esclarecer dúvidas recorrentes antes mesmo que um atendente humano seja acionado.

- Telegram
Telegram é uma plataforma de mensagens instantâneas freeware (distribuído gratuitamente) e, em sua maioria, open source. É muito popular entre desenvolvedores por ser pioneiro na implantação da funcionalidade de criação de chatbots, que, por sua vez, permitem a criação de diversas automações.

- Objetivo
Nesse projeto vamos criar um grupo no telegram e enviar mensagens para teste durante 3 dias. A captação dos dados via chatbot será feita diariamente. Ao final dessa atividade, vamos para a parte analítica. O objetivo do projeto é responder as seguintes perguntas:

      - Quantas mensagens cada usuário mandou por dia?
      - Qual a média do tamanho das mensagens enviadas por usuário por dia?
      - Qual a quantidade de mensagens por hora por dia da semana por número da semana?

Portanto, vamos construir um pipeline de dados que ingira, processe, armazene e exponha mensagens de um grupo do Telegram para que profissionais de dados possam realizar análises. A arquitetura proposta é dividida em duas: transacional, no Telegram, onde os dados são produzidos, e analítica, na Amazon Web Services (AWS), onde os dados são analisados.

![](https://github.com/joaolucascv/pipeline-img/blob/main/img%20projeto%20final.png?raw=true)
