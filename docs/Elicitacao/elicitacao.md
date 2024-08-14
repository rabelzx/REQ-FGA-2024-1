## Histórico de Revisão

| Versão | Alteração | Responsável | Revisor | Data |
|--------|-----------|-------------|---------|------|
| 1.0 | Criando aba - Elicitação | Danilo Naves do Nascimento, Paulo Henrique Melo de Souza | - | 30/07 |
| 1.1 | Adição dos tópicos 1 ao 6 | Paulo Henrique Melo de Souza | - | 31/07 |
| 1.2 | Adição do tópico 5.1.1 e 5.1.2 | Paulo Henrique Melo de Souza | - | 01/08 |
| 2.0 | Adição dos requisitos elicitados | Eric Rabelo Borges | - | 10/08 |

## 1 - Introdução
---
Elicitação é o processo de coleta de informações sobre o sistema a ser desenvolvido. A elicitação de requisitos é uma das atividades mais importantes do processo de Engenharia de Requisitos, pois é nela que se obtém informações sobre o que o sistema deve fazer, como ele deve se comportar e quais são as restrições que ele deve obedecer.

## 2 - Objetivo
---
O objetivo deste documento é apresentar as técnicas de elicitação de requisitos que serão utilizadas no projeto, bem como suas definições e artefatos gerados. 

