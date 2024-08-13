# Cenários

## Objetivo
---
Cenários são descrições detalhadas de situações específicas em que os usuários interagem com um sistema. Eles representam casos de uso realistas que mostram como o sistema deve funcionar em diferentes contextos e sob diversas condições. Os cenários têm como objetivo ilustrar de forma clara e detalhada como os usuários interagem com o sistema em situações específicas. Eles descrevem passo a passo as ações realizadas pelo usuário ao executar tarefas, como navegar por uma série ou avaliar um episódio, por exemplo.

---
##Cenário 001 - Primeiro acesso##
|   **Titulo**   | Primeiro acesso                                                          |
| :------------: | ------------------------------------------------------------------------ |
|  **Objetivo**  | Realizar o primeiro acesso na aplicação.                                 |
|  **Contexto**  | Possuir acesso ao Tv Time.                                               |
|   **Atores**   | Usuário.                                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                                           |
| **Episódios**  | 1. O usuário abre o aplicativo do Tv Time pela primeira vez. <br> 2. O usuário clica em cadastrar-se/fazer login. <br> 3. O usuário insere sua data de nascimento. <br> 4. O usuário seleciona seu gênero. <br> 5. O usuário clica em continuar. <br> 6. O usuário seleciona séries para adicionar à lista séries. <br> 7. O usuário seleciona filmes já visto para adicionar à lista de filmes. <br> 8. O usuário seleciona filmes que quer assistir.                         |
|  **Exceções**  | A internet deixa de funcionar. <br> O usuário já possui conta na aplicação. <br> O usuário interrompe o fluxo de execução.                                |

##Cenário 002 - Marcar um episódio como assistido##
|   **Titulo**   | Marcar um episódio como assistido                        |
| :------------: | -------------------------------------------------------- |
|  **Objetivo**  | O usuário marcar um ou mais episódios como já assistido. |
|  **Contexto**  | O usuário está logado e acessa a aba de séries.          |
|   **Atores**   | Usuário.                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                           |
| **Episódios**  | 1. Usuário navega até a aba de séries. <br> 2. O usuário seleciona uma série da lista. <br> 3. O usuário seleciona um episódio. <br> 4. O usuário marca o episódio como assistido.            |
| **Restrições** | O usuário deve estar logado. <br> Ter séries pré-selecionadas na aba.                      |
|  **Exceções**  | A internet deixa de funcionar. <br> O usuário fecha o aplicativo durante a ação.             |

##Cenário 003 - Notificar o usuário sobre novos episódios ##
|   **Titulo**   | Notificar o usuário sobre novos episódios                          |
| :------------: | ------------------------------------------------------------------ |
|  **Objetivo**  | O usuário ser notificado sobre um novo episódio da série na lista. |
|  **Contexto**  | O usuário segue uma ou mais séries.                                |
|   **Atores**   | Usuário, Sistema                                                   |
|  **Recursos**  | Acesso à internet, smartphone                                      |
| **Episódios**  | 1. Um novo episódio da lista de séries é lançado. <br> 2. O sistema envia uma notificação para o smartphone do usuário. <br> 3. O usuário recebe a notificação.                                 |
| **Restrições** | A conta do usuário estar conectada no sistema. <br> Possuir séries na lista. <br> O usuário permitir o envio de notificações.                        |
|  **Exceções**  | Não ter conexão com a internet. <br> O usuário desativou o envio de notificações.                       |

##Cenário 004 - Favoritar série ##
|   **Titulo**   | Favoritar série                                                |
| :------------: | -------------------------------------------------------------- |
|  **Objetivo**  | O usuário adicionar uma série aos favoritos.                   |
|  **Contexto**  | O usuário está logado.                                         |
|   **Atores**   | Usuário.                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                 |
| **Episódios**  | 1. O usuário navega até a aba de perfil. <br> 2. O usuário seleciona para adicionar uma série aos favoritos. <br> 3. O usuário seleciona uma série marcando o ícone de coração.  |
| **Restrições** | O usuário possuir séries na lista.                             |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O usuário sai do aplicativo durante a ação.                    |

##Cenário 005 - Avaliar episódio ##
|   **Título**   | Avaliar episódio                                                               |
| :------------: | ------------------------------------------------------------------------------ |
|  **Objetivo**  | O usuário dar uma nota ao episódio de uma série.                               |
|  **Contexto**  | O usuário está logado.                                                         |
|   **Atores**   | Usuário.                                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                                 |
| **Episódios**  | 1. O usuário navega até a aba de séries.<br>2. O usuário seleciona uma série.<br>3. O usuário seleciona um episódio da série.<br>4. O usuário seleciona o ícone de check para marcar o episódio como assistido.<br>5. O usuário seleciona um dos ícones de estrela para avaliar. |
| **Restrições** | O usuário possuir séries na lista.<br>O usuário ter visto o episódio.           |
|  **Exceções**  | A internet deixa de funcionar.<br>O aplicativo deixa de funcionar.<br>O usuário sai do aplicativo durante a ação.<br>O usuário não ter assistido o episódio. | 

