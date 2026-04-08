# 🃏 Super Trunfo - Países (Python Edition)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)

## 💻 Sobre o Projeto

Este projeto é uma recriação em **Python** do clássico jogo de cartas "Super Trunfo", originalmente desenvolvido em C. O objetivo desta refatoração foi aplicar conceitos aprofundados de Lógica de Programação, Estruturas de Decisão e *Clean Code* em uma linguagem de alto nível.

O sistema atua via CLI (Command Line Interface) e permite o cadastro de cartas representando cidades, gerenciando atributos reais e realizando comparações complexas para determinar a carta vencedora.

## ⚙️ Funcionalidades e Níveis de Complexidade

O projeto foi estruturado em três níveis de evolução arquitetural:

- **Nível Novato:** - Cadastro de cartas via terminal.
  - Cálculo automático de Densidade Populacional e PIB per Capita.
  - Comparação simples entre dois atributos diretos usando estruturas `if/else`.

- **Nível Aventureiro:** - Implementação de um Menu Interativo (`match-case`).
  - Comparação dinâmica onde o usuário escolhe o atributo de duelo.
  
- **Nível Mestre:** - Lógica de decisão complexa avaliando dois atributos simultaneamente.
  - Tratamento de Casos Extremos (Edge Cases), como empates absolutos.
  - Otimização do fluxo de dados e menus aninhados.

## 🛠️ Tecnologias e Conceitos Aplicados

- **Linguagem:** Python 3.10+
- **Paradigma:** Programação Estruturada (com transição para abstrações de dados).
- **Conceitos Chave:**
  - Manipulação de I/O (Entrada e Saída).
  - Type Casting (Conversão de Tipos).
  - Operadores Lógicos e Ternários.
  - Estruturas de Controle de Fluxo Avançadas (`match-case`).
