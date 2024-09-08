## Histórico de Revisão
---
| Data       | Autor         | Descrição                          | Versão |
|------------|---------------|------------------------------------|--------|
| 03/09/2024 | Danilo Naves | Criando seção: Pos-Rastreabilidade | 1.0     |
| 08/09/2024 | Paulo Henrique Melo de Souza | Separação entre Backkward-From e Forward-From e modelagem do documento | 1.1     |

## Introdução

O Backward-From é um artefato essencial no processo de engenharia de requisitos, cujo objetivo é rastrear os requisitos do sistema até as técnicas de elicitação e análise que os originaram. Essa técnica não apenas documenta a origem dos requisitos, mas também oferece uma compreensão mais profunda do contexto e das variáveis que influenciaram seu surgimento. Ao utilizar o Backward-From, é possível identificar as motivações e as necessidades subjacentes que levaram à definição de cada requisito, facilitando a validação e a verificação contínua ao longo do ciclo de vida do projeto. Além disso, essa rastreabilidade aprimora a comunicação entre os stakeholders, garantindo que todos tenham uma visão clara e compartilhada das bases e justificativas para os requisitos estabelecidos.

## Objetivo

O presente documento tem como objetivo apresentar os requisitos do sistema e suas origens, detalhando as técnicas de elicitação e análise que foram utilizadas para identificar e definir esses requisitos. Ao fornecer essa rastreabilidade, o documento busca oferecer uma visão abrangente do processo de desenvolvimento, destacando as motivações e contextos que influenciaram a formulação dos requisitos. Dessa forma, pretende-se facilitar a compreensão e a validação dos requisitos, assegurando que todas as partes interessadas tenham uma visão clara e compartilhada das bases e justificativas para cada requisito estabelecido.

## Requisitos

### Legendas

Para facilitar a leitura e compreensão do leitor, segue abaixo uma pequena lista de legendas utilizadas ao longo do documento:

- **RFnº**: Requisito Funcional
- **RNFnº**: Requisito Não Funcional
- **APnº**: Análise de Protocolo
- **BS**: Brainstorm
- **RPnº**: Rich Picture
- **OBS**: Observação
- **ESPnº**: Especificação NFR

#### Requisitos Funcionais

