## Histórico de Revisão
--- 
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 20/08      |Danilo Naves   | Criação do documento referente a Especificações de  Casos de Uso | 1.0|

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
| Fluxo Principal | 1. Usuário acessa TV Time <br>2. O usuário vai até o botão de Descobrir<br>3. O usuário clica na barra de "Ver todos os filmes"[FA01]<br> 4. O usuário pode procurar o filme [FA02]<br> 5. O usuário clica em adicionar filme ( botão de '+') [FA03]|
| Fluxo Alternativo 1 |1. O usuário acessa a barra de pesquisar ( canto superior) <br> 2. O usuário digita o nome do filme <br> 3. Usuário adiciona o Filme clicando no botão ("+")|
| Fluxo Alternativo 2 |1. O usuário usa pode navegar na página para ver os filmes que estão sendo apresentados <br> 2. Adiciona o filme apertando o botão de adicionar filme(+) <br>|
| Fluxo Alternativo 3 |1. O usuário clica na barra do filme <br> 2. Clica no botão adicionar filme ("+") ou  no check <br>|
| Fluxo de Exceção | -- |
| Pós-Condições | O usuário agora adicionou esse filme a sua lista de Filmes assistidos. |