##Cenário 006 - Plataforma utilizada  ##
|   **Título**   | Plataforma utilizada                                                          |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário registrar a plataforma que assistiu o conteúdo.                     |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:**<br>1. O usuário navega até a aba de séries.<br>2. O usuário seleciona uma série da lista.<br>3. O usuário marca a série como assistida.<br>4. O usuário registra a plataforma na qual viu a série.<br>**Caminho B:**<br>1. O usuário navega até a aba de filmes.<br>2. O usuário seleciona um filme da lista.<br>3. O usuário marca o filme como assistido.<br>4. O usuário registra a plataforma na qual viu o filme. |
|  **Exceções**  | A internet deixa de funcionar.<br>O aplicativo deixa de funcionar.<br>O usuário não ter filmes ou séries na lista. |

##Cenário 007 - Reação do usuário ##
|   **Título**   | Reação do usuário                                                              |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário registrar sua reação.                                               |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O usuário seleciona um conteúdo.<br>2. O usuário marca qual sua reação acerca do conteúdo. |
|  **Exceções**  | A internet deixa de funcionar.<br>O usuário interrompe o fluxo de execução.   |

##Cenário 008 - Comentar conteúdo ##
|   **Título**   | Comentar conteúdo                                                             |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário fazer o comentário em um conteúdo da aplicação.                     |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:**<br>1. O usuário navega até a aba de séries.<br>**Caminho A1:**<br>1. O usuário clica no título da série.<br>2. O usuário clica no comentário geral da série.<br>3. O usuário clica no ícone do lápis.<br>4. O usuário deixa um comentário sobre a série.<br>5. O usuário clica em publicar.<br>**Caminho B1:**<br>1. O usuário clica na imagem da série.<br>2. O usuário seleciona um episódio da série.<br>3. O usuário clica no ícone de task.<br>4. O usuário clica no comentário do episódio.<br>5. O usuário clica no ícone do lápis.<br>6. O usuário deixa um comentário sobre o episódio da série.<br>7. O usuário clica em publicar.<br>**Caminho B:**<br>1. O usuário navega até a aba de filmes vistos.<br>2. O usuário clica em comentários.<br>3. O usuário clica em "já vi este filme".<br>4. O usuário clica no ícone do lápis.<br>5. O usuário deixa um comentário sobre o filme.<br>6. O usuário clica em publicar. |
|  **Exceções**  | O usuário não possuir filmes ou séries na lista.<br>Perda de conexão com a internet.<br>O usuário interrompe o fluxo de execução.<br>O aplicativo deixa de funcionar. |

##Cenário 009 - Compartilhar perfil ##
|   **Título**   | Compartilhar perfil                                                           |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário compartilhar seu perfil                                             |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica no ícone de três pontos.<br>3. O usuário clica em compartilhar.<br>4. O usuário seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução. |

##Cenário 010 - Escolher foto/capa de perfil ##
|   **Título**   | Escolher foto/capa de perfil                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário inserir/editar sua foto/capa de perfil                              |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica em editar.<br>3. O usuário clica em escolher foto/capa de perfil.<br>4. O usuário seleciona uma foto da galeria do dispositivo. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução.<br>O usuário não permite que o sistema acesse a galeria do dispositivo. |

##Cenário 011 - Criar listas ##
|   **Título**   | Criar listas                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário criar uma lista de filmes/séries.                                   |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica em "criar uma nova lista".<br>3. O usuário insere um nome a lista.<br>4. Se quiser, insere uma descrição.<br>5. Se quiser, pode tornar a lista opcional.<br>6. O usuário clica em "criar lista". |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução.<br>A lista já existir. |

##Cenário 012 - Editar lista ##
|   **Título**   | Editar lista                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário editar uma lista.                                                   |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica em uma lista existente.<br>3. O usuário clica no ícone de três pontos.<br>4. O usuário clica em editar detalhes. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução. |

##Cenário 013 - Excluir lista ##
|   **Título**   | Excluir lista                                                                 |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário excluir uma lista.                                                  |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica em uma lista existente.<br>3. O usuário clica no ícone de três pontos.<br>4. O usuário clica em excluir. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução. |

##Cenário 014 - Compartilhar lista ##
|   **Título**   | Compartilhar lista                                                            |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O usuário compartilhar uma lista.                                             |
|  **Contexto**  | O usuário está logado.                                                        |
|   **Atores**   | Usuário.                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, lista existente.                               |
| **Episódios**  | 1. O usuário navega até a aba de perfil.<br>2. O usuário clica em uma lista existente.<br>3. O usuário clica no ícone de três pontos.<br>4. O usuário clica em compartilhar.<br>5. O usuário seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O usuário interrompe o fluxo de execução. |


|   **Titulo**   |                              |
| :------------: | ---------------------------- |
|  **Objetivo**  |                              |
|  **Contexto**  |                              |
|   **Atores**   |                              |
|  **Recursos**  |                              |
| **Episódios**  |                              |
|  **Exceções**  |                              |