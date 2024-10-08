## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 14/08/2024 | Paulo Henrique  | Criação do documento e inserção dos tópicos 1 ao 4.4 | 1.0 |
| 20/08/2024 | Paulo Henrique  | Revisão do documento e correção de erros | 1.1 |
| 02/09/2024 | Eric Rabelo Borges  | Adição dos requisitor RF61 ao RF64 na priorização | 1.2 |
| 04/09/2024 | Wolfgang Stein  | Adição dos requisitor RF51 ao RF60 na priorização | 1.2 |

## 1 - Introdução
---
Priorização é o processo de classificar as necessidades, requisitos ou funcionalidades de um produto ou projeto de acordo com sua importância e valor para o cliente ou para o negócio. A priorização é essencial para garantir que os recursos disponíveis sejam alocados de forma eficiente e que as entregas atendam às expectativas dos stakeholders.

## 2 - Objetivo
---
Este documento tem como objetivo apresentar os critérios e métodos de priorização utilizados para definir a ordem de implementação dos requisitos do projeto.

## 3 - Metodogia
---
Na reunião do dia [13/08](../Atas/reuniao_13_08.md), por meio da técnica de brainstorming, cada membro da equipe argumentou sobre a prioridade de cada requisito elicitado. A partir disso, foi possível definir a ordem de priorização dos requisitos definida a seguir.

## 4 - MoSCoW
---
A técnica MoSCoW é uma abordagem de priorização de requisitos que classifica os requisitos em quatro categorias:

- **Must have (Deve ter):** Requisitos essenciais para o sucesso do projeto. Se um requisito for classificado como "Must have" e não for implementado, o projeto será considerado um fracasso.
- **Should have (Deveria ter):** Requisitos importantes, mas não essenciais. Se um requisito for classificado como "Should have" e não for implementado, o projeto ainda poderá ser considerado um sucesso.
- **Could have (Poderia ter):** Requisitos desejáveis, mas não críticos. Se um requisito for classificado como "Could have" e não for implementado, o projeto não será afetado.
- **Won't/Would have (Não terá):** Requisitos que não serão implementados na versão atual do projeto, mas podem ser considerados em futuras iterações.

