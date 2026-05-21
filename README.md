# 📊 Sistema de Gestão Financeira e Business Intelligence — CASER Luziânia

[![Goiás Social](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)](https://github.com/seu-usuario)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Google Data](https://img.shields.io/badge/Power_BI-Data_Visualization-yellow)](https://datastudio.google.com/u/0/navigation/reporting)

## 📝 Visão Geral do Projeto
Este projeto consiste no desenvolvimento e implementação de um **Sistema Integrado de Gestão Financeira e Business Intelligence** para o CASER - Luziânia (institucionalizado sob a identidade do Goiás Social). 

O objetivo principal foi centralizar, padronizar e automatizar o controle de fluxo de caixa (entradas e saídas) do mês vigente, permitindo que a gestão administrativa substitua controles descentralizados por uma tomada de decisão baseada em dados em tempo real.

---

## 🛠️ Arquitetura e Componentes do Projeto

O projeto foi dividido em duas grandes frentes integradas:

### 1. Base de Dados e Estruturação (Planilha de Gestão)
* **Identidade Visual e Padronização:** Desenvolvida com cabeçalho institucional e estrutura limpa para garantir a conformidade administrativa.
* **Painel de Análise Mensal:** Localizado de forma estática à esquerda para consolidação rápida dos valores do período atual.
* **Filtros Inteligentes:** Implementação de segmentação por *Data, Tipo, Transação* e *Natureza* para consultas rápidas.
* **Integridade de Dados (Botão ADD +):** Automação via script/macro para inserção de novos registros, o que preserva as fórmulas, formatação e impede a quebra da estrutura da tabela por erro humano.

### 2. Painel de Business Intelligence (Dashboard Interativo)
* **Indicadores de Desempenho (KPIs):** Visualização clara no topo da tela do total de Entradas, Saídas e Saldo Atual.
* **Gráficos Comparativos:** Análise temporal de Entradas vs. Saídas e detalhamento volumétrico de gastos por *Natureza* (Higiene, Horta, Mobiliário, Utilitários, etc.).
* **Tabela de Auditoria:** Inclusão de uma tabela detalhada na base do painel para conferência rápida de lançamentos específicos sem necessidade de abrir a base bruta.
* **Interatividade Total:** Filtros dinâmicos de período e atualização cross-filtering (clicar em uma categoria no gráfico filtra todo o painel).

---

## 🚀 Próximos Passos (Fase de Engenharia de Dados)
Como parte da evolução do projeto dentro do cronograma de Engenharia de Dados, os próximos passos mapeados são:
1.  **Pipeline de ETL com Python (Pandas):** Construir um script para extrair os dados diretamente da planilha, aplicar regras de limpeza (remover linhas vazias, tratar formatos de data e valores) e consolidar os históricos mensais.
2.  **Modelagem em Banco de Dados:** Migrar a carga final do dado limpo para um banco de dados relacional (**PostgreSQL**).

---

## 📂 Estrutura do Repositório

* `/documentos`: Manuais de instrução completos do Dashboard e da Planilha Financeira.
* `/imagens`: Prints do painel de BI e da estrutura da planilha de inputs.
* `/scripts`: (Em desenvolvimento) Scripts Python de automação.

---

## 🧑‍💻 Autor

* **Ryan Gabriel Fernandes Rezende**
* **Contato:** (64) 9 9321-5131
* **LinkedIn:** [(https://www.linkedin.com/in/ryan-rezende-5176312b5/)]
