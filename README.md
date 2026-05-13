# Sistema de Gestão das Olimpíadas (SGO)

**Disciplina:** Projeto de Software  
**Curso:** Engenharia de Software – PUC Minas  
**Professor:** João Paulo Carneiro Aramuni  
**Autora:** Giovanna Lima Torres Guasch  
**Data:** Maio de 2026  

---

## Descrição do Sistema

Com a realização das Olimpíadas, torna-se necessário um sistema capaz de coordenar os principais aspectos do evento esportivo. O Sistema de Gestão das Olimpíadas (SGO) foi projetado para apoiar o gerenciamento de competições, inscrições de atletas, alocação de locais, registro de resultados e geração de relatórios de medalhas. :contentReference[oaicite:0]{index=0}

---

## Histórias de Usuário

- **US01:** Como administrador, gostaria de cadastrar competições para disponibilizar eventos esportivos no sistema.
- **US02:** Como atleta, gostaria de me inscrever em competições para participar das modalidades olímpicas.
- **US03:** Como organizador, gostaria de alocar locais para evitar conflitos de horário entre competições.
- **US04:** Como administrador, gostaria de registrar os resultados para identificar os atletas vencedores e classificados.
- **US05:** Como administrador, gostaria de gerar relatórios de medalhas para acompanhar o desempenho de cada país.

---

## Regras de Negócio

1. Cada competição possui nome da modalidade, data, horário, local e lista de atletas inscritos.
2. Um atleta pode participar de várias competições, representando apenas um país em cada modalidade.
3. Um local só pode sediar uma competição por vez.
4. Cada resultado registra o vencedor e os atletas classificados em segundo e terceiro lugares.
5. O sistema deve gerar relatórios com medalhas de ouro, prata e bronze por país.

---

# Diagramas UML

## Diagrama de Caso de Uso

<img width="700px" src="https://github.com/GioGuasch/sistema-gestao-olimpiadas/blob/main/imagens/diagrama-de-caso-de-uso.png"/>

---

## Diagrama de Classes

<img width="1000px" src="https://github.com/GioGuasch/sistema-gestao-olimpiadas/blob/main/imagens/diagrama-de-classes.png"/>

---

## Diagrama de Pacotes

<img width="900px" src="https://github.com/GioGuasch/sistema-gestao-olimpiadas/blob/main/imagens/diagrama-de-pacotes.png"/>

---

## Diagrama de Componentes

<img width="1000px" src="https://github.com/GioGuasch/sistema-gestao-olimpiadas/blob/main/imagens/diagrama-de-componentes.png"/>

---

## Diagrama de Implantação

<img width="1000px" src="https://github.com/GioGuasch/sistema-gestao-olimpiadas/blob/main/imagens/diagrama-de-implantacao.png"/>

---

## Estrutura do Repositório

```text
sistema-gestao-olimpiadas/
│
├── README.md
│
├── imagens/
│   ├── diagrama-de-caso-de-uso.png
│   ├── diagrama-de-classes.png
│   ├── diagrama-de-pacotes.png
│   ├── diagrama-de-componentes.png
│   └── diagrama-de-implantacao.png
│
└── modelagens/
    ├── diagrama-de-caso-de-uso.puml
    ├── diagrama-de-classes.puml
    ├── diagrama-de-pacotes.puml
    ├── diagrama-de-componentes.puml
    └── diagrama-de-implantacao.puml
