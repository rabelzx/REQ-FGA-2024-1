## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 21/08/2024 | Eric Rabelo Borges   | Criando seção: Requisitos Elicitados | 1.0 |
| 21/08/2024 | Eric Rabelo Borges   | Formatando links das técnicas de elicitação | 1.1 |
| 01/09/2024 | Paulo Henrique Melo de Souza  | Adicionando RF51 ao RF60 | 1.3 |
| 02/09/2024 | Eric Rabelo Borges  | Adicionando RF61 ao RF63 | 1.4 |
| 02/09/2024 | Eric Rabelo Borges  | Adicionando RF64 | 1.4.1 |
| 04/09/2024 | Wolfgang Friedrich Stein  | Adicionando RF58 | 1.4.2 |

## 1 - Requisitos Funcionais
--- 
| ID   | Descrição                                                                                          | Técnica                 |
|------|----------------------------------------------------------------------------------------------------|-------------------------|
| RF01 | O sistema deve permitir que o usuário marque episódios como assistidos.                            | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)|
| RF02 | O sistema deve enviar notificações para o usuário sobre novos episódios de séries que ele segue.   | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF03 | O sistema deve permitir que o usuário adicione novas séries à sua lista de favoritos.              | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF04 | O sistema deve exibir informações detalhadas sobre cada episódio, incluindo sinopse e elenco.      | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF05 | O sistema deve oferecer recomendações de séries com base no histórico de visualização do usuário.  | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF06 | O sistema deve permitir que o usuário dê notas para os episódios assistidos.                       | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF07 | O sistema deve permitir que o usuário registre o tipo de dispositivo em que assistiu ao conteúdo.  | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)   |
| RF08 | O sistema deve permitir que o usuário registre suas reações ao assistir ao conteúdo.               | [Análise de Protocolo](analise.md#APD) e [Observação](observacao.md)  |
| RF09 | O sistema deve permitir que o usuário informe em qual plataforma ou serviço de streaming assistiu ao conteúdo. | [Análise de Protocolo](analise.md#APD)    |
| RF10 | O sistema deve permitir que o usuário compartilhe suas atividades em redes sociais.                | [Análise de Protocolo](analise.md#APD)    |
| RF11 | O sistema deve permitir que o usuário faça login com redes sociais ou e-mail.                      | [Análise de Protocolo](analise.md#APD)              |
| RF12 | O sistema deve oferecer uma seção para comentários e discussões sobre os episódios.                | [Análise de Protocolo](analise.md#APD)   |
| RF13 | O sistema deve sincronizar o progresso do usuário entre diferentes dispositivos.                   | [Análise de Protocolo](analise.md#APD)    |
| RF14 | O usuário deve ser capaz de visualizar seu perfil.                                                 | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)              |
| RF15 | O sistema deve permitir a visualização de quem segue o usuário.                                    | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF16 | O sistema deve listar todos os comentários do usuário.                                             | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF17 | O usuário deve ser capaz de seguir outros usuários.                                                | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                     |
| RF18 | O sistema deve permitir a filtragem baseada na ordem de relevância dos comentários do usuário.     | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                     |
| RF19 | O usuário poderá excluir um comentário.                                                            | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF20 | O sistema deve permitir o compartilhamento de comentários para redes sociais vizinhas.             | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                     |
| RF21 | O sistema deve permitir que o usuário acesse um único comentário em específico.                    | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF22 | O usuário deve ser capaz de adicionar uma foto de perfil.                                          | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                     |
| RF23 | O usuário deve ser capaz de adicionar uma foto de capa ao perfil.                                  | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                     |
| RF24 | O usuário poderá trocar seu nome de exibição para outros usuários.                                 | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF25 | O usuário deve ser capaz de editar suas informações pessoais.                                      | [Análise de Protocolo](analise.md#APP1) e [Brainstorm](brainstorm.md#BSU)                      |
| RF26 | O sistema deve computar o tempo gasto do usuário assistindo filmes ou séries.                      | [Análise de Protocolo](analise.md#APP1)    |
| RF27 | O sistema deve computar a quantidade de episódios vistos pelo usuário.                             | [Análise de Protocolo](analise.md#APP1)    |
| RF28 | O sistema deve computar a quantidade de filmes vistos pelo usuário.                                | [Análise de Protocolo](analise.md#APP1)    |
| RF29 | O usuário deve ser capaz de criar novas listas.                                                    | [Brainstorm](brainstorm.md#BSU)               |
| RF30 | O usuário deve conseguir adicionar um nome e descrição à nova lista.                               | [Brainstorm](brainstorm.md#BSU)              |
| RF31 | O sistema deve permitir que o usuário deixe a lista oculta para outros usuários.                   | [Brainstorm](brainstorm.md#BSU)              |
| RF32 | O sistema deve permitir que o usuário adicione filmes ou séries à lista existente.                           | [Análise de Protocolo](analise.md#APP1)    |
| RF33 | O sistema deve permitir que o usuário acesse suas listas existentes.                               | [Brainstorm](brainstorm.md#BSU)               |
| RF34 | O sistema deve permitir que o usuário atualize uma lista existente.                                | [Brainstorm](brainstorm.md#BSU)               |
| RF35 | O sistema deve permitir que o usuário exclua uma lista.                                            | [Brainstorm](brainstorm.md#BSU)               |
| RF36 | O usuário deve ser capaz de acessar suas séries/filmes selecionadas.                              | [Análise de Protocolo](analise.md#APP1)    |
| RF37 | O sistema deve permitir que o usuário separe entre séries/filmes vistas e não vistas.              | [Análise de Protocolo](analise.md#APD)    |
| RF38 | O usuário deve ser capaz de localizar filmes/séries por meio de um filtro.                                              | [Análise de Protocolo](analise.md#APP1)    |
| RF39 | O sistema deve permitir o compartilhamento da lista de séries/filmes favoritos para redes sociais vizinhas. | [Análise de Protocolo](analise.md#APP1)    |
| RF40 | O sistema deve permitir o usuário alterar sua senha de acesso.                                     | [Análise de Protocolo](analise.md#APP1)    |
| RF41 | O usuário poderá vincular/desvincular sua conta a outras redes sociais                             | [Análise de Protocolo](analise.md#APP1)    |
| RF42 | O sistema deve permitir que o usuário torne sua conta privada.                                     | [Análise de Protocolo](analise.md#APP1)    |
| RF43 | O sistema deve permitir que o usuário exclua permanentemente sua conta.                            | [Análise de Protocolo](analise.md#APP1)    |
| RF44 | O usuário deve ser capaz de sair de sua conta.                                                     | [Análise de Protocolo](analise.md#APP1)    |
| RF45 | O sistema deve permitir que o usuário escolha o idioma da exibição dos títulos do filmes/séries.   | [Análise de Protocolo](analise.md#APP1)    |
| RF46 | O sistema deve permitir que o usuário selecione o idioma preferencial para exibição dos comentários, exibindo primeiro os comentários no idioma escolhido.                     | [Análise de Protocolo](analise.md#APP1)    |
| RF47 | O usuário deve ser capaz de escolher entre tema claro ou escuro, com a possibilidade de alternar a qualquer momento. | [Análise de Protocolo](analise.md#APP1)    |
| RF48 | O usuário deve ser capaz de limpar o cache de uso de memória do sistema.                           | [Análise de Protocolo](analise.md#APP1)    |
| RF49 | O sistema deve permitir a filtragem de emissoras.                                                  | [Análise de Protocolo](analise.md#APP1)    |
| RF50 | O usuário deve ser capaz de ocultar episódios já assistidos.                                       | [Análise de Protocolo](analise.md#APP1)    |
| RF51 | O usuário deve ser capaz de comparar o tempo gasto vendo shows com outros usuários                 | [Análise de Protocolo](analise.md#APP2)    |
| RF52 | O sistema deve mostrar um gráfico contendo o tempo gasto assistindo shows.                         | [Análise de Protocolo](analise.md#APP2)    |
| RF53 | O sistema deve computar as principais emissoras vistas pelo usuário.                               | [Análise de Protocolo](analise.md#APP2)    |
| RF54 | O sistema deve computar os gêneros de shows consumidos pelo usuário.                               | [Análise de Protocolo](analise.md#APP2)    |
| RF55 | O sistema deve listas as conquistas do usuário.                                                    | [Análise de Protocolo](analise.md#APP2)    |
| RF56 | O usuário deve ser capaz de compartilhar suas conquistas para fora do sistema.                     | [Análise de Protocolo](analise.md#APP2)    |
| RF57 | O sistema deve filtrar as conquistas relacionadas à conteúdo visto, avaliações, comentários e seguidores. | [Análise de Protocolo](analise.md#APP2)  |
| RF58 | O sistema só pode se conectar com redes sociais habilitadas no país em questão| [Análise de Protocolo](analise.md#APP2)  |
| RF59 | O sistema deve computar a quantidade de shows adicionados pelo usuário.                            |  [Análise de Protocolo](analise.md#APP2)   |
| RF60 | O sistema deve computar as avaliações do usuário.                                                  | [Análise de Protocolo](analise.md#APP2)    |
| RF61 | O sistema deve permitir que o usuário visualize informações detalhadas sobre um ator ao clicar em seu nome na seção de elenco. | [Análise de Protocolo](analise.md#APE)  |
| RF62 | O sistema deve exibir todos os filmes e séries em que o ator trabalhou na página do ator. |[Análise de Protocolo](analise.md#APE) |
| RF63 | O sistema deve permitir que o usuário filtre a filmografia do ator em "Séries", "Filmes" ou "Séries e Filmes". |[Análise de Protocolo](analise.md#APE) |
| RF64 | O sistema deve permitir que o usuário acesse as redes sociais do ator, assim como o link para sua wikipédia. | [Análise de Protocolo](analise.md#APE)|

## 2 - Requisitos Não Funcionais
---
Os requisitos não funcionais foram elicitados utilizando o NFR Framework que pode ser acessado [aqui](../Modelagem/NFR/nfr.md#RNFs).