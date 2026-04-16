# 🗺️ Mapa da Mina: Bússola da Transição Tech

> **"Transformando a paralisia de escolha em um roadmap estratégico e acionável."**

Este projeto é um simulador interativo desenvolvido em **Python** que funciona como uma bússola para profissionais em transição de carreira. Ele organiza a complexidade do ecossistema de tecnologia em um jogo de escolhas lógico, ajudando a definir focos de estudo e alvos de contratação. Algo que vivenciei na pele a quantidade de informações e opções!

---

## 🎯 O Problema vs. A Solução

### O Problema
A migração para TI gera o fenômeno da **Paralisia de Decisão**:
* Excesso de linguagens e frameworks.
* Dificuldade em saber o que é relevante para um iniciante.
* Currículos genéricos que não passam em filtros de vagas específicas.

### A Solução
O **Mapa da Mina** atua como um filtro inteligente que entrega:
1. **Clareza de Atuação:** Define o que cada área faz na prática.
2. **Roadmap de Estudos:** Lista curada de tecnologias prioritárias (Hard Skills).
3. **Direcionamento de Mercado:** Títulos de cargos reais para otimizar a busca no LinkedIn.

---

## 🛠️ Tecnologias e Conceitos Aplicados

Para garantir a escalabilidade e manutenção do projeto, foram aplicados conceitos de **Arquitetura de Software Sênior**:

| Recurso | Descrição |
| :--- | :--- |
| **Python 3.x** | Core engine do simulador. |
| **Data-Driven Architecture** | Uso de dicionários aninhados para separar a lógica do jogo dos dados de carreira. |
| **Modularização** | Divisão de responsabilidades (Lógica, Dados, Utilitários). |
| **Interface CLI** | UI limpa e intuitiva via terminal para melhor experiência do usuário. |

---

## 📂 Estrutura de Pastas (Padrão de Mercado)

```text
tech_path_simulator/
├── data/
│   └── roadmap_data.py    # Base de conhecimento (trilhas e informações)
├── core/
│   └── engine.py          # Motor do jogo e lógica de navegação
├── utils/
│   └── pdf_generator.py   # Script para exportação visual em PDF
├── main.py                # Ponto de entrada do sistema
└── README.md              # Documentação profissional
