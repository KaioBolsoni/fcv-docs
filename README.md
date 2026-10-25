# FCV Docs

Documentação geral da Plataforma de Benefícios FCV (projeto integrador, 5º período, Faminas).
Aqui fica só o que vale para o sistema inteiro; o que é de uma frente fica no repositório dela.

## Documentos

| Documento | O que tem |
| --- | --- |
| [ADR](arquitetura/ADR_Arquitetura_Tecnologias_FCV.pdf) | Stack e arquitetura da API, do portal e do app |
| [Requisitos](requisitos/Documento_Requisitos_FCV.pdf) | Escopo, requisitos funcionais e não funcionais, casos de uso |
| [Diagrama de classes](modelagem/diagrama_classes_fcv.drawio) | As 10 entidades e como se relacionam (abrir no [draw.io](https://app.diagrams.net)) |

## Repositórios do projeto

| Frente | Repositório | Grupo |
| --- | --- | --- |
| API | [joaovictorcascardo/fcv-backend](https://github.com/joaovictorcascardo/fcv-backend) | Grupo 2 |
| App mobile | [PedroCacador/fundacao-mobile](https://github.com/PedroCacador/fundacao-mobile) | Grupo 1 |
| Portal web | [Samuel-SouzaZz/Frontend- (privado)](https://github.com/Samuel-SouzaZz/Frontend-) | Grupo 3 |

As rotas da API estão documentadas no Swagger: com a API rodando, acesse `http://localhost:3333/api/v1/docs`.
O passo a passo para rodar está no README do `fcv-backend`.

## Equipe

### Grupo 1

| Integrante | GitHub |
| --- | --- |
| Kaio | [KaioBolsoni](https://github.com/KaioBolsoni) |
| Pedro | [PedroCacador](https://github.com/PedroCacador) |
| Diogo | [Diogo03032](https://github.com/Diogo03032) |
| Camily | [camilyolivei](https://github.com/camilyolivei) |

### Grupo 2

| Integrante | GitHub |
| --- | --- |
| João | [joaovictorcascardo](https://github.com/joaovictorcascardo) |
| Caio | [Cai0Braga](https://github.com/Cai0Braga) |
| Gabriel | [gabrielsales007](https://github.com/gabrielsales007) |
| Aryelle | [elle4ry](https://github.com/elle4ry) |

### Grupo 3

| Integrante | GitHub |
| --- | --- |
| Heitor | [HeitorPolastri](https://github.com/HeitorPolastri) |
| Samuel Salazar | [salazarr0](https://github.com/salazarr0) |
| Samuel Souza | [Samuel-SouzaZz](https://github.com/Samuel-SouzaZz) |
| Thales | [thalesfercaetano](https://github.com/thalesfercaetano) |

## Como atualizar

- Mudou um documento: substitua o arquivo na mesma pasta, com o mesmo nome, e faça um commit `docs: atualiza ...`.
  O histórico do GitHub guarda as versões antigas, então não crie cópias como `_v2` ou `_final`.
- Documento novo que vale para o sistema inteiro: coloque na pasta certa e adicione uma linha na tabela de documentos.
- Documento de uma frente só (telas do app, circuito do totem, banco da API): vai no repositório daquela frente.
