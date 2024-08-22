## Histórico de Revisão
--- 
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 20/08      |Danilo Naves   | Criação do documento referente a Especificações de  Casos de Uso | 1.0|
| 21/08      |Wolfgang Stein  | Adicionando [UC01](#uc01---criação-de-conta) e [UC02](#uc02---adicionando-filmes) | 1.1|
| 21/08      |Wolfgang Stein  | Adicionando [UC03](#uc03---adicionando-séries), [UC04](#uc04---avaliando-filmes), [UC05]()| 1.1|

### Sumário


### 1.Introdução

Esse documento visa especificar os casos de uso do TV time.

### 2. Objetivo

Objetivo é representar o comportamento de usuários do Tv time a fim de levantar requisitos para a modelagem


### Especificação de Casos de Uso
---
UC01 - Criação de conta
---

|           |               |
|-----------|---------------|
| Descrição | Criação de conta |
| Ator(es)  | Usuário, Sistema de login externo | 
| Pré-Requisitos | Possuir uma conta no Apple, Facebook, Google ou X|
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O aplicativo apresenta uma tela de login <br>3. O usuário decide em qual conta externa usará para login<br> 4. O usuário decide se quer receber atualizações do app por caixa de email <br> 5. Usuário é automaticamente redirecionado para tela de novos usuários |
| Fluxo Alternativo 1 |1. O usuário já tinha uma conta no aplicativo <br> 2. O usuário entra em sua conta já existente <br> 3. Usuário é redirecionado para a tela principal do aplicativo |
| Fluxo de Exceção | -- |
| Pós-Condições | O usuário agora possui uma conta no aplicativo |

UC02 - Adicionando Filmes
---

|           |               |
|-----------|---------------|
| Descrição | Adicionando Filmes |
| Ator(es)  | Usuário, Produtoras, Serviços de Streaming| 
| Pré-Requisitos | Possuir cadastro no Tv time e estar conectado a internet|
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O usuário vai até o botão de Descobrir<br>3. O usuário clica na barra de "Ver todos os filmes"[FA01]<br> 4. O usuário pode procurar o filme [FA02][FA03]<br> 5. O usuário clica em adicionar filme ( botão de '+') [FA04]|
| Fluxo Alternativo 1 |1. O usuário acessa a barra de pesquisar ( canto superior) <br> 2. O usuário digita o nome do filme <br> 3. Usuário adiciona o Filme clicando no botão ("+")|
| Fluxo Alternativo 2 |1. O usuário usa pode navegar na página para ver os filmes que estão sendo apresentados <br> 2. Adiciona o filme apertando o botão de adicionar filme(+) <br>|
| Fluxo Alternativo 3 |1. O usuário aperta o botão "filtros" <br> 2. Escolhe a opção de filtros <br> 3. clica no botão ("+") para adicionar o filme<br>|
| Fluxo Alternativo 4 |1. O usuário clica na barra do filme <br> 2. Clica no botão adicionar filme ("+") ou  no check <br>|
| Fluxo de Exceção | -- |
| Pós-Condições | O usuário agora adicionou esse filme a sua lista de Filmes assistidos. |


UC03 - Adicionando Séries
---

|           |               |
|-----------|---------------|
| Descrição | Adicionando Series |
| Ator(es)  | Usuário, Produtoras, Serviços de Streaming| 
| Pré-Requisitos | Possuir cadastro no Tv time e estar conectado a internet|
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O usuário vai até o botão de Descobrir<br>3. O usuário clica na barra de "Ver todas as séries"[FA01]<br> 4. O usuário pode procurar o Série [FA02][FA03]<br> 5. O usuário clica em adicionar Série ( botão de '+') [FA04]|
| Fluxo Alternativo 1 |1. O usuário acessa a barra de pesquisar ( canto superior) <br> 2. O usuário digita o nome da Série <br> 3. Usuário adiciona a série clicando no botão ("+")|
| Fluxo Alternativo 2 |1. O usuário usa pode navegar na página para ver as séries que estão sendo apresentados <br> 2. Adiciona o Série apertando o botão de adicionar Série(+) <br>|
| Fluxo Alternativo 3 |1. O usuário aperta o botão "filtros" <br> 2. Escolhe a opção de filtros <br> 3. clica no botão ("+") para adicionar a série<br>|
| Fluxo Alternativo 4 |1. O usuário clica na barra do Série <br> 2. Clica no botão adicionar Série ("+") ou  no check <br>|
| Fluxo de Exceção | -- |
| Pós-Condições | O usuário agora adicionou essa série a sua lista de Filmes assistidos. |

UC04 - Avaliando Filmes
---

|           |               |
|-----------|---------------|
| Descrição | Avalia os Filmes, fala de onde assistiu, onde assistiu, como se sentiu e por fim qual seu ator favorito|
| Ator(es)  | Usuário, Produtoras, Serviços de Streaming| 
| Pré-Requisitos | Possuir cadastro no Tv time e estar conectado a internet|
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O usuário vai até o botão de Perfil[FA01]<br>3. O usuário clica no icone ">" para ver seus filmes <br> 4. Seleciona o filme que deseja avaliar<br> 5. O usuário coloca onde assistiu, avalia o filme, como se sentiu e qual o seu personagem favorito.|
| Fluxo Alternativo 1 |1. O usuário acessa a barra de descobrir<br> 2. O usuário acessa a barra de pesquisar ( canto superior)  <br> 3. O usuário procura o filme que já tenha na sua lista [FE01]<br> 4. O usuário clica na aba "mais" no qual tem as mesmas opções do fluxo principal|
| Fluxo de Exceção | Caso não esteja como assistido, não é possivel avaliar|
| Pós-Condições | O usuário agora avaliou o Filme |

UC05 - Avaliando Séries
---

|           |               |
|-----------|---------------|
| Descrição | Avalia as séries, fala de onde assistiu, onde assistiu, como se sentiu e por fim qual seu ator favorito|
| Ator(es)  | Usuário, Produtoras, Serviços de Streaming| 
| Pré-Requisitos | Possuir cadastro no Tv time e estar conectado a internet|
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O usuário vai até o botão de Perfil[FA01]<br>3. O usuário clica no icone ">" para ver suas séries <br> 4. Seleciona a série que deseja avaliar<br>5. Seleciona o episódio que quer avaliar <br> 6. O usuário coloca onde assistiu, avalia a śerie, como se sentiu e qual o seu personagem favorito.|
| Fluxo Alternativo 1 |1. O usuário acessa a barra de descobrir<br> 2. O usuário acessa a barra de pesquisar ( canto superior)  <br> 3. O usuário procura a série que já tenha na sua lista [FE01]<br> 4. O usuário clica na aba "mais" no qual tem as mesmas opções do fluxo principal|
| Fluxo de Exceção | Caso não esteja como assistido, não é possivel avaliar|
| Pós-Condições | O usuário agora avaliou a série |