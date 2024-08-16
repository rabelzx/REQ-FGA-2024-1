## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 13/08/2024 |  Eric Rabelo, Paulo Henrique  | Criação do documento e inserção do CEN01 até o CEN14 | 1.0 |
| 13/08/2024 |  Eric Rabelo  | Linkando léxico do usário nos cenários | 1.1 |
| 14/08/2024 |  Paulo Henrique  | Inserção do CEN15 ao CEN19 | 1.2 |
| 14/08/2024 |  Sunamita Vitória  | Inserção do CEN20 ao CEN25 | 1.3 |

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
- [CEN20 - Sair da conta](#cen20)
- [CEN21 - Traduzir títulos de séries/filmes](#cen21)
- [CEN22 - Priorizar idioma dos comentários](#cen22)
- [CEN23 - Tema claro/escuro](#cen23)
- [CEN24 - Limpar memória](#cen24)
- [CEN25 - Filtrar emissoras](#cen25)

---

### Primeiro acesso {#cen01}
|   **Título**   | Primeiro acesso                                                          |
| :------------: | -------------------------------------------------------------------------------------------------------------------- |
|  **Objetivo**  | Realizar o primeiro acesso na aplicação.                                 |
|  **Contexto**  | Possuir acesso ao Tv Time.                                               |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                                           |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) abre o aplicativo do Tv Time pela primeira vez. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em cadastrar-se/fazer login. <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere sua data de nascimento. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona seu gênero. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em continuar. <br> 6. O [usuário](../Lexico/lexico.md#usuario) seleciona séries para adicionar à lista de séries. <br> 7. O [usuário](../Lexico/lexico.md#usuario) seleciona filmes já vistos para adicionar à lista de filmes. <br> 8. O [usuário](../Lexico/lexico.md#usuario) seleciona filmes que quer assistir.                         |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) já possui conta na aplicação. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.                                |
| **Requisitos** | | 

### Marcar um episódio como assistido {#cen02}
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

### Notificar o [usuário](../Lexico/lexico.md#usuario) sobre novos episódios {#cen03} 
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

### Favoritar série {#cen04}
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

### Avaliar episódio {#cen05}
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

### Plataforma utilizada {#cen06}
|   **Título**   | Plataforma utilizada                                                          |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar a plataforma que assistiu o conteúdo.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma série da lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca a série como assistida. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a plataforma na qual viu a série. <br> **Caminho B:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona um filme da lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca o filme como assistido. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a plataforma na qual viu o filme. |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) não ter filmes ou séries na lista. |
| **Requisitos** | |

### Reação do usuário {#cen07}
|   **Título**   | Reação do usuário                                                              |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar sua reação.                                               |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) seleciona um conteúdo. <br> 2. O [usuário](../Lexico/lexico.md#usuario) marca qual sua reação acerca do conteúdo. |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.   |
| **Requisitos** | | 

### Comentar conteúdo {#cen08}
|   **Título**   | Comentar conteúdo                                                             |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) fazer o comentário em um conteúdo da aplicação.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de séries.<br>**Caminho A1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica no título da série.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica no comentário geral da série.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>4. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre a série.<br>5. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica na imagem da série.<br>2. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio da série.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no comentário do episódio.<br>5. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>6. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre o episódio da série.<br>7. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes vistos.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em comentários.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em "já vi este filme".<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>5. O [usuário](../Lexico/lexico.md#usuario) deixa um comentário sobre o filme.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em publicar. |
|  **Exceções**  | O [usuário](../Lexico/lexico.md#usuario) não possuir filmes ou séries na lista. <br> Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O aplicativo deixa de funcionar. |
| **Requisitos** | | 

### Compartilhar perfil {#cen09}
|   **Título**   | Compartilhar perfil                                                           |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar seu perfil                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | |

### Escolher foto/capa de perfil {#cen10}
|   **Título**   | Escolher foto/capa de perfil                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) inserir/editar sua foto/capa de perfil                              |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em editar.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em escolher foto/capa de perfil.<br>4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma foto da galeria do dispositivo. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>O [usuário](../Lexico/lexico.md#usuario) não permite que o sistema acesse a galeria do dispositivo. |
| **Requisitos** | | 

### Criar listas {#cen11}
|   **Título**   | Criar listas                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) criar uma lista de filmes/séries.                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em "criar uma nova lista".<br>3. O [usuário](../Lexico/lexico.md#usuario) insere um nome para a lista.<br>4. Se quiser, insere uma descrição.<br>5. Se quiser, pode tornar a lista opcional.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em "criar lista". |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>A lista já existir. |
| **Requisitos** | |

### Editar lista {#cen12}
|   **Título**   | Editar lista                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) editar uma lista.                                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em editar detalhes. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | | 

### Excluir lista {#cen13}
|   **Título**   | Excluir lista                                                                 |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) excluir uma lista.                                                  |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em excluir. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | | 

### Compartilhar lista {#cen14}
|   **Título**   | Compartilhar lista                                                            |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar uma lista.                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma lista existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar.<br>5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |
| **Requisitos** | |

### Ocultar conteúdo assistido {#cen15}
|   **Titulo**   | Ocultar conteúdo assistido                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) ocultar os conteúdos já assistidos.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de filmes ou séries. <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona sua lista. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> Ter filmes/séries na lista geral que já foram vistos. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.                             |
| **Requisitos** |                              |

### Localizar conteúdo {#cen16}
|   **Titulo**   | Localizar conteúdo                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) buscar por um filme ou série.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de descobrir. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em "Pesquisar séries e filmes". <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere o nome de um filme ou série. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona o filme ou série pesquisado.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.     |
| **Requisitos** |                              |

### Alterar senha {#cen17}
|   **Titulo**   | Alterar senha                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) alterar sua senha de acesso.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em alterar senha. <br> 5. O [usuário](../Lexico/lexico.md#usuario) insere a senha atual, a nova senha e confirma a nova senha.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui conta.                             |
| **Requisitos** |                              |

### Vincular/Desvincular redes sociais {#cen18}   
|   **Titulo**   | Vincular/Desvincular redes sociais                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) vincular/desvincular suas redes sociais no aplicativo.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em "Editar contas vinculadas". <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma ou mais redes para vincular/desvincular.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui rede social.                             |
| **Requisitos** |                              |

### Privar conta {#cen19}
|   **Titulo**   | Privar conta                              |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) tornar sua conta privada.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até aba de perfil. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona "definir perfil como privado".                          |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.|