## 3 - Geral
---
Durante as reuniões dos dias [23/07](../Atas/reuniao_23_07.md) e [25/07](../Atas/reuniao_25_07.md), foi discutido, de modo externo, os possíveis interessados e suas necessidades para qual tenham com o aplicativo. A partir disso, utilizando a técnica de brainstorming, foi possível identificar os possíveis interessados e gerar como artefato o [RichPicture Geral - versão 1.0](../Pre-rastreabilidade/richpicture.md#v1geral) e [RichPicture Geral - versão 2.0](../Pre-rastreabilidade/richpicture.md#v2geral).

## 4 - Filmes / Séries
---
### 4.1 - Técnicas

#### 4.1.1 - Observação Participativa
Utilizando a técnica de observação, foi feita uma breve análise da aba relacionada a séries do aplicativo, com o intuito de identificar suas possíveis funcionalidades, na qual a análise foi documentada em [Observação Shows](../documentacao/observacaoShows.md). A partir dessa análise foi possível identificar pontos positivos, dificuldades e sugestões para a aba de séries e gerar como artefato a primeira versão do [RichPicture Shows - versão 1.0](../Pre-rastreabilidade/richpicture.md#v1shows).

#### 4.1.2 - Análise de protocolo
Para reforçar possíveis pontos de melhoria e identificar novas funcionalidades, foram feitas duas análises de protocolo, na qual na reunião do dia [29/07](../Atas/reuniao_29_07.md) o membro Danilo Naves fez a análise de protocolo da aba de filmes e a Sunamita Vitoria fez da aba de séries.

Segue abaixo a análise de protocolo feita pelo Danilo Naves:
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/-PtVC4qcJpo" frameborder="0" allowfullscreen></iframe>
</center>

Análise de protocolo feita pela Sunamita Vitoria:
<center>
<audio controls>
  <source src="../audio/analiseProtocoloSeries.mp3" type="audio/mp3">
  Seu navegador não suporta o elemento de áudio.
</audio>
</center>

A partir dessas análises, percebeu-se que a aba de séries e filmes são basicamente iguais, com a diferença de que a aba de séries possui um campo dedicado aos episódios e temporadas. Com isso, a equipe entrou em consenso de unificar os rich pictures de filmes e séries, gerando como artefato uma nova versão para o rich picture de shows, chamada: [RichPicture Shows - versão 2.0](../Pre-rastreabilidade/richpicture.md#v2shows).

## 5 - Usuário
---
### 5.1 - Técnicas

#### 5.1.1 - Brainstorming
Durante a reunião do dia [30/07](../Atas/reuniao_30_07.md), os membros Paulo Henrique e Danilo Naves fizeram um brainstorming da aba de perfil de usuário do aplicativo com o objetivo de extrair possíveis funcionalidades e necessidades dos usuários. A partir disso, foi gerado o [RichPicture Usuário - versão 1.0](../Pre-rastreabilidade/richpicture.md#v1usuario).

#### 5.1.2 - Análise de Protocolo
Com o objetivo de reforçar possíveis pontos de melhoria e levantar novos requisitos, foi passada a tarefa de fazer a análise de protocolo na aba de configurações do perfil de usuário. O objetivo da tarefa era acessar as configurações e trocar o tema de claro para escuro, mostrando todos os passos realizados e explicando o que foi feito. A análise foi feita pelo membro Paulo Henrique. Segue abaixo o vídeo da análise de protocolo:

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZCHwscVyR6E?si=0Fd2ZefGvImdKBnp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

Feita a análise de protocolo e brainstorming, foi gerada uma nova versão para o rich picture de usuário, chamada: [RichPicture Usuário - versão 2.0](../Pre-rastreabilidade/richpicture.md#v2usuario).

## 6 - Requisitos Elicitados {#reqElicitados}

A partir das técnicas de elicitação utilizadas, foram elicitados os seguintes requisitos:

| ID   | Descrição                                                                                          | Técnica                 |
|------|----------------------------------------------------------------------------------------------------|-------------------------|
| RF01 | O sistema deve permitir que o usuário marque episódios como assistidos.                            | Análise de Protocolo e Observação   |
| RF02 | O sistema deve enviar notificações para o usuário sobre novos episódios de séries que ele segue.   | Análise de Protocolo e Observação   |
| RF03 | O sistema deve permitir que o usuário adicione novas séries à sua lista de favoritos.              | Análise de Protocolo e Observação   |
| RF04 | O sistema deve exibir informações detalhadas sobre cada episódio, incluindo sinopse e elenco.      | Análise de Protocolo e Observação   |
| RF05 | O sistema deve oferecer recomendações de séries com base no histórico de visualização do usuário.  | Análise de Protocolo e Observação   |
| RF06 | O sistema deve permitir que o usuário dê notas para os episódios assistidos.                       | Análise de Protocolo e Observação   |
| RF07 | O sistema deve permitir que o usuário registre o tipo de dispositivo em que assistiu ao conteúdo.  | Análise de Protocolo e Observação   |
| RF08 | O sistema deve permitir que o usuário registre suas reações ao assistir ao conteúdo.               | Análise de Protocolo e Observação  |
| RF09 | O sistema deve permitir que o usuário informe em qual plataforma ou serviço de streaming assistiu ao conteúdo. | Análise de Protocolo    |
| RF10 | O sistema deve permitir que o usuário compartilhe suas atividades em redes sociais.                | Análise de Protocolo    |
| RF11 | O sistema deve permitir que o usuário faça login com redes sociais ou e-mail.                      | Brainstorm              |
| RF12 | O sistema deve oferecer uma seção para comentários e discussões sobre os episódios.                | Análise de Protocolo    |
| RF13 | O sistema deve sincronizar o progresso do usuário entre diferentes dispositivos.                   | Análise de Protocolo    |
| RF14 | O usuário deve ser capaz de visualizar seu perfil.                                                 | Brainstorm              |
| RF15 | O sistema deve permitir a visualização de quem segue o usuário.                                    | Brainstorm              |
| RF16 | O sistema deve listar todos os comentários do usuário.                                             | Brainstorm              |
| RF17 | O usuário deve ser capaz de seguir outros usuários.                                                | Brainstorm              |
| RF18 | O sistema deve permitir a filtragem baseada na ordem de relevância dos comentários do usuário.     | Brainstorm              |
| RF19 | O usuário poderá excluir um comentário.                                                            | Brainstorm              |
| RF20 | O sistema deve permitir o compartilhamento de comentários para redes sociais vizinhas.             | Brainstorm              |
| RF21 | O sistema deve permitir que o usuário acesse um único comentário em específico.                    | Brainstorm              |
| RF22 | O usuário deve ser capaz de adicionar uma foto de perfil.                                          | Brainstorm              |
| RF23 | O usuário deve ser capaz de adicionar uma foto de capa ao perfil.                                  | Brainstorm              |
| RF24 | O usuário poderá trocar seu nome de exibição para outros usuários.                                 | Brainstorm              |
| RF25 | O usuário deve ser capaz de editar suas informações pessoais.                                      | Brainstorm              |
| RNF26 | O sistema deve computar o tempo gasto do usuário assistindo filmes ou séries.                      | Análise de Protocolo    |
| RNF27 | O sistema deve computar a quantidade de episódios vistos pelo usuário.                             | Análise de Protocolo    |
| RNF28 | O sistema deve computar a quantidade de filmes vistos pelo usuário.                                | Análise de Protocolo    |
| RF29 | O usuário deve ser capaz de criar novas listas.                                                    | Brainstorm              |
| RF30 | O usuário deve conseguir adicionar um nome e descrição à nova lista.                               | Brainstorm              |
| RF31 | O sistema deve permitir que o usuário deixe a lista oculta para outros usuários.                   | Brainstorm              |
| RF32 | O sistema deve permitir que o usuário adicione filmes ou séries à lista existente.                           | Análise de Protocolo    |
| RF33 | O sistema deve permitir que o usuário acesse suas listas existentes.                               | Brainstorm              |
| RF34 | O sistema deve permitir que o usuário atualize uma lista existente.                                | Brainstorm              |
| RF35 | O sistema deve permitir que o usuário exclua uma lista.                                            | Brainstorm              |
| RF36 | O usuário deve ser capaz de acessar suas séries/filmes selecionadas.                              | Análise de Protocolo    |
| RF37 | O sistema deve permitir que o usuário separe entre séries/filmes vistas e não vistas.              | Análise de Protocolo    |
| RF38 | O usuário deve ser capaz de localizar filmes/séries por meio de um filtro.                                              | Análise de Protocolo    |
| RF39 | O sistema deve permitir o compartilhamento da lista de séries/filmes favoritos para redes sociais vizinhas. | Análise de Protocolo    |
| RF40 | O sistema deve permitir o usuário alterar sua senha de acesso.                                     | Análise de Protocolo    |
| RF41 | O usuário poderá vincular/desvincular sua conta a outras redes sociais                             | Análise de Protocolo    |
| RF42 | O sistema deve permitir que o usuário torne sua conta privada.                                     | Análise de Protocolo    |
| RNF43 | O sistema deve permitir que o usuário exclua permanentemente sua conta.                            | Análise de Protocolo    |
| RNF44 | O usuário deve ser capaz de sair de sua conta.                                                     | Análise de Protocolo    |
| RNF45 | O sistema deve permitir que o usuário escolha o idioma da exibição dos títulos do filmes/séries.   | Análise de Protocolo    |
| RNF46 | O sistema deve permitir que o usuário selecione o idioma preferencial para exibição dos comentários, exibindo primeiro os comentários no idioma escolhido.                     | Análise de Protocolo    |
| RNF47 | O usuário deve ser capaz de escolher entre tema claro ou escuro, com a possibilidade de alternar a qualquer momento. | Análise de Protocolo    |
| RNF48 | O usuário deve ser capaz de limpar o cache de uso de memória do sistema.                           | Análise de Protocolo    |
| RNF49 | O sistema deve permitir a filtragem de emissoras.                                                  | Análise de Protocolo    |
| RF50 | O usuário deve ser capaz de ocultar episódios já assistidos.                                       | Análise de Protocolo    |
