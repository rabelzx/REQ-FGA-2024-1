## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 13/08/2024 |  Eric Rabelo, Paulo Henrique  | Criação do documento e inserção do CEN01 até o CEN14 | 1.0 |
| 13/08/2024 |  Eric Rabelo  | Linkando léxico do usário nos cenários | 1.1 |
| 14/08/2024 |  Paulo Henrique  | inserção do CEN15 ao CEN19 | 1.2 |

## Introdução
--- 
Cenários são descrições detalhadas de situações específicas em que os usuários interagem com um sistema. Eles representam casos de uso realistas que mostram como o sistema deve funcionar em diferentes contextos e sob diversas condições. 

## Objetivo
---
Os cenários têm como objetivo ilustrar de forma clara e detalhada como os usuários interagem com o sistema em situações específicas. Eles descrevem passo a passo as ações realizadas pelo usuário ao executar tarefas, como navegar por uma série ou avaliar um episódio, por exemplo.

## Metodologia
---
O grupo se reuniu para produzir os cenários baseados nos requisitos até então elicitados. Durante o processo, foram realizadas sessões de brainstorming para identificar os principais fluxos de interação dos usuários com o sistema. Cada cenário foi desenvolvido com o objetivo de representar situações reais que os usuários possam enfrentar ao utilizar a aplicação.