| ID   | Descrição                                                                                          | Técnicas | Rich Picture  |
|------|----------------------------------------------------------------------------------------------------|--------------------------|-------------------------|
| RF01 | O sistema deve permitir que o usuário marque episódios como assistidos.                            | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)| [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF02 | O sistema deve enviar notificações para o usuário sobre novos episódios de séries que ele segue.   | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF03 | O sistema deve permitir que o usuário adicione novas séries à sua lista de favoritos.              | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF04 | O sistema deve exibir informações detalhadas sobre cada episódio, incluindo sinopse e elenco.      | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF05 | O sistema deve oferecer recomendações de séries com base no histórico de visualização do usuário.  | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF06 | O sistema deve permitir que o usuário dê notas para os episódios assistidos.                       | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF07 | O sistema deve permitir que o usuário registre o tipo de dispositivo em que assistiu ao conteúdo.  | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF08 | O sistema deve permitir que o usuário registre suas reações ao assistir ao conteúdo.               | [AP01](../Elicitacao/analise.md#APD), [OBS](../Elicitacao/observacao.md)  | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF09 | O sistema deve permitir que o usuário informe em qual plataforma ou serviço de streaming assistiu ao conteúdo. | [AP01](../Elicitacao/analise.md#APD)    | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF10 | O sistema deve permitir que o usuário compartilhe suas atividades em redes sociais.                | [AP01](../Elicitacao/analise.md#APD)    | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) | 
| RF11 | O sistema deve permitir que o usuário faça login com redes sociais ou e-mail.                      | [AP01](../Elicitacao/analise.md#APD) | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF12 | O sistema deve oferecer uma seção para comentários e discussões sobre os episódios.                | [AP01](../Elicitacao/analise.md#APD)   | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF13 | O sistema deve sincronizar o progresso do usuário entre diferentes dispositivos.                   | [AP01](../Elicitacao/analise.md#APD)    | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF14 | O usuário deve ser capaz de visualizar seu perfil.                                                 | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)              | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF15 | O sistema deve permitir a visualização de quem segue o usuário.                                    | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                      | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF16 | O sistema deve listar todos os comentários do usuário.                                             | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                      | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF17 | O usuário deve ser capaz de seguir outros usuários.                                                | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                     | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF18 | O sistema deve permitir a filtragem baseada na ordem de relevância dos comentários do usuário.     | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                     | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF19 | O usuário poderá excluir um comentário.                                                            | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                      | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF20 | O sistema deve permitir o compartilhamento de comentários para redes sociais vizinhas.             | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                     | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) |
| RF21 | O sistema deve permitir que o usuário acesse um único comentário em específico.                    | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                      | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF22 | O usuário deve ser capaz de adicionar uma foto de perfil.                                          | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF23 | O usuário deve ser capaz de adicionar uma foto de capa ao perfil.                                  | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF24 | O usuário poderá trocar seu nome de exibição para outros usuários.                                 | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                     | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF25 | O usuário deve ser capaz de editar suas informações pessoais.                                      | [AP03](../Elicitacao/analise.md#APP1), [BS](../Elicitacao/brainstorm.md#BSU)                     | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF26 | O sistema deve computar o tempo gasto do usuário assistindo filmes ou séries.                      | [AP03](../Elicitacao/analise.md#APP1)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF27 | O sistema deve computar a quantidade de episódios vistos pelo usuário.                             | [AP03](../Elicitacao/analise.md#APP1)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF28 | O sistema deve computar a quantidade de filmes vistos pelo usuário.                                | [AP03](../Elicitacao/analise.md#APP1)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF29 | O usuário deve ser capaz de criar novas listas.                                                    | [BS](../Elicitacao/brainstorm.md#BSU)              | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF30 | O usuário deve conseguir adicionar um nome e descrição à nova lista.                               | [BS](../Elicitacao/brainstorm.md#BSU)             | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF31 | O sistema deve permitir que o usuário deixe a lista oculta para outros usuários.                   | [BS](../Elicitacao/brainstorm.md#BSU)             | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF32 | O sistema deve permitir que o usuário adicione filmes ou séries à lista existente.                           | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF33 | O sistema deve permitir que o usuário acesse suas listas existentes.                               | [BS](../Elicitacao/brainstorm.md#BSU)              | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF34 | O sistema deve permitir que o usuário atualize uma lista existente.                                | [BS](../Elicitacao/brainstorm.md#BSU)              | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF35 | O sistema deve permitir que o usuário exclua uma lista.                                            | [BS](../Elicitacao/brainstorm.md#BSU)              | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF36 | O usuário deve ser capaz de acessar suas séries/filmes selecionadas.                              | [AP03](../Elicitacao/analise.md#APP1)    |  [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) | 
| RF37 | O sistema deve permitir que o usuário separe entre séries/filmes vistas e não vistas.              | [AP01](../Elicitacao/analise.md#APD)    | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) | 
| RF38 | O usuário deve ser capaz de localizar filmes/séries por meio de um filtro.                                              | [AP03](../Elicitacao/analise.md#APP1)    | [RP01](../Pre-rastreabilidade/richpicture.md#v2shows) | 
| RF39 | O sistema deve permitir o compartilhamento da lista de séries/filmes favoritos para redes sociais vizinhas. | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF40 | O sistema deve permitir o usuário alterar sua senha de acesso.                                     | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF41 | O usuário poderá vincular/desvincular sua conta a outras redes sociais                             | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF42 | O sistema deve permitir que o usuário torne sua conta privada.                                     | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF43 | O sistema deve permitir que o usuário exclua permanentemente sua conta.                            | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF44 | O usuário deve ser capaz de sair de sua conta.                                                     | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF45 | O sistema deve permitir que o usuário escolha o idioma da exibição dos títulos do filmes/séries.   | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF46 | O sistema deve permitir que o usuário selecione o idioma preferencial para exibição dos comentários, exibindo primeiro os comentários no idioma escolhido.                     | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF47 | O usuário deve ser capaz de escolher entre tema claro ou escuro, com a possibilidade de alternar a qualquer momento. | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF48 | O usuário deve ser capaz de limpar o cache de uso de memória do sistema.                           | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF49 | O sistema deve permitir a filtragem de emissoras.                                                  | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF50 | O usuário deve ser capaz de ocultar episódios já assistidos.                                       | [AP03](../Elicitacao/analise.md#APP1)    | [RP02](../Pre-rastreabilidade/richpicture.md#v2usuario) |
| RF51 | O usuário deve ser capaz de comparar o tempo gasto vendo shows com outros usuários                 | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF52 | O sistema deve mostrar um gráfico contendo o tempo gasto assistindo shows.                         | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF53 | O sistema deve computar as principais emissoras vistas pelo usuário.                               | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF54 | O sistema deve computar os gêneros de shows consumidos pelo usuário.                               | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF55 | O sistema deve listas as conquistas do usuário.                                                    | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF56 | O usuário deve ser capaz de compartilhar suas conquistas para fora do sistema.                     | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF57 | O sistema deve filtrar as conquistas relacionadas à conteúdo visto, avaliações, comentários e seguidores. | [AP04](../Elicitacao/analise.md#APP2)  | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF58 | O sistema só pode se conectar com redes sociais habilitadas no país em questão| [AP04](../Elicitacao/analise.md#APP2)  | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF59 | O sistema deve computar a quantidade de shows adicionados pelo usuário.                            |  [AP04](../Elicitacao/analise.md#APP2)   | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF60 | O sistema deve computar as avaliações do usuário.                                                  | [AP04](../Elicitacao/analise.md#APP2)    | [RP03](../Pre-rastreabilidade/richpicture.md#v1estatisticas) |
| RF61 | O sistema deve permitir que o usuário visualize informações detalhadas sobre um ator ao clicar em seu nome na seção de elenco. | [AP02](../Elicitacao/analise.md#APE)   | -
| RF62 | O sistema deve exibir todos os filmes e séries em que o ator trabalhou na página do ator. |[AP02](../Elicitacao/analise.md#APE)  | -
| RF63 | O sistema deve permitir que o usuário filtre a filmografia do ator em "Séries", "Filmes" ou "Séries e Filmes". |[AP02](../Elicitacao/analise.md#APE)  | - |
| RF64 | O sistema deve permitir que o usuário acesse as redes sociais do ator, assim como o link para sua wikipédia. | [AP02](../Elicitacao/analise.md#APE) | - |

#### Requisitos Não Funcionais

| ID   | Descrição                                                                                          | Origem | 
|------|----------------------------------------------------------------------------------------------------|--------|
| RNF01 | O sistema deve permitir que os usuários configurem suas contas para que certas informações ou atividades sejam privadas, controlando quem pode visualizar ou interagir com esses dados.                       | [NFR2](../Modelagem/NFR/nfr.md#NFR2), [ESP01](../Modelagem/NFR/nfr.md#RNF1)        |
| RNF02 | O sistema deve permitir que usuários de diferentes habilidades realizem login de forma fácil e acessível                        | [NFR1](../Modelagem/NFR/nfr.md#NFR1), [ESP02](../Modelagem/NFR/nfr.md#RNF2)        |
| RNF03 | O sistema deve estar disponível para acesso e uso 24 horas por dia, 7 dias por semana, garantindo que os usuários possam utilizá-lo sem interrupções a qualquer momento.                      | [NFR1](../Modelagem/NFR/nfr.md#NFR1), [ESP03](../Modelagem/NFR/nfr.md#RNF3)        |
| RNF04 | O sistema deve garantir que todos os dados exibidos ou processados estejam sempre atualizados, refletindo as informações mais recentes disponíveis em tempo real ou o mais próximo possível disso.                       | [NFR1](../Modelagem/NFR/nfr.md#NFR1), [ESP04](../Modelagem/NFR/nfr.md#RNF4)        |
| RNF05 | O sistema deve estar disponível e funcional tanto em plataformas de aplicativos móveis (iOS e Android) quanto na web, proporcionando uma experiência consistente e integrada para os usuários em ambas as interfaces.                       | [NFR1](../Modelagem/NFR/nfr.md#NFR1), [ESP05](../Modelagem/NFR/nfr.md#RNF5)        |
| RNF06 | O sistema deve proporcionar uma experiência de usuário intuitiva e agradável, garantindo que os usuários possam navegar, interagir e completar suas tarefas com facilidade e eficiência.                       | [NFR1](../Modelagem/NFR/nfr.md#NFR1), [ESP06](../Modelagem/NFR/nfr.md#RNF6)        |