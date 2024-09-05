## Histórico de Revisão
| Data       | Autor         | Descrição                          | Versão |
|------------|---------------|------------------------------------|--------|
| 05/09/2024 | Paulo Henrique Melo de Souza  | Criação da inspeção dos Casos de Uso  | 1.0    |

---

## Metodologia

Utilizando a técnica de inspeção de checklist, cada Caso de Uso foi avaliado individualmente de acordo com tópicos previamente estabelecidos. Sendo que, cada caso de uso será avaliado de forma binária (sim/não) em relação a cada tópico estabelecido. 

## Tópicos de Validação:

1. **Fluxo Principal:** Possui um único fluxo principal?
2. **Fluxos Alternativos:** O caso de uso define claramente mais de um fluxo alternativo?
3. **Fluxo de Exceção:** O caso de uso inclui um fluxo de exceção devidamente especificado?
4. **Título e Descrição:** O título e a descrição estão alinhados e adequados ao caso de uso em questão?
5. **Pré-requisito:** O pré-requisito foi definido de forma simples, clara e objetiva para o entendimento do leitor?
6. **Pós-condição:** O caso de uso inclui uma pós-condição claramente definida?
7. **Relacionamento com Requisitos:** O caso de uso está devidamente relacionado a um ou mais requisitos do sistema?

---

### Lista dos Casos de Uso inspecionados

#### UC01 - Criação de Conta

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Não         | O fluxo alternativo não está devidamente detalhado. |
| **Fluxo de Exceção**              | Não         | -           |
| **Título e Descrição**            | Não         | A descrição não está descrevendo bem o caso de uso.            |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |

#### UC02 - Adicionando Filmes

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Sim         |             |
| **Fluxo de Exceção**              | Não         | Falta um fluxo de exceção para no caso ocorra algum erro na hora de adicionar um filme.            |
| **Título e Descrição**            | Não         | A descrição não está descrevendo bem o caso de uso.            |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |

#### UC03 - Adicionando Séries

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Sim         |             |
| **Fluxo de Exceção**              | Não         | Não possui fluxo de exceção para no casa haja algum impedimento na hora de adicionar uma série.             |
| **Título e Descrição**            | Não         | A descrição não está descrevendo bem o caso de uso.            |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |

#### UC04 - Avaliando Filmes

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Não         | Por mais que tenha um único fluxo alternativo, ele está devidamente detalhado.            |
| **Fluxo de Exceção**              | Sim         |             |
| **Título e Descrição**            | Sim         |             |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |

#### UC05 - Avaliando Séries

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Não         | -           |
| **Fluxo de Exceção**              | Sim         |             |
| **Título e Descrição**            | Sim         |             |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |


#### UC06 - Editando Perfil

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Não         | A falta de um fluxo alternativo afeta no caso do usuário decidir editar outra coisa presente no perfil além do que foi mencionado no fluxo principal.           |
| **Fluxo de Exceção**              | Não         | -           |
| **Título e Descrição**            | Sim         |             |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |

#### UC07 - Pesquisar usuários

| Critérios de Análise              | Satisfeito? | Observações |
|-----------------------------------|-------------|-------------|
| **Fluxo Principal**               | Sim         |             |
| **Fluxos Alternativos**           | Não         | -           |
| **Fluxo de Exceção**              | Sim         |             |
| **Título e Descrição**            | Sim         |             |
| **Pré-requisito**                 | Sim         |             |
| **Pós-condição**                  | Sim         |             |
| **Relacionamento com Requisitos** | Não         | Relacionar o caso de uso com seus respectivos requisitos na matriz de pós-rastreabilidade. |