Por meio desta técnica e respeitando a ordem de prioridade do MoSCoW, os [requisitos elicitados](../Elicitacao/elicitacao.md#reqElicitados) receberam a seguinte classificação de priorização:

### **4.1 - Must Have (Deve ter)**
| ID   | Descrição                                                                                                      | 
|------|----------------------------------------------------------------------------------------------------------------|
| RF01 | O sistema deve permitir que o usuário marque episódios como assistidos.                                        | 
| RF09 | O sistema deve permitir que o usuário informe em qual plataforma ou serviço de streaming assistiu ao conteúdo. | 
| RF11 | O sistema deve permitir que o usuário faça login com redes sociais ou e-mail.                                  | 
| RF13 | O sistema deve sincronizar o progresso do usuário entre diferentes dispositivos.                               | 
| RF14 | O usuário deve ser capaz de visualizar seu perfil.                                                             | 
| RF36 | O usuário deve ser capaz de acessar suas séries/filmes selecionadas.                                           | 
| RF37 | O sistema deve permitir que o usuário separe entre séries/filmes vistas e não vistas.                          | 
| RF38 | O usuário deve ser capaz de localizar filmes/séries por meio de um filtro.                                     | 
| RF40 | O sistema deve permitir o usuário alterar sua senha de acesso.                                                 |  
| RF43 | O sistema deve permitir que o usuário exclua permanentemente sua conta.                                       | 
| RF44 | O usuário deve ser capaz de sair de sua conta.                                                                | 
| RF45 | O sistema deve permitir que o usuário escolha o idioma da exibição dos títulos do filmes/séries.              | 
| RF59 | O sistema deve computar a quantidade de shows adicionados pelo usuário.              | 
| RF60 | O sistema deve computar as avaliações do usuário.              | 

### **4.2 - Should Have (Deveria ter)**
| ID   | Descrição                                                                                             | 
|------|-------------------------------------------------------------------------------------------------------|
| RF02 | O sistema deve enviar notificações para o usuário sobre novos episódios de séries que ele segue.      | 
| RF05 | O sistema deve oferecer recomendações de séries com base no histórico de visualização do usuário.     | 
| RF26 | O sistema deve computar o tempo gasto do usuário assistindo filmes ou séries.                        | 
| RF27 | O sistema deve computar a quantidade de episódios vistos pelo usuário.                               | 
| RF28 | O sistema deve computar a quantidade de filmes vistos pelo usuário.                                  | 
| RF29 | O usuário deve ser capaz de criar novas listas.                                                       | 
| RF30 | O usuário deve conseguir adicionar um nome e descrição à nova lista.                                  | 
| RF32 | O sistema deve permitir que o usuário adicione filmes ou séries à lista existente.                    | 
| RF33 | O sistema deve permitir que o usuário acesse suas listas existentes.                                  | 
| RF34 | O sistema deve permitir que o usuário atualize uma lista existente.                                   |   
| RF35 | O sistema deve permitir que o usuário exclua uma lista.                                               |
| RF41 | O usuário poderá vincular/desvincular sua conta a outras redes sociais                                |
| RF42 | O sistema deve permitir que o usuário torne sua conta privada.                                        | 
| RF46 | O sistema deve permitir que o usuário selecione o idioma preferencial para exibição dos comentários. | 
| RF50 | O usuário deve ser capaz de ocultar episódios já assistidos.                                          | 
| RF53 |   O sistema deve computar as principais emissoras vistas pelo usuário.                                        | 
| RF54 |   O sistema deve computar os gêneros de shows consumidos pelo usuário.	                                        | 
| RF58 | O sistema só pode se conectar com redes sociais habilitadas no país em questão                                              |

### **4.3 - Could Have (Poderia ter)**
| ID   | Descrição                                                                                                             |
|------|-----------------------------------------------------------------------------------------------------------------------|
| RF03 | O sistema deve permitir que o usuário adicione novas séries à sua lista de favoritos.                                 |
| RF04 | O sistema deve exibir informações detalhadas sobre cada episódio, incluindo sinopse e elenco.                         |
| RF06 | O sistema deve permitir que o usuário dê notas para os episódios assistidos.                                          |
| RF07 | O sistema deve permitir que o usuário registre o tipo de dispositivo em que assistiu ao conteúdo.                     |
| RF08 | O sistema deve permitir que o usuário registre suas reações ao assistir ao conteúdo.                                  |
| RF10 | O sistema deve permitir que o usuário compartilhe suas atividades em redes sociais.                                   |
| RF12 | O sistema deve oferecer uma seção para comentários e discussões sobre os episódios.                                   |
| RF15 | O sistema deve permitir a visualização de quem segue o usuário.                                                       |
| RF16 | O sistema deve listar todos os comentários do usuário.                                                                |
| RF17 | O usuário deve ser capaz de seguir outros usuários.                                                                   |
| RF18 | O sistema deve permitir a filtragem baseada na ordem de relevância dos comentários do usuário.                        |
| RF19 | O usuário poderá excluir um comentário.                                                                               |
| RF20 | O sistema deve permitir o compartilhamento de comentários para redes sociais vizinhas.                                |
| RF21 | O sistema deve permitir que o usuário acesse um único comentário em específico.                                       |
| RF22 | O usuário deve ser capaz de adicionar uma foto de perfil.                                                             |
| RF23 | O usuário deve ser capaz de adicionar uma foto de capa ao perfil.                                                     |
| RF24 | O usuário poderá trocar seu nome de exibição para outros usuários.                                                    |
| RF31 | O sistema deve permitir que o usuário deixe a lista oculta para outros usuários.                                      |
| RF39 | O sistema deve permitir o compartilhamento da lista de séries/filmes favoritos para redes sociais vizinhas.           |
| RF47 | O usuário deve ser capaz de escolher entre tema claro ou escuro, com a possibilidade de alternar a qualquer momento.  |
| RF48 | O usuário deve ser capaz de limpar o cache de uso de memória do sistema.                                              |
| RF51 |O usuário deve ser capaz de comparar o tempo gasto vendo shows com outros usuários	                                   |
| RF52 |  O sistema deve mostrar um gráfico contendo o tempo gasto assistindo shows.                                           |
| RF55 |O sistema deve listar as conquistas do usuário.		                                                                   |
| RF56 |O usuário deve ser capaz de compartilhar suas conquistas para fora do sistema.                                         |
| RF57 |O sistema deve filtrar as conquistas relacionadas à conteúdo visto, avaliações, comentários e seguidores.    
| RF61 | O sistema deve permitir que o usuário visualize informações detalhadas sobre um ator ao clicar em seu nome na seção de elenco. |
| RF62 | O sistema deve exibir todos os filmes e séries em que o ator trabalhou na página do ator. |
| RF63 | O sistema deve permitir que o usuário filtre a filmografia do ator em "Séries", "Filmes" ou "Séries e Filmes". |
| RF64 | O sistema deve permitir que o usuário acesse as redes sociais do ator, assim como o link para sua wikipédia. |
                                      |


### **4.4 - Would Have (Teria)**
| ID   | Descrição                                                                                          |
|------|----------------------------------------------------------------------------------------------------|
| RF25 | O usuário deve ser capaz de editar suas informações pessoais.                                      | 
| RF49 | O sistema deve permitir a filtragem de emissoras.                                                 |



