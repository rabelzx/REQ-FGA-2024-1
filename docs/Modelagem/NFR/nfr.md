## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
|--------|-----------|-------------|---------|------|
| 1.0 | Criação de documento acerca do NFR | Danilo Naves do Nascimento | |  21/08 |
| 1.1 | Descrição de NFR | Danilo Naves do Nascimento | | 22/08 |

## NFR Framework

O NFR (Non-Functional Requirements) Framework é uma ferramenta útil na engenharia de requisitos para lidar com requisitos não funcionais (como desempenho, segurança, usabilidade, etc.). Ele permite a modelagem desses requisitos como softgoals, que podem ser refinados e relacionados entre si para entender como as decisões impactam o sistema.

## Impactos

<center>

![Legenda - Impactos](../../images/modelagem/NFR/Icons_NFR.svg)

</center>

> Referências: CHUNG, L., et al. Non-Functional Requirements in Software Engineering. Springer, 2000. CHUNG, L. "Representing and Using Non-Functional Requirements: A Process-Oriented Approach." In: Requirements Engineering Journal, vol. 2, no. 1, 1997, pp. 55-73.

Especificações dos Impactos:

- <strong>Aceito:</strong> Softgoal pode ser cumprido segundo a análise, portanto, escolhido para ser implementado. 

- <strong>Negado:</strong> Softgoal não pode ser cumprido segundo a análise, portanto, não escolhido para ser implementado

- <strong>Conflito:</strong> Existem conflitos de interesse para o cumprimento do softgoal alguns indicadores positivos outros negativos

- <strong>Indefinido:</strong> Realização do softgoal nem pode ser confirmada nem negada.

- <strong>Aceito Parcialmente:</strong> Existem indicadores positivos para o cumprimento do softgoal.

- <strong>Negado Parcialmente:</strong> Existem indicadores contras para o pleno cumprimento do softgoal.

## Contribuições

As contribuições representam as maneiras pelas quais as ações ou características específicas (softgoals de folha) influenciam os requisitos não funcionais mais amplos ou de nível superior (softgoals principais). Essas contribuições podem ser positivas, negativas, ou neutras e são usadas para modelar como diferentes partes do sistema afetam os requisitos gerais.

<center>

![Legenda - Impactos](../../images/modelagem/NFR/contribuicoes_NFR_.png)

> Fonte: Requisitos de Software - Slides Aula 17(Pag. 13)

</center>


|Contribuições | Símbolo | Descrição |
|--------------|---------|-----------|
|Make|++|FILHO com contribuição tão positiva a ponto de satisfazer o PAI sob a perspectiva dos envolvidos.|
|Help|+| FILHO com contribuição positiva parcial, que sozinho não chega a satisfazer o PAI sob a perspectiva dos envolvidos|
|Unknown|?| FILHO não afeta o PAI|
|Hurt|-|FILHO com contribuição negativa parcial, que sozinho não chega a negar o PAI sob a perspectiva dos envolvidos|
|Break|--| FILHO com contribuição tão negativa a ponto de negar o PAI sob a perspectiva dos envolvidos.|
|Some+|Some +| FILHO com contribuição positiva, cuja intensidade não se pode determinar.|
|Some-|Some -| FILHO com contribuição negativa, cuja intensidade não se pode determinar.|
|And|E| "Pai" é satisfeito se, e somente se, todos os "filhos" forem satisfeitos sob a perspectiva dos envolvidos|
|Or|OU| "Pai" é satisfeito se, e somente se, um dos "filhos" é satisfeito sob a perspectiva dos envolvidos|
|Equal|=| Ambos compartilham o mesmo label.|


> Fonte: Requisitos de Software - Slides Aula 17(Pag. 13)


## NFR 1

![Usuabilidade](../../images/modelagem/NFR/NFR1.drawio.svg)
