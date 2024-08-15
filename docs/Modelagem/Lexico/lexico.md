## Histórico de Revisão
---
| Data       | Autor         | Descrição                         | Versão  |
|------------|---------------|-----------------------------------|---------|
| 13/08/2024 |  Eric Rabelo  | Criação do documento e do léxico "Usuário"| 1.0 |
| 14/08/2024 |  Eric Rabelo  | Inserção do léxico LEX02 até o léxico LEX10| 1.1 |
| 15/08/2024 |  Eric Rabelo  | Remoção dos léxicos: "Adicionar conteúdo" e "Marcar como assistido"; Inserção dos léxicos: Avaliação, Episódio, Reação, Comentário, Recomendação, TV Time Score, Favoritar, [estatísticas](#estatísticas), Seguidores e Plataforma; Adição de introdução, objetivo e metodoloia no documento| 2.0 |

## Introdução
--- 
A técnica de léxicos é empregada para garantir que todos os termos e conceitos críticos sejam claramente definidos e compreendidos, promovendo consistência e clareza no desenvolvimento e manutenção do sistema.

## Objetivo
---
O objetivo deste documento é estruturar e definir de forma clara e concisa os termos e conceitos fundamentais do TV Time, facilitando a comunicação e o entendimento entre todos os envolvidos no desenvolvimento e utilização da plataforma. Este léxico serve como uma referência para padronizar o uso dos termos, garantindo consistência e clareza nas funcionalidades do aplicativo, além de auxiliar na documentação e futuras implementações.

## Metodologia
---
A elaboração deste documento foi fundamentada na coleta e análise de requisitos por meio de técnicas de observação e análise de protocolos. Essas técnicas permitiram a identificação detalhada das necessidades e funcionalidades do sistema, possibilitando a definição precisa dos termos e conceitos essenciais.

## Léxicos
 
- [LEX01 - Usuário](#usuário) 
- [LEX02 - Lista geral](#lista-geral)
- [LEX03 - Lista personalizada](#lista-personalizada)
- [LEX04 - Favorito](#favorito)   
- [LEX05 - Filme](#filme)
- [LEX06 - Série](#série)
- [LEX07 - Perfil](#perfil)
- [LEX08 - Avaliação](#avaliação)
- [LEX09 - Episódio](#episódio)
- [LEX10 - Reação](#reação)
- [LEX11 - Comentário](#comentário)
- [LEX12 - Recomendação](#recomendação)
- [LEX13 - TV Time Score](#tv-time-score)
- [LEX14 - Favoritar](#favoritar)
- [LEX15 - Etatísticas](#estatísticas)
- [LEX16 - Seguidores](#seguidores)
- [LEX17 - Plataforma](#plataforma)
---

### Usuário

| Nome     | Usuário  |
|----------|----------|
| **Classificação** | Sujeito  |
| **Sinônimo** | [usuário](#usuário)s, espectadores |
| **Noção** | O [usuário](#usuário) possui uma conta e utiliza o TV Time para rastrear, avaliar, discutir, e organizar conteúdos audiovisuais, como [séries](#série) e [filmes](#filme). |
| **Impacto** | - O [usuário](#usuário) rastreia seus programas de TV e [filmes](#filme) assistidos, podendo marcá-los como assistidos em sua [lista geral](#lista-geral) ou [listas personalizadas](#lista-personalizada).<br>- O [usuário](#usuário) avalia e classifica os [episódios](#episódio) e [filmes](#filme) que assistiu, atribuindo uma [nota](#nota-do-conteúdo) com base em uma escala de 1 a 5 estrelas, o que contribui para o cálculo da nota do conteúdo.<br>- O [usuário](#usuário) pode adicionar uma [reação](#reação) aos [episódios](#episódio) e [filmes](#filme), escolhendo entre emojis que representam como ele se sentiu durante o conteúdo, como triste ou chocado.<br>- O [usuário](#usuário) participa ativamente das discussões, podendo comentar em [filmes](#filme), [séries](#série) ou [episódios](#episódio), com textos, imagens e GIFs. Esses [comentários](#comentário) podem ser curtidos e comentados por outros [usuário](#usuário)s, sendo a quantidade e os comentários feitos visíveis em seu [perfil](#perfil).<br>- O [usuário](#usuário) pode personalizar seu [perfil](#perfil) e organizar seus conteúdos em [favoritos](#favorito) e listas personalizadas, que são exibidos em seu [perfil](#perfil).<br>- O [usuário](#usuário) tem acesso a [recomendações](#recomendação) de conteúdos baseadas em seus gostos, visualizadas na aba "Descobrir". Ele também pode ver o [TV Time Score](#tv-time-score), que indica a probabilidade de gostar de uma [série](#série) ou [filme](#filme).<br>- As [estatísticas](#estatísticas) do [usuário](#usuário) são exibidas em seu [perfil](#perfil), mostrando dados como tempo total assistido de [séries](#série) e [filmes](#filme), [episódios](#episódio) assistidos e comparações em um ranking com as pessoas que ele segue.<br>- O [usuário](#usuário) pode seguir outros [usuário](#usuário)s e visualizar um ranking de seguidores, baseado no tempo total de conteúdos assistidos.<br>- Ao acessar uma [série](#série) ou [filme](#filme), o [usuário](#usuário) pode ver onde o conteúdo está disponível para assistir, em plataformas de streaming ou canais de TV, contribuindo para a monetização do TV Time por meio de comissões de redirecionamento.|

---

### Lista Geral

| Nome     | Lista geral  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Lista default, lista padrão |
| **Noção** | Uma lista automática que armazena todos os [[filmes](#filme)](#filme) e [séries](#série) que o [usuário](#usuário) marcar para adicionar. Existem duas listas padrão: uma para [séries](#série) e outra para [[filmes](#filme)](#filme). |
| **Impacto** |  - Todos os conteúdos adicionados pelo [usuário](#usuário) são organizados na lista geral conforme seu status.<br>- A lista geral permite que o [usuário](#usuário) filtre conteúdos por status para melhor gerenciamento do que está assistindo ou planeja assistir. |

---

### Lista Personalizada

| Nome     | Lista personalizada  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Lista customizada, lista particular |
| **Noção** | Lista criada pelo [usuário](#usuário) para organizar [[filmes](#filme)](#filme) e [séries](#série) de acordo com suas preferências pessoais, como gêneros ou temas específicos. |
| **Impacto** | - O [usuário](#usuário) pode criar, editar e deletar listas personalizadas para organizar seus conteúdos de forma específica.<br>- As listas personalizadas permitem que o [usuário](#usuário) categorize seus conteúdos além da [lista geral](#lista-geral), proporcionando uma experiência de organização mais flexível.<br>- As listas personalizadas podem ser visualizadas no [perfil](#perfil) do [usuário](#usuário). |

---

### Favorito

| Nome     | [favorito](#favorito) |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Favorito, preferido |
| **Noção** | Conteúdo ([série](#série) ou [filme](#filme)) marcado como [favorito](#favorito)pelo [usuário](#usuário) no TV Time, armazenado na aba de [favoritos](#favorito) em seu [perfil](#perfil). |
| **Impacto** | - Um conteúdo marcado como [favorito](#favorito)é destacado na aba de [favoritos](#favorito) no [perfil](#perfil) do [usuário](#usuário).<br>- Os [favoritos](#favorito) permitem que o [usuário](#usuário) organize e acesse rapidamente seus programas e [[filmes](#filme)](#filme) preferidos. |

---

### Filme

| Nome     | Filme  |
|----------|----------|
| **Classificação** | Objeto  |
| **Sinônimo** | Longa-metragem |
| **Noção** | Produção audiovisual de longa-metragem que o [usuário](#usuário) pode adicionar, assistir e avaliar no TV Time. |
| **Impacto** | - O [usuário](#usuário) pode adicionar o [filme](#filme) à sua [lista geral](#lista-geral) ou [listas personalizadas](#lista-personalizada).<br>- O [filme](#filme) adicionado à [lista geral](#lista-geral) pode ter os status: não assistido e assistido.<br>- O [filme](#filme) pode ser marcado como favorito, adicionando-o à aba de [favoritos](#favorito) no [perfil](#perfil) do [usuário](#usuário).<br>- O tempo dedicado a assistir [[filmes](#filme)](#filme) é exibido no [perfil](#perfil) do [usuário](#usuário), junto com o número de [[filmes](#filme)](#filme) assistidos. |

---

### Série

| Nome   | Série |
|----------|----------|
| **Classificação** | Objeto  |
| **Sinônimo** | [Programa de TV](#série), show |
| **Noção** | Produção audiovisual em formato de [episódios](#episódio) que o [usuário](#usuário) pode adicionar, assistir e avaliar no TV Time. |
| **Impacto** | - O [usuário](#usuário) pode adicionar a [série](#série) à sua [lista geral](#lista-geral) ou [listas personalizadas](#lista-personalizada).<br>- A [série](#série) adicionada à [lista geral](#lista-geral) pode ter status como assistindo, não iniciada, assistir depois, assistida, ou interrompida.<br>- A [série](#série) pode ser marcada como favorita, adicionando-a à aba de [favoritos](#favorito) no [perfil](#perfil) do [usuário](#usuário).<br>- O tempo dedicado a assistir [séries](#série), assim como o número de [episódios](#episódio) assistidos, é exibido no [perfil](#perfil) do [usuário](#usuário). |

---

### Perfil

| Nome     | Perfil  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Conta do [usuário](#usuário), página do [usuário](#usuário) |
| **Noção** | Página pessoal do [usuário](#usuário) no TV Time, exibindo sua foto, capa, número de seguidores e seguidos, comentários feitos, tempo assistindo [séries](#série) e [filmes](#filme), número de [episódios](#episódio) e [filmes](#filme) assistidos, [listas personalizadas](#lista-personalizada), [lista geral](#lista-geral), e [favoritos](#lex04). |
| **Impacto** | - O [usuário](#usuário) pode visualizar e gerenciar suas atividades e preferências no [perfil](#perfil).<br>- O [perfil](#perfil) apresenta um resumo das interações do [usuário](#usuário) com o conteúdo, incluindo o tempo dedicado e os [favoritos](#favorito).<br>- Permite que outros [usuários](#usuário) vejam as preferências e atividades do [usuário](#usuário). |


---

### Avaliação

| Nome     | Avaliação  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Rating, Classificação |
| **Noção** | A pontuação atribuída pelo [usuário](#usuário) a um [filme](#filme) ou episódio de [série](#série) que assistiu, utilizando uma escala de 1 a 5 estrelas. |
| **Impacto** | - A nota do conteúdo reflete a opinião do [usuário](#usuário) sobre o episódio ou [filme](#filme) assistido.<br>- A nota é usada para calcular uma média geral, que pode ser exibida no [perfil](#perfil) do conteúdo no TV Time.<br>- A avaliação influencia as recomendações e o algoritmo de popularidade do TV Time, ajudando outros [usuários](#usuário) a descobrirem novos conteúdos. |

---

### Episódio

| Nome     | Episódio  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Capítulo, parte |
| **Noção** | Unidade de conteúdo pertencente exclusivamente a [séries](#série). Cada episódio contém uma sinopse, nota, resumo e comentários. |
| **Impacto** | - O [usuário](#usuário) pode avaliar e classificar cada episódio individualmente, contribuindo para a nota geral da [série](#série).<br>- [episódios](#episódio) assistidos podem ser marcados como tal, com a opção de marcar automaticamente todos os anteriores ao último episódio assistido.<br>- Os [episódios](#episódio) assistidos são contabilizados nas [estatísticas](#estatísticas) de tempo assistido e número de [episódios](#episódio) visualizados no [perfil](#perfil) do [usuário](#usuário). |

---

### Reação

| Nome     | Reação  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Emoção, sentimento |
| **Noção** | Expressão emocional do [usuário](#usuário) sobre um [episódio](#episódio) ou [filme](#filme) assistido, utilizando emojis que representam diferentes estados emocionais, como triste, chocado, feliz, entre outros. |
| **Impacto** | - O [usuário](#usuário) pode selecionar um emoji que melhor representa sua reação ao conteúdo assistido, permitindo uma forma rápida e visual de compartilhar como se sentiu.<br>- As reações contribuem para a análise e discussão sobre o impacto emocional dos [episódios](#episódio) e [filmes](#filme) entre os [usuários](#usuário). |

---

### Comentário

| Nome     | Comentário  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Post, observação |
| **Noção** | Texto, imagem, ou GIF postado pelo [usuário](#usuário) sobre um [filme](#filme), [série](#série), ou [episódio](#episódio) assistido, expressando opiniões, reações, ou reflexões sobre o conteúdo. |
| **Impacto** | - O [usuário](#usuário) pode compartilhar seus pensamentos e opiniões em comentários, enriquecendo a discussão sobre o conteúdo assistido.<br>- Comentários podem incluir textos, imagens e GIFs, proporcionando uma maneira diversificada de expressão.<br>- Outros [usuários](#usuário) podem curtir e responder aos comentários, fomentando a interação e o engajamento na comunidade.<br>- A quantidade de comentários feitos por um [usuário](#usuário) e os comentários específicos podem ser visualizados no [perfil](#perfil) do [usuário](#usuário). |

---

### Recomendação

| Nome     | Recomendação  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Sugestão, indicação |
| **Noção** | Sugestões de [séries](#série) e [filmes](#filme) oferecidas ao [usuário](#usuário) com base em seu histórico de visualizações e preferências, exibidas na aba "Descobrir". As recomendações incluem as categorias: "Principais [séries](#série) para você", "[filmes](#filme) em alta", e "Séries em alta". |
| **Impacto** | - As recomendações ajudam o [usuário](#usuário) a descobrir novos conteúdos que se alinham com seus gostos e preferências.<br>- O [TV Time Score](#tv-time-score), um indicador que vai de 0 a 100%, é exibido quando o [usuário](#usuário) acessa uma [série](#série) ou [filme](#filme) não visto anteriormente, indicando a probabilidade de o [usuário](#usuário) gostar daquele conteúdo.<br>- A aba "Descobrir" oferece uma variedade de recomendações para facilitar a exploração de novos conteúdos. |

---

### TV Time Score

| Nome     | TV Time Score  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Score de recomendação |
| **Noção** | Um indicador que varia de 0 a 100%, exibido quando o [usuário](#usuário) acessa uma [série](#série) ou [filme](#filme) ainda não visto. Esse indicador estima a probabilidade de o [usuário](#usuário) gostar daquele conteúdo, com base em seu histórico de visualizações e preferências. |
| **Impacto** | - O TV Time Score oferece ao [usuário](#usuário) uma indicação rápida sobre o quão compatível aquele conteúdo é com seus gostos pessoais.<br>- Quanto maior a pontuação, maior a chance de o [usuário](#usuário) gostar do conteúdo, auxiliando na decisão de assistir ou não à [série](#série) ou ao [filme](#filme).<br>- O TV Time Score é uma ferramenta importante para personalizar a experiência do [usuário](#usuário) na plataforma, fornecendo recomendações mais precisas. |

---

### Favoritar

| Nome     | Favoritar |
|----------|----------|
| **Classificação** | Verbo  |
| **Sinônimo** | Curtir |
| **Noção** | Ação de marcar uma [série](#série) ou [filme](#filme) como [favorito](#favorito) no TV Time, adicionando-o na aba respectiva de [favoritos](#favorito) em seu [perfil](#perfil).  |
| **Impacto** | - Ao favoritar um conteúdo, ele é adicionado à aba de [favoritos](#favorito) no [perfil](#perfil) do [usuário](#usuário).<br>- O [usuário](#usuário) pode acessar facilmente seus [favoritos](#favorito) através da aba específica em seu [perfil](#perfil). |

--- 

### Estatísticas

| Nome     | Estatísticas|
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Métricas, Dados de visualização |
| **Noção** | Informações que mostram o tempo total assistido em [séries](#série) e [filmes](#filme), o número de [episódios](#episódio) e [filmes](#filme) assistidos, exibidos no [perfil](#perfil) do [usuário](#usuário). |
| **Impacto** | - Exibe dados detalhados sobre o tempo total assistido, separados por [séries](#série) e [filmes](#filme), assim como o número de [episódios](#episódio) e [filmes](#filme) assistidos.<br>- O [usuário](#usuário) pode acessar uma página dedicada de [estatísticas](#estatísticas) para ver dados adicionais, como [séries](#série) e [filmes](#filme) assistidos por mês.<br>- O app permite comparar o tempo de visualização com outras pessoas que o [usuário](#usuário) segue, através de um ranking. |

---

### Seguidores

| Nome     | Seguidores  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Amigos |
| **Noção** | [Usuários](#usuário) que seguem o [perfil](#perfil) de outro [usuário](#usuário) no TV Time, permitindo acompanhar suas atividades e interações no app. |
| **Impacto** | - Os seguidores podem ver as atividades, listas, [favoritos](#favorito) e [estatísticas](#estatísticas) do [usuário](#usuário) que seguem.<br>- O número de seguidores é exibido no [perfil](#perfil) do [usuário](#usuário), junto com a lista de pessoas que o [usuário](#usuário) segue.<br>- O TV Time permite comparar o tempo que um [usuário](#usuário) assistiu [séries](#série) e [filmes](#filme) com o tempo de seus seguidores, apresentando esses dados em um ranking, incentivando uma competição saudável entre eles. |

---

### Plataforma

| Nome     | Plataforma  |
|----------|----------|
| **Classificação** | Substantivo  |
| **Sinônimo** | Onde assisir, canais disponíveis |
| **Noção** | Indica onde uma [série](#série) ou [filme](#filme) pode ser assistido, mostrando as plataformas de streaming ou canais de TV disponíveis. |
| **Impacto** | - Quando o [usuário](#usuário) acessa a página de uma [série](#série) ou [filme](#filme), ele pode ver onde o conteúdo está disponível para assistir.<br>- A lista inclui tanto plataformas de streaming quanto canais de TV tradicionais.<br>- Ao clicar em uma dessas opções, o [usuário](#usuário) é redirecionado para a plataforma correspondente, permitindo assistir ao conteúdo diretamente.<br>- Essa funcionalidade é uma fonte de monetização para o TV Time, pois a plataforma recebe uma comissão pelas redirecionamentos feitos através do app. |