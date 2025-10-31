 ![Imagem do WhatsApp de 2025-09-29 à(s) 17 22 15_7f101fc3](https://github.com/user-attachments/assets/ac8e7dc4-3e5c-481f-b9e5-d2669b35b72a)


# GRUPO LOGISTIFY - API - 3º SEMESTRE

# Índice

* [Projeto API](#Projeto-API)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Ferramentas e Tecnologias Utilizadas](#Ferramentas-e-Tecnologias-Utilizadas)
* [Product Backlog](#Product-Backlog)
* [Sprints](#Sprints)
* [Resultados](#Resultados)
* [Sprint 1](#Sprint-1)
* [Sprint 2](#Sprint-2)
* [Sprint 3](#Sprint-3)
* [Feira de soluções](#Feira-de-soluções)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Alocação de Tarefas com base no DoR](#Alocação-de-Tarefas-com-base-no-DoR)

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Projeto API 

- Segurança viária no Brasil.

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Equipe

|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Bruno        |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-della-corte-4a792233a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Bruno2811)              |
| Scrum Master  |Larissa |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/larissa-alves-422a10213) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Larih13)     |
|  Team Member  | Gabriel                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-alves-3b5aba1ba) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://www.linkedin.com/in/gabriel-alves-3b5aba1ba)   |
|  Team Member  | Paulo      |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/paulo-henrique-b21680306) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Paulo0805)          |

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Objetivo do Projeto

Desenvolver um dashboard interativo em Power BI para análise integrada da segurança viária no Brasil, utilizando bases oficiais como PRF, RENAINF e DATASUS. O projeto visa consolidar informações sobre frota, população, sinistros e mortalidade, permitindo visualizações dinâmicas, rankings de municípios e indicadores de risco. O objetivo é apoiar a tomada de decisões em políticas públicas e contribuir para a conscientização e prevenção de acidentes de trânsito.

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Ferramentas e Tecnologias Utilizadas

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| 1    | Alta       | Como tomador de decisões de politicas públicas, quero uma visualização interativa da frota nacional, apresentando quantidade de veículos por tipo e ano, com filtros por estado e comparativos de evolução histórica para identificar tendências no crescimento da frota.                                                    | 4          | 1      |
| 2    | Alta       | Como tomador de decisões de politicas públicas, quero visualizar dados da população nacional segmentados por estado, ano, faixa etária e gênero com possibilidade de cruzar informações com frota e acidentes, para avaliar riscos e impactos regionais.                                                                    | 3         | 1      |
| 3    | Alta       | Como tomador de decisões de politicas públicas, quero uma visualização consolidada da mortalidade do DATASUS, apresentando evolução temporal com comparativos por gênero, idade e localização para compreender os fatores associados às mortes no trânsito.                                               | 1          | 1      |
| 4  | Alta      | Como tomador de decisões de politicas públicas, quero integrar dados de sinistros da PRF em gráficos e tabelas mostrando tipos de acidentes, gravidade, número de vítimas e óbitos, com filtros por ano, estado e rodovia para apoiar a definição de políticas de prevenção.                                                                                                                                                     | 8        | 2    |
| 5   | Alta      | Como tomador de decisões de politicas públicas, quero mapas e gráficos de tendência por estado e município, destacando áreas críticas com maior concentração de acidentes, permitindo análises comparativas regionais e exportação de relátorios para apoio em reuniões.     | 2          | 2      |
| 6  | Alta      | Como tomador de decisões de politicas públicas, quero indicadoresde de taxa de motorização, relacionando frota de veículos com população por estado e evolução ao longo dos anos, para entender o impacto do crescimento da frota na mobilidade e segurança viária.     | 2          | 2      |
| 7  | Alta      | Como tomador de decisões de politicas públicas, quero indicadoresde de mortalidade por 100mil habitantes, com gráficos comparativos entre estados e séries temporais, para identificar regiões mais críticas e acompanhar se políticas públicas têm reduzido as taxas.     | 2          | 1      |
| 8  | Alta      | Como tomador de decisões de politicas públicas, quero indicadoresde de sinistros por 10 mil veículos, com comparativos anuais e regionais, apresentados em mapa interativo e gráficos de evolução, para medir a gravidade e frequência relativa de acidentes no país.     | 2          | 1      |
| 9  | Alta      | Como tomador de decisões de politicas públicas, quero filtros interativos no Dashboard por tipo de veículo, região, ano e gravidade do acidente, permitindo cruzamento direto com dados de saúde e frota, para análises mais direcionadas.     | 3          | 3      |
| 10  | Média      | Como tomador de decisões de politicas públicas, quero que o Dashboard em PowerBI tenha design padronizado, limpo, responsivo e interativo, facilitando tanto a anásile exploratória quanto a apresentação formal dos resultados.     | 5          | 3      |
| 11  | Média      | Como tomador de decisões de politicas públicas, quero filtros de sazonalidades dos acidentes, óbitos e incidentes, permitindo identificar padrões mensais, períodos de maior risco e sazonalidade regional, para enbasar campanhas de prevenção em épocas críticas.     | 3          | 3      |
| 12  | Baixa      | Como tomador de decisões de politicas públicas, quero botões e menus interativos no Dashboard que facilitem a navegação entre diferentes visões(frota, população, acidentes, indicadores), além da opção de retorno rápido à tela inicial, garantindo praticidade no uso.     | 10          | 3      |

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 03/10/2025 | concluído | [MVP](https://github.com/Larih13/Sprints/blob/Sprint01/Sprint01.md)  |
| 02                | 30/10/2025 | a fazer  | [MVP](https://github.com/Larih13/Sprints/blob/Sprint01/Sprint02.md)  |
| 03                | 14/11/2025 | a fazer  | [MVP](#) |
| Feira de Soluções | 04/12/2025 | a fazer  | [MVP](#) |

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Resultados

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Sprint 1

## Tela 1

<img width="1280" height="720" alt="Design sem nome" src="https://github.com/user-attachments/assets/1e263b56-ea1a-4be0-be4d-d87c7bf7d817" />

## Tela 2

<img width="1280" height="720" alt="Design sem nome (1)" src="https://github.com/user-attachments/assets/38cca6ca-6cac-4ef9-b958-adf907c7cb43" />

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Sprint 2

## Tela 3

![WhatsApp Image 2025-10-31 at 16 56 42](https://github.com/user-attachments/assets/f9050986-424d-4ca0-8655-5ad75d8a7acd)


![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Sprint 3

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Feira de soluções

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Competências desenvolvidas

## Hard Skill (saber tecnológico)

<details>
<summary>Hard Skills desenvolvidas</summary>
  
| Tecnologia/Metodologia | Classificação |
| ---------------------- | ------------- |
| GitHub | ☆ ☆ ☆ ☆ ☆ |
| Gestão de Projetos | ☆ ☆ ☆ ☆ ☆ |
| Scrum Master | ☆ ☆ ☆ ☆ ☆ |
| Prodct Owner | ☆ ☆ ☆ ☆ ☆ |
| Markdown | ☆ ☆ ☆ ☆ ☆ |
| Git Projects | ☆ ☆ ☆ ☆ ☆ |
 
</details>

## Soft Skill (saber comportamental)

<details>
<summary>Soft Skills desenvolvidas</summary>

| Habilidades | Classificação |
| ---------------------- | ------------- |
| Colaboração | ☆ ☆ ☆ ☆ ☆ |
| Proatividade| ☆ ☆ ☆ ☆ ☆ |
| Pensamento Crítico | ☆ ☆ ☆ ☆ ☆ |
| Gerenciamento de Tempo | ☆ ☆ ☆ ☆ ☆ |
| Adaptabilidade | ☆ ☆ ☆ ☆ ☆ |
| Resiliência | ☆ ☆ ☆ ☆ ☆ |

</details>

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

# Alocação de Tarefas com base no DoR

### Divisão das tarefas:
Duplas - cada sprint o BI passará para uma dupla que fará a apresentação da sprint. 

* 1 sprint: Gabriel e Larissa; 
* 2 sprint: Bruno;
* 3 sprint: Paulo.

### Divisão das tarefas "secundárias":
 
* jira - Gabriel;
* Github - Larissa;
* Relatório - Bruno;
* Dashboard - Paulo.

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

* [Volte ao topo](#GRUPO-LOGISTIFY---API---3º-SEMESTRE)

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)