## Cenários
---
- [CEN01 - Primeiro acesso](#cen01)
- [CEN02 - Marcar um episódio como assistido](#cen02)
- [CEN03 - Notificar o usuário sobre novos episódios](#cen03)
- [CEN04 - Favoritar série](#cen04)
- [CEN05 - Avaliar episódio](#cen05)
- [CEN06 - Plataforma utilizada](#cen06)
- [CEN07 - Reação do usuário](#cen07)
- [CEN08 - Comentar conteúdo](#cen08)
- [CEN09 - Compartilhar perfil](#cen09)
- [CEN10 - Escolher foto/capa de perfil](#cen10)
- [CEN11 - Criar listas](#cen11)
- [CEN12 - Editar lista](#cen12)
- [CEN13 - Excluir lista](#cen13)
- [CEN14 - Compartilhar lista](#cen14)
- [CEN15 - Ocultar conteúdo assistido](#cen15)
- [CEN16 - Localizar conteúdo](#cen16)
- [CEN17 - Alterar senha](#cen17)
- [CEN18 - Vincular/Desvincular redes sociais](#cen18)
- [CEN19 - Privar conta](#cen19)

---

<a name="cen01"></a>

### Primeiro acesso

|   **Título**   | Primeiro acesso                                                          |
| :------------: | -------------------------------------------------------------------------------------------------------------------- |
|  **Objetivo**  | Realizar o primeiro acesso na aplicação.                                 |
|  **Contexto**  | Possuir acesso ao Tv Time.                                               |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                                           |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) abre o aplicativo do Tv Time pela primeira vez. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em cadastrar-se/fazer login. <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere sua data de nascimento. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona seu gênero. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em continuar. <br> 6. O [usuário](../Lexico/lexico.md#usuario) seleciona séries para adicionar à lista de séries. <br> 7. O [usuário](../Lexico/lexico.md#usuario) seleciona filmes já vistos para adicionar à lista de filmes. <br> 8. O [usuário](../Lexico/lexico.md#usuario) seleciona filmes que quer assistir.                         |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) já possui conta na aplicação. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.                                |
| **Requisitos** | | 

<a name="cen02"></a>

### Marcar um episódio como assistido

|   **Título**   | Marcar um episódio como assistido                        |
| :------------: | -------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) marcar um ou mais episódios como já assistido. |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado e acessa a aba de séries.          |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                           |
| **Episódios**  | 1. [Usuário](../Lexico/lexico.md#usuario) navega até a aba de séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma série da lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio. <br> 4. O [usuário](../Lexico/lexico.md#usuario) marca o episódio como assistido.            |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) deve estar logado. <br> Ter séries pré-selecionadas na aba.                      |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) fecha o aplicativo durante a ação.             |
| **Requisitos** | | 

<a name="cen03"></a>

### Notificar o [usuário](../Lexico/lexico.md#usuario) sobre novos episódios 

|   **Título**   | Notificar o [usuário](../Lexico/lexico.md#usuario) sobre novos episódios                          |
| :------------: | ------------------------------------------------------------------ |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) ser notificado sobre um novo episódio da série na lista. |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) segue uma ou mais séries.                                |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario), Sistema                                                   |
|  **Recursos**  | Acesso à internet, smartphone                                      |
| **Episódios**  | 1. Um novo episódio da lista de séries é lançado. <br> 2. O sistema envia uma notificação para o smartphone do [usuário](../Lexico/lexico.md#usuario). <br> 3. O [usuário](../Lexico/lexico.md#usuario) recebe a notificação.                                 |
| **Restrições** | A conta do [usuário](../Lexico/lexico.md#usuario) estar conectada no sistema. <br> Possuir séries na lista. <br> O [usuário](../Lexico/lexico.md#usuario) permitir o envio de notificações.                        |
|  **Exceções**  | Não ter conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) desativou o envio de notificações.                       |
| **Requisitos** | |

<a name="cen04"></a>

### Favoritar série
|   **Título**   | Favoritar série                                                |
| :------------: | -------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) adicionar uma série aos favoritos.                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                         |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                 |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona para adicionar uma série aos favoritos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona uma série marcando o ícone de coração.  |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) possuir séries na lista.                             |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) sai do aplicativo durante a ação.                    |
| **Requisitos** | | 

<a name="cen05"></a>

### Avaliar episódio
|   **Título**   | Avaliar episódio                                                               |
| :------------: | ------------------------------------------------------------------------------ |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) dar uma nota ao episódio de uma série.                               |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                         |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                                 |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma série. <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio da série. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona o ícone de check para marcar o episódio como assistido. <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona um dos ícones de estrela para avaliar. |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) possuir séries na lista. <br> O [usuário](../Lexico/lexico.md#usuario) ter visto o episódio.           |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) sai do aplicativo durante a ação. <br> O [usuário](../Lexico/lexico.md#usuario) não ter assistido o episódio. | 
| **Requisitos** | | 

<a name="cen06"></a>

### Plataforma utilizada 
|   **Título**   | Plataforma utilizada                                                          |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar a plataforma que assistiu o conteúdo.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma série da lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca a série como assistida. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a plataforma na qual viu a série. <br> **Caminho B:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona um filme da lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca o filme como assistido. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a plataforma na qual viu o filme. |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) não ter filmes ou séries na lista. |
| **Requisitos** | |

<a name="cen07"></a>

### Reação do usuário 
|   **Título**   | Reação do usuário                                                              |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar sua reação.                                               |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) seleciona um conteúdo. <br> 2. O [usuário](../Lexico/lexico.md#usuario) marca qual sua reação acerca do conteúdo. |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.   |
| **Requisitos** | | 

<a name="cen08"></a>

### Comentar conteúdo
|   **Título**   | Comentar conteúdo                                                             |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) fazer o comentário em um conteúdo da aplicação.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de séries.<br>**Caminho A1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica no título da série.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica no comentário geral da série.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>4. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre a série.<br>5. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica na imagem da série.<br>2. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio da série.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no comentário do episódio.<br>5. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>6. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre o episódio da série.<br>7. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes vistos.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em comentários.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em "já vi este filme".<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>5. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre o filme.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em publicar. |
|  **Exceções**  | O [usuário](../Lexico/lexico.md#usuario) não possuir filmes ou séries na lista. <br> Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O aplicativo deixa de funcionar. |
| **Requisitos** | | 

<a name="cen09"></a>

### Compartilhar perfil
|   **Título**   | Compartilhar perfil                                                           |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar seu perfil                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | |

<a name="cen10"></a>

### Escolher foto/capa de perfil
|   **Título**   | Escolher foto/capa de perfil                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) inserir/editar sua foto/capa de perfil                              |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em editar.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em escolher foto/capa de perfil.<br>4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma foto da galeria do dispositivo. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>O [usuário](../Lexico/lexico.md#usuario) não permite que o sistema acesse a galeria do dispositivo. |
| **Requisitos** | | 

<a name="cen11"></a>

### Criar listas
|   **Título**   | Criar listas                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) criar uma lista de filmes/séries.                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em "criar uma nova lista".<br>3. O [usuário](../Lexico/lexico.md#usuario) insere um nome para a lista.<br>4. Se quiser, insere uma descrição.<br>5. Se quiser, pode tornar a lista opcional.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em "criar lista". |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>A lista já existir. |
| **Requisitos** | | 

<a name="cen12"></a>

### Editar lista
|   **Título**   | Editar lista                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) editar uma lista.                                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em editar detalhes. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | | 

<a name="cen13"></a>

### Excluir lista
|   **Título**   | Excluir lista                                                                 |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) excluir uma lista.                                                  |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em excluir. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | | 

<a name="cen14"></a>

### Compartilhar lista
|   **Título**   | Compartilhar lista                                                            |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar uma lista.                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar.<br>5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | |

<a name="cen15"></a>

### Ocultar conteúdo assistido 
|   **Titulo**   | Ocultar conteúdo assistido                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) ocultar os conteúdos já assistidos.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes ou séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona sua lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> Ter filmes/séries na lista geral que já foram vistos. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.                             |
| **Requisitos** |                              |

<a name="cen16"></a>

### Localizar conteúdo 
|   **Titulo**   | Localizar conteúdo                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) buscar por um filme ou série.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de descobrir. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em "Pesquisar séries e filmes". <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere o nome de um filme ou série. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona o filme ou série pesquisado.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.     |
| **Requisitos** |                              |

<a name="cen17"></a>

### Alterar senha
|   **Titulo**   | Alterar senha                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) alterar sua senha de acesso.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em alterar senha. <br> 5. O [usuário](../Lexico/lexico.md#usuario) insere a senha atual, a nova senha e confirma a nova senha.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui conta.                             |
| **Requisitos** |                              |

<a name="cen18"></a>

### Vincular/Desvincular redes sociais   
|   **Titulo**   | Vincular/Desvincular redes sociais                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) vincular/desvincular suas redes sociais no aplicativo.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em "Editar contas vinculadas". <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma ou mais redes para vincular/desvincular.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui rede social.                             |
| **Requisitos** |                              |

<a name="cen19"></a>

### Privar conta
|   **Titulo**   | Privar conta                              |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) tornar sua conta privada.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona "definir perfil como privado".                          |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.                            |