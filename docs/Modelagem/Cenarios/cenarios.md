## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 13/08/2024 |  Eric Rabelo, Paulo Henrique  | Criação do documento e inserção do CEN01 até o CEN14 | 1.0 |
| 13/08/2024 |  Eric Rabelo  | Linkando léxico do usário nos cenários | 1.1 |
| 14/08/2024 |  Paulo Henrique  | Inserção do CEN15 ao CEN19 | 1.2 |
| 14/08/2024 |  Sunamita Vitória  | Inserção do CEN20 ao CEN25 | 1.3 |
| 19/08/2024 |  Paulo Henrique  | Linkando léxicos aos cenários | 1.5 |
| 09/09/2024 |  Paulo Henrique  | Inserção do CEN26 ao CEN39 | 1.6 |

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
- [CEN26 - Comparar tempo gasto](#cen26)
- [CEN27 - Visualizar gráfico de tempo gasto vendo filmes/séries](#cen27)
- [CEN28 - Visualizar principais emissoras de séries](#cen28)
- [CEN29 - Visualizar principais gêneros de filmes/séries](#cen29)
- [CEN30 - Acessar emblemas](#cen30)
- [CEN31 - Compartilhar emblemas](#cen31)
- [CEN32 - Visualizar total de séries adicionadas](#cen32)
- [CEN33 - Visualizar total de avaliações feitas](#cen33)
- [CEN34 - Visualizar informações sobre um ator](#cen34)
- [CEN35 - Visualizar filmes e séries trabalhados por um ator](#cen35)
- [CEN36 - Filtrar filmografia de um ator](#cen36)
- [CEN37 - Acessar as redes sociais de um ator](#cen37)
- [CEN38 - Visualizar total de seguidores e comentários](#cen38)
- [CEN39 - Visualizar quem segue o usuário](#cen39)

---

### Primeiro acesso {#cen01}
|   **Título**   | Primeiro acesso                                                          |
| :------------: | -------------------------------------------------------------------------------------------------------------------- |
|  **Objetivo**  | Realizar o primeiro acesso na aplicação.                                 |
|  **Contexto**  | Possuir acesso ao Tv Time.                                               |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                                           |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) abre o aplicativo do Tv Time pela primeira vez. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em cadastrar-se/fazer login. <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere sua data de nascimento. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona seu gênero. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em continuar. <br> 6. O [usuário](../Lexico/lexico.md#usuario) seleciona [séries](../Lexico/lexico.md#serie) para adicionar à [lista](../Lexico/lexico.md#lista-geral) de [séries](../Lexico/lexico.md#serie). <br> 7. O [usuário](../Lexico/lexico.md#usuario) seleciona [filmes](../Lexico/lexico.md#filme) já vistos para adicionar à [lista](../Lexico/lexico.md#lista-geral) de [filmes](../Lexico/lexico.md#filme). <br> 8. O [usuário](../Lexico/lexico.md#usuario) seleciona [filmes](../Lexico/lexico.md#filme) que quer assistir.                         |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) já possui conta na aplicação. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.                                |

### Marcar um episódio como assistido {#cen02}
|   **Título**   | Marcar um episódio como assistido                        |
| :------------: | -------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) marcar um ou mais episódios como já assistido. |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado e acessa a aba de [séries](../Lexico/lexico.md#serie).          |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                 |
|  **Recursos**  | Acesso à internet, smartphone.                           |
| **Episódios**  | 1. [Usuário](../Lexico/lexico.md#usuario) navega até a aba de [séries](../Lexico/lexico.md#serie). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma [série](../Lexico/lexico.md#serie) da [lista](../Lexico/lexico.md#lista-geral). <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio. <br> 4. O [usuário](../Lexico/lexico.md#usuario) marca o episódio como assistido.            |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) deve estar logado. <br> Ter [séries](../Lexico/lexico.md#serie) pré-selecionadas na aba.                      |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) fecha o aplicativo durante a ação.             |

### Notificar o [usuário](../Lexico/lexico.md#usuario) sobre novos episódios {#cen03} 
|   **Título**   | Notificar o [usuário](../Lexico/lexico.md#usuario) sobre novos episódios                          |
| :------------: | ------------------------------------------------------------------ |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) ser notificado sobre um novo episódio da [série](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral). |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) segue uma ou mais [séries](../Lexico/lexico.md#serie).                                |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario), Sistema                                                   |
|  **Recursos**  | Acesso à internet, smartphone                                      |
| **Episódios**  | 1. Um novo episódio da [lista](../Lexico/lexico.md#lista-geral) de [séries](../Lexico/lexico.md#serie) é lançado. <br> 2. O sistema envia uma notificação para o smartphone do [usuário](../Lexico/lexico.md#usuario). <br> 3. O [usuário](../Lexico/lexico.md#usuario) recebe a notificação.                                 |
| **Restrições** | A conta do [usuário](../Lexico/lexico.md#usuario) estar conectada no sistema. <br> Possuir [séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral). <br> O [usuário](../Lexico/lexico.md#usuario) permitir o envio de notificações.                        |
|  **Exceções**  | Não ter conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) desativou o envio de notificações.                       |

### [Favoritar](../Lexico/lexico.md#favoritar) [série](../Lexico/lexico.md#serie) {#cen04}
|   **Título**   | [Favoritar](../Lexico/lexico.md#favoritar) [série](../Lexico/lexico.md#serie)                                                |
| :------------: | -------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) adicionar uma [série](../Lexico/lexico.md#serie) aos [favorito](../Lexico/lexico.md#favorito).                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                         |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                 |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona para adicionar uma [série](../Lexico/lexico.md#serie) aos [favorito](../Lexico/lexico.md#favorito). <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona uma [série](../Lexico/lexico.md#serie) marcando o ícone de coração.  |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) possuir [séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral).                             |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) sai do aplicativo durante a ação.                    |

### [Avaliar](../Lexico/lexico.md#avaliacao) episódio {#cen05}
|   **Título**   | [Avaliar](../Lexico/lexico.md#avaliacao) episódio                                                               |
| :------------: | ------------------------------------------------------------------------------ |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) dar uma nota ao episódio de uma [série](../Lexico/lexico.md#serie).                               |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                         |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                       |
|  **Recursos**  | Acesso à internet, smartphone.                                                 |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [séries](../Lexico/lexico.md#serie). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma [série](../Lexico/lexico.md#serie). <br> 3. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio da [série](../Lexico/lexico.md#serie). <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona o ícone de check para marcar o episódio como assistido. <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona um dos ícones de estrela para [avaliar](../Lexico/lexico.md#avaliacao). |
| **Restrições** | O [usuário](../Lexico/lexico.md#usuario) possuir [séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral). <br> O [usuário](../Lexico/lexico.md#usuario) ter visto o episódio.           |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) sai do aplicativo durante a ação. <br> O [usuário](../Lexico/lexico.md#usuario) não ter assistido o episódio. | 

### [Plataforma](../Lexico/lexico.md#plataforma) utilizada {#cen06}
|   **Título**   | Plataforma utilizada                                                          |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar a [plataforma](../Lexico/lexico.md#plataforma) que assistiu o conteúdo.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [séries](../Lexico/lexico.md#serie). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona uma [série](../Lexico/lexico.md#serie) da [lista](../Lexico/lexico.md#lista-geral). <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca a [série](../Lexico/lexico.md#serie) como assistida. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a [plataforma](../Lexico/lexico.md#plataforma) na qual viu a [série](../Lexico/lexico.md#serie). <br> **Caminho B:** <br> 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [filmes](../Lexico/lexico.md#filme). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona um [filme](../Lexico/lexico.md#filme) da [lista](../Lexico/lexico.md#lista-geral). <br> 3. O [usuário](../Lexico/lexico.md#usuario) marca o [filme](../Lexico/lexico.md#filme) como assistido. <br> 4. O [usuário](../Lexico/lexico.md#usuario) registra a [plataforma](../Lexico/lexico.md#plataforma) na qual viu o [filme](../Lexico/lexico.md#filme). |
|  **Exceções**  | A internet deixa de funcionar. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) não ter [filmes](../Lexico/lexico.md#filme) ou [séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral). |

### [Reação](../Lexico/lexico.md#reacao) do usuário {#cen07}
|   **Título**   | [Reação](../Lexico/lexico.md#reacao) do usuário                                                              |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) registrar sua [reação](../Lexico/lexico.md#reacao).                                               |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) seleciona um conteúdo. <br> 2. O [usuário](../Lexico/lexico.md#usuario) marca qual sua [reação](../Lexico/lexico.md#reacao) acerca do conteúdo. |
|  **Exceções**  | A internet deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.   |

### [Comentar](../Lexico/lexico.md#comentario) conteúdo {#cen08}
|   **Título**   | [Comentar](../Lexico/lexico.md#comentario) conteúdo                                                             |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) fazer o [comentário](../Lexico/lexico.md#comentario) em um conteúdo da aplicação.                     |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | **Caminho A:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [séries](../Lexico/lexico.md#serie).<br>**Caminho A1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica no título da [série](../Lexico/lexico.md#serie).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica no [comentário](../Lexico/lexico.md#comentario) geral da [série](../Lexico/lexico.md#serie).<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>4. O [usuário](../Lexico/lexico.md#usuario) deixa um [comentário](../Lexico/lexico.md#comentario) sobre a [série](../Lexico/lexico.md#serie).<br>5. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B1:**<br>1. O [usuário](../Lexico/lexico.md#usuario) clica na imagem da [série](../Lexico/lexico.md#serie).<br>2. O [usuário](../Lexico/lexico.md#usuario) seleciona um episódio da [série](../Lexico/lexico.md#serie).<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no [comentário](../Lexico/lexico.md#comentario) do episódio.<br>5. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>6. O [usuário](../Lexico/lexico.md#usuario) deixa um [comentário](../Lexico/lexico.md#comentario) sobre o episódio da [série](../Lexico/lexico.md#serie).<br>7. O [usuário](../Lexico/lexico.md#usuario) clica em publicar.<br>**Caminho B:**<br>1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [filmes](../Lexico/lexico.md#filme) vistos.<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em [comentários](../Lexico/lexico.md#comentario).<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em "já vi este [filme](../Lexico/lexico.md#filme)".<br>4. O [usuário](../Lexico/lexico.md#usuario) clica no ícone do lápis.<br>5. O [usuário](../Lexico/lexico.md#usuario) deixa um [comentário](../Lexico/lexico.md#comentario) sobre o filme.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em publicar. |
|  **Exceções**  | O [usuário](../Lexico/lexico.md#usuario) não possuir [filmes](../Lexico/lexico.md#filme) ou [séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-geral). <br> Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O aplicativo deixa de funcionar. |

### Compartilhar [perfil](../Lexico/lexico.md#perfil) {#cen09}
|   **Título**   | Compartilhar [perfil](../Lexico/lexico.md#perfil)                                                           |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar seu [perfil](../Lexico/lexico.md#perfil)                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet. <br> O aplicativo deixa de funcionar. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |

### Escolher foto/capa de [perfil](../Lexico/lexico.md#perfil) {#cen10}
|   **Título**   | Escolher foto/capa de [perfil](../Lexico/lexico.md#perfil)                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) inserir/editar sua foto/capa de [perfil](../Lexico/lexico.md#perfil)                              |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em editar.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica em escolher foto/capa de [perfil](../Lexico/lexico.md#perfil).<br>4. O [usuário](../Lexico/lexico.md#usuario) seleciona uma foto da galeria do dispositivo. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>O [usuário](../Lexico/lexico.md#usuario) não permite que o sistema acesse a galeria do dispositivo. |

### Criar listas {#cen11}
|   **Título**   | Criar listas                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) criar uma [lista](../Lexico/lexico.md#lista-personalizada) de [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie).                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone.                                                |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em "criar uma nova [lista](../Lexico/lexico.md#lista-personalizada)".<br>3. O [usuário](../Lexico/lexico.md#usuario) insere um nome para a [lista](../Lexico/lexico.md#lista-personalizada).<br>4. Se quiser, insere uma descrição.<br>5. Se quiser, pode tornar a [lista](../Lexico/lexico.md#lista-personalizada) opcional.<br>6. O [usuário](../Lexico/lexico.md#usuario) clica em "criar [lista](../Lexico/lexico.md#lista-personalizada)". |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.<br>A [lista](../Lexico/lexico.md#lista-personalizada) já existir. |

### Editar [lista](../Lexico/lexico.md#lista-personalizada) {#cen12}
|   **Título**   | Editar [lista](../Lexico/lexico.md#lista-personalizada)                                                                  |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) editar uma [lista](../Lexico/lexico.md#lista-personalizada).                                                   |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, [lista](../Lexico/lexico.md#lista-personalizada) existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [lista](../Lexico/lexico.md#lista-personalizada) existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em editar detalhes. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. | 

### Excluir [lista](../Lexico/lexico.md#lista-personalizada) {#cen13}
|   **Título**   | Excluir [lista](../Lexico/lexico.md#lista-personalizada)                                                                 |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) excluir uma [lista](../Lexico/lexico.md#lista-personalizada).                                                  |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, [lista](../Lexico/lexico.md#lista-personalizada) existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [lista](../Lexico/lexico.md#lista-personalizada) existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em excluir. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |

### Compartilhar [lista](../Lexico/lexico.md#lista-personalizada) {#cen14}
|   **Título**   | Compartilhar [lista](../Lexico/lexico.md#lista-personalizada)                                                            |
| :------------: | ----------------------------------------------------------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar uma [lista](../Lexico/lexico.md#lista-personalizada).                                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                                                        |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                                                                      |
|  **Recursos**  | Acesso à internet, smartphone, [lista](../Lexico/lexico.md#lista-personalizada) existente.                               |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil).<br>2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [lista](../Lexico/lexico.md#lista-personalizada) existente.<br>3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos.<br>4. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar.<br>5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma rede social para compartilhar. |
|  **Exceções**  | Perda de conexão com a internet.<br>O aplicativo deixa de funcionar.<br>O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. |

### Ocultar conteúdo assistido {#cen15}
|   **Titulo**   | Ocultar conteúdo assistido                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) ocultar os conteúdos já assistidos.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [filmes](../Lexico/lexico.md#filme) ou [séries](../Lexico/lexico.md#serie). <br> 2. O [usuário](../Lexico/lexico.md#usuario) seleciona sua [lista](../Lexico/lexico.md#lista-personalizada). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de task.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> Ter [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie) na [lista](../Lexico/lexico.md#lista-personalizada) geral que já foram vistos. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.                             |

### Localizar conteúdo {#cen16}
|   **Titulo**   | Localizar conteúdo                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) buscar por um [filme](../Lexico/lexico.md#filme) ou [série](../Lexico/lexico.md#serie).                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de descobrir. <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em "Pesquisar [séries](../Lexico/lexico.md#serie) e [filmes](../Lexico/lexico.md#filme)". <br> 3. O [usuário](../Lexico/lexico.md#usuario) insere o nome de um [filme](../Lexico/lexico.md#filme) ou [série](../Lexico/lexico.md#serie). <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona o [filme](../Lexico/lexico.md#filme) ou [série](../Lexico/lexico.md#serie) pesquisado.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interromper o fluxo de execução.     |

### Alterar senha {#cen17}
|   **Titulo**   | Alterar senha                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) alterar sua senha de acesso.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em alterar senha. <br> 5. O [usuário](../Lexico/lexico.md#usuario) insere a senha atual, a nova senha e confirma a nova senha.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui conta.                             |

### Vincular/Desvincular redes sociais {#cen18}   
|   **Titulo**   | Vincular/Desvincular redes sociais                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) vincular/desvincular suas redes sociais no aplicativo.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em "Editar contas vinculadas". <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona uma ou mais redes para vincular/desvincular.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não possui rede social.                             |

### Privar conta {#cen19}
|   **Titulo**   | Privar conta                              |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) tornar sua conta privada.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) seleciona "definir [perfil](../Lexico/lexico.md#perfil) como privado".                          |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução.|

### Sair da conta {#cen20}  
|   **Titulo**   | Sair da conta                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) sair da conta.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | Usuário.                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em sair.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado.                             |

### Traduzir títulos de [séries](../Lexico/lexico.md#serie)/[filmes](../Lexico/lexico.md#filme) {#cen21}
|   **Titulo**   | Traduzir títulos de [séries](../Lexico/lexico.md#serie)/[filmes](../Lexico/lexico.md#filme)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) traduzir os títulos das [séries](../Lexico/lexico.md#serie)/[filmes](../Lexico/lexico.md#filme).                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até app. <br> 6. O [usuário](../Lexico/lexico.md#usuario) clica em "Exibir no seu idioma".                                |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado.   |

### Priorizar idioma dos [comentários](../Lexico/lexico.md#comentario) {#cen22} 
|   **Titulo**   | Priorizar idioma dos [comentários](../Lexico/lexico.md#comentario).                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) selecionar os [comentários](../Lexico/lexico.md#comentario) de determinado idioma.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até app. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em "selecionar os idiomas dos [comentários](../Lexico/lexico.md#comentario)". <br> 6. O [usuário](../Lexico/lexico.md#usuario) seleciona um ou mais idiomas.                              |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O usuário não está logado. |

### Tema claro/escuro {#cen23}   
|   **Titulo**   | Tema claro/escuro                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) trocar o tema.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até app. <br> 5. O [usuário](../Lexico/lexico.md#usuario) seleciona o tema.                            |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Limpar memória {#cen24}  
|   **Titulo**   | Limpar memória                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) limpar o cache de memória do sistema.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até app. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em "limpar cache".  |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado.                             |

### Filtrar emissoras {#cen25} 
|   **Titulo**   | Filtrar emissoras                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) filtrar emissoras.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica no ícone de três pontos. <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em configurações. <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até em breve. <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em filtrar emissoras.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Comparar tempo gasto {#cen26}

|   **Titulo**   | Comparar tempo gasto                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) comparar o tempo gasto em [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie) com seus [seguidores](../Lexico/lexico.md#seguidores).                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em "Compare com as pessoas que você [segue](../Lexico/lexico.md#seguidores)".                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar gráfico de tempo gasto vendo [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie) {#cen27}

|   **Titulo**   | Visualizar gráfico de tempo gasto vendo [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar um gráfico com o tempo gasto vendo [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie).                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica na aba de [filmes](../Lexico/lexico.md#filme). <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza o gráfico com o tempo total assistindo [filmes](../Lexico/lexico.md#filme).                         |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar principais [emissoras](../Lexico/lexico.md#plataforma) de [séries](../Lexico/lexico.md#serie) {#cen28}

|   **Titulo**   | Visualizar principais [emissoras](../Lexico/lexico.md#plataforma) de [séries](../Lexico/lexico.md#serie)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar as principais [emissoras](../Lexico/lexico.md#plataforma) de [séries](../Lexico/lexico.md#serie) que anda consomumindo ultimamente.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica na aba de [séries](../Lexico/lexico.md#serie). <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza as principais [emissoras](../Lexico/lexico.md#plataforma) de [séries](../Lexico/lexico.md#serie) que consome ultimamente.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar principais [gêneros](../Lexico/lexico.md#genero) de [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie) {#cen29}

|   **Titulo**   | Visualizar principais [gêneros](../Lexico/lexico.md#genero) de [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar os principais [gêneros](../Lexico/lexico.md#genero) de [filmes](../Lexico/lexico.md#filme)/[séries](../Lexico/lexico.md#serie) que vem assistindo ultimamente.                            |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica na aba de [filmes](../Lexico/lexico.md#filme). <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza os principais [gêneros](../Lexico/lexico.md#genero) de [filmes](../Lexico/lexico.md#filme) vistos.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Acessar [emblemas](../Lexico/lexico.md#emblema) {#cen30}

|   **Titulo**   | Acessar [emblemas](../Lexico/lexico.md#emblema)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) acessar os [emblemas](../Lexico/lexico.md#emblema) que conquistou.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em [séries](../Lexico/lexico.md#serie).  <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até "[Emblemas](../Lexico/lexico.md#emblema) relacionados ao app". <br> 5. O [usuário](../Lexico/lexico.md#usuario) visualiza [emblemas](../Lexico/lexico.md#emblema) relacionados a assistir, avaliações, [comentários](../Lexico/lexico.md#comentario) e [seguidores](../Lexico/lexico.md#seguidores). <br> 6. O [usuário](../Lexico/lexico.md#usuario) clica em um [emblema](../Lexico/lexico.md#emblema).                            |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. <br> O [usuário](../Lexico/lexico.md#usuario) não possui emblemas. |

### Compartilhar [emblemas](../Lexico/lexico.md#emblema) {#cen31}

|   **Titulo**   | Compartilhar [emblemas](../Lexico/lexico.md#emblema)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) compartilhar um [emblema](../Lexico/lexico.md#emblema) conquistado.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em [séries](../Lexico/lexico.md#serie).  <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até "[Emblemas](../Lexico/lexico.md#emblema) relacionados ao app". <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em um [emblema](../Lexico/lexico.md#emblema). <br> 6. O [usuário](../Lexico/lexico.md#usuario) clica em compartilhar.                            |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. <br> O [usuário](../Lexico/lexico.md#usuario) não possui emblemas. |

### Visualizar total de [séries](../Lexico/lexico.md#serie) adicionadas {#cen32}

|   **Titulo**   | Visualizar total de [séries](../Lexico/lexico.md#serie) adicionadas                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar o total de [séries](../Lexico/lexico.md#serie) adicionadas.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica na aba de [séries](../Lexico/lexico.md#serie). <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza o total de [séries](../Lexico/lexico.md#serie) adicionadas.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar total de [avaliações](../Lexico/lexico.md#avaliacao) feitas {#cen33}

|   **Titulo**   | Visualizar total de avaliações feitas                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar o total de [avaliações](../Lexico/lexico.md#avaliacao) feitas.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [Estatísticas](../Lexico/lexico.md#estatisticas). <br> 3. O [usuário](../Lexico/lexico.md#usuario) navega até [avaliações](../Lexico/lexico.md#avaliacao) feitas. <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza o total de [avaliações](../Lexico/lexico.md#avaliacao) feitas.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar informações sobre um [ator](../Lexico/lexico.md#ator) {#cen34}

|   **Titulo**   | Visualizar informações sobre um [Ator](../Lexico/lexico.md#ator)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar informações sobre um [Ator](../Lexico/lexico.md#ator) específico.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [série](../Lexico/lexico.md#serie) ou [filme](../Lexico/lexico.md#filme). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em um [ator](../Lexico/lexico.md#ator) presente no [elenco](../Lexico/lexico.md#elenco). <br> 4. O [usuário](../Lexico/lexico.md#usuario) visualiza informações sobre o [ator](../Lexico/lexico.md#ator) específico.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar [filmes](../Lexico/lexico.md#filme) e [séries](../Lexico/lexico.md#serie) trabalhados por um [ator](../Lexico/lexico.md#ator) {#cen35}

|   **Titulo**   | Visualizar [filmes](../Lexico/lexico.md#filme) e [séries](../Lexico/lexico.md#serie) trabalhados por um [ator](../Lexico/lexico.md#ator)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar [filmes](../Lexico/lexico.md#filme) e [séries](../Lexico/lexico.md#serie) trabalhados por um [ator](../Lexico/lexico.md#ator) específico.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [série](../Lexico/lexico.md#serie) ou [filme](../Lexico/lexico.md#filme). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em um [ator](../Lexico/lexico.md#ator) presente no [elenco](../Lexico/lexico.md#elenco). <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até a [filmografia](../Lexico/lexico.md#filmografia) do [ator](../Lexico/lexico.md#ator). <br> 5. O [usuário](../Lexico/lexico.md#usuario) visualiza [filmes](../Lexico/lexico.md#filme) e [séries](../Lexico/lexico.md#serie) trabalhados pelo [ator](../Lexico/lexico.md#ator) específico.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Filtrar [filmografia](../Lexico/lexico.md#filmografia) de um [ator](../Lexico/lexico.md#ator) {#cen36}

|   **Titulo**   | Filtrar [filmografia](../Lexico/lexico.md#filmografia) de um [ator](../Lexico/lexico.md#ator)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) filtrar a [filmografia](../Lexico/lexico.md#filmografia) de um [ator](../Lexico/lexico.md#ator) específico.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [série](../Lexico/lexico.md#serie) ou [filme](../Lexico/lexico.md#filme). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em um [ator](../Lexico/lexico.md#ator) presente no [elenco](../Lexico/lexico.md#elenco). <br> 4. O [usuário](../Lexico/lexico.md#usuario) navega até a [filmografia](../Lexico/lexico.md#filmografia) do [ator](../Lexico/lexico.md#ator). <br> 5. O [usuário](../Lexico/lexico.md#usuario) clica em "[Séries](../Lexico/lexico.md#series) e [filmes](../Lexico/lexico.md#filme)" ou "[Séries](../Lexico/lexico.md#series)" ou "[Filmes](../Lexico/lexico.md#filme)". <br> 6. O [usuário](../Lexico/lexico.md#usuario) visualiza a [filmografia](../Lexico/lexico.md#filmografia) filtrada.                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

## Acessar as redes sociais de um [ator](../Lexico/lexico.md#ator) {#cen37}

|   **Titulo**   | Acessar as redes sociais de um [ator](../Lexico/lexico.md#ator)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) acessar as redes sociais de um [ator](../Lexico/lexico.md#ator) específico.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em uma [série](../Lexico/lexico.md#serie) ou [filme](../Lexico/lexico.md#filme). <br> 3. O [usuário](../Lexico/lexico.md#usuario) clica em um [ator](../Lexico/lexico.md#ator) presente no [elenco](../Lexico/lexico.md#elenco). <br> 4. O [usuário](../Lexico/lexico.md#usuario) clica em uma das redes sociais disponíveis do [ator](../Lexico/lexico.md#ator).                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar total de [seguidores](../Lexico/lexico.md#segudiores) e [comentários](../Lexico/lexico.md#comentario) {#cen38}

|   **Titulo**   | Visualizar total de [seguidores](../Lexico/lexico.md#seguidores) e [comentários](../Lexico/lexico.md#comentario)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar o total de [seguidores](../Lexico/lexico.md#seguidores) e [comentários](../Lexico/lexico.md#comentario) feitos em suas [avaliações](../Lexico/lexico.md#avaliacao).                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) visualiza o total de [seguidores](../Lexico/lexico.md#seguidores) que o segue, total de [seguidores](../Lexico/lexico.md#seguidores) que segue e total de [comentários](../Lexico/lexico.md#comentarios).                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |

### Visualizar quem segue o [usuário](../Lexico/lexico.md#usuario) {#cen39}

|   **Titulo**   | Visualizar quem segue o [usuário](../Lexico/lexico.md#usuario)                             |
| :------------: | ---------------------------- |
|  **Objetivo**  | O [usuário](../Lexico/lexico.md#usuario) visualizar quem segue ele.                             |
|  **Contexto**  | O [usuário](../Lexico/lexico.md#usuario) está logado.                             |
|   **Atores**   | [Usuário](../Lexico/lexico.md#usuario).                             |
|  **Recursos**  | Acesso à internet, smartphone.                             |
| **Episódios**  | 1. O [usuário](../Lexico/lexico.md#usuario) navega até a aba de [perfil](../Lexico/lexico.md#perfil). <br> 2. O [usuário](../Lexico/lexico.md#usuario) clica em [seguidores](../Lexico/lexico.md#seguidores).                             |
|  **Exceções**  | Perda de conexão com a internet. <br> O [usuário](../Lexico/lexico.md#usuario) interrompe o fluxo de execução. <br> O [usuário](../Lexico/lexico.md#usuario) não está logado. |