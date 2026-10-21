# FCV Docs

Documentação geral da Plataforma de Benefícios e Relacionamento da Fundação Cristiano Varella (FCV),
projeto integrador do 5º período da Faminas (Programação para Dispositivos Móveis e Robótica Aplicada).

A plataforma substitui o controle de benefícios feito em planilha por três frentes que usam a mesma API:
o app do colaborador e do conveniado, o totem de validação (IoT) e o portal web de gestão da FCV.

Este repositório guarda só o que vale para o sistema inteiro. O que é de uma frente só fica no repositório dela.

## Documentos

| Documento | O que tem | Arquivo |
| --- | --- | --- |
| Arquitetura e tecnologias (ADR) | Stack e padrão de arquitetura da API, do portal e do app | [arquitetura/ADR_Arquitetura_Tecnologias_FCV.pdf](arquitetura/ADR_Arquitetura_Tecnologias_FCV.pdf) |
| Requisitos | Escopo do semestre, 43 requisitos funcionais, 19 não funcionais e diagramas de casos de uso | [requisitos/Documento_Requisitos_FCV.pdf](requisitos/Documento_Requisitos_FCV.pdf) |
| Diagrama de classes | As 10 entidades do sistema, seus campos e como se relacionam | [modelagem/diagrama_classes_fcv.drawio](modelagem/diagrama_classes_fcv.drawio) |

O diagrama de classes é um arquivo do draw.io. Para abrir: acesse [app.diagrams.net](https://app.diagrams.net),
clique em **Abrir de → Dispositivo** e escolha o arquivo baixado daqui.

## Repositórios do projeto

| Frente | Repositório | Grupo |
| --- | --- | --- |
| API | [joaovictorcascardo/fcv-backend](https://github.com/joaovictorcascardo/fcv-backend) | Grupo 2 |
| App mobile | [PedroCacador/fundacao-mobile](https://github.com/PedroCacador/fundacao-mobile) | Grupo 1 |
| Portal web | Samuel-SouzaZz/Frontend- (privado) | Grupo 3 |

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