### Sair da conta {#cen20}  
|   **Titulo**   | Sair da conta                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário sair da conta.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário clica em sair.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado.                             |

### Traduzir títulos de séries/filmes {#cen21}
|   **Titulo**   | Traduzir títulos de séries/filmes                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário traduzir os títulos das séries/filmes.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário navega até app. <br> 6. O usuário clica em "Exibir no seu idioma".                                |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado.   |

### Priorizar idioma dos comentários {#cen22} 
|   **Titulo**   | Priorizar idioma dos comentários.                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário selecionar os comentários de determinado idioma.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário navega até app. <br> 5. O usuário clica em "selecionar os idiomas dos comentários". <br> 6. O usuário seleciona um ou mais idiomas.                              |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado. |

### Tema claro/escuro {#cen23}   
|   **Titulo**   | Tema claro/escuro                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário trocar o tema.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário navega até app. <br> 5. O usuário seleciona o tema.                            |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado. |

### Limpar memória {#cen24}  
|   **Titulo**   | Limpar memória                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário limpar o cache de memória do sistema.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário navega até app. <br> 5. O usuário clica em "limpar cache".  |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado.                             |

### Filtrar emissoras {#cen25} 
|   **Titulo**   | Filtrar emissoras                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O usuário filtrar emissoras.                             |
|  **Contexto**  | O usuário está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O usuário navega até perfil. <br> 2. O usuário clica no ícone de três pontos. <br> 3. O usuário clica em configurações. <br> 4. O usuário navega até em breve. <br> 5. O usuário clica em filtrar emissoras.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O usuário interrompe o fluxo de execução. <br> O usuário não está logado. |