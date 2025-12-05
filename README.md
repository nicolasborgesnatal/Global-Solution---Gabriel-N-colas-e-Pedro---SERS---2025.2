# EcoWork Energy

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Context](https://img.shields.io/badge/Global%20Solution-FIAP-green)

> **Projeto de análise de dados e simulação energética para otimização de ambientes de trabalho híbridos.**

## 📄 Sobre o Projeto

No contexto do **"Futuro do Trabalho"**, a eficiência energética não é apenas uma questão ambiental, mas estratégica. Este projeto, desenvolvido como parte da **Global Solution**, visa analisar o perfil de consumo de um escritório comercial e simular a implementação de uma matriz energética híbrida (Rede Elétrica + Energia Solar).

O objetivo é demonstrar como a inteligência de dados pode reduzir custos operacionais (OpEx) e a pegada de carbono, alinhando empresas às práticas de ESG.

### 🎯 Objetivos Técnicos (Requisitos Atendidos)
* **Opção A (Análise de Dados):** Identificação de padrões de consumo, desperdícios em horários ociosos e sazonalidade (ar-condicionado).
* **Opção C (Energias Renováveis):** Simulação computacional de um sistema fotovoltaico de 20kWp e seu impacto no balanço energético.

---

## 📊 Resultados Alcançados

A simulação realizada com dados projetados para um período de 12 meses demonstrou:

| Indicador | Cenário Atual | Cenário Proposto (EcoWork) | Impacto |
| :--- | :---: | :---: | :---: |
| **Consumo da Rede** | 118.788 kWh | 71.436 kWh | 📉 **-39,9%** |
| **Custo Anual** | R$ 89.091,00 | R$ 53.577,00 | 💰 **Economia de R$ 35k** |
| **Emissão CO₂** | 10.2 ton | 6.1 ton | 🌱 **-4 ton de CO₂** |

---

## 🛠️ Tecnologias Utilizadas

* **[Python 3](https://www.python.org/)**: Linguagem base para o script de simulação.
* **[Pandas](https://pandas.pydata.org/)**: Manipulação e análise de dados tabulares.
* **[NumPy](https://numpy.org/)**: Cálculos matemáticos e geração de distribuições estatísticas.
* **[Matplotlib](https://matplotlib.org/)**: Visualização de dados e geração de gráficos.

---

## 📂 Estrutura do Repositório

```text
/
├── data/
│   └── dados_energia_projeto.csv   # Dataset gerado pela simulação (Input/Output)
├── docs/
│   └── apresentacao_projeto.pdf    # PDF com a documentação completa
├── src/
│   └── analise_energia.py          # Script principal de simulação e gráficos
├── README.md                       # Documentação do projeto
└── requirements.txt                # Dependências do projeto
