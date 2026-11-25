<div align="center">

# 🚜 Fleet Analytics Dashboard

**Dashboard Interativo de Gestão e Análise Operacional de Empilhadeiras**

[![Dashboard Online](https://img.shields.io/badge/🌐_Dashboard-Online-0078D4?style=for-the-badge)](https://caibny.github.io/fleet-analytics-dashboard/)
![Status](https://img.shields.io/badge/Status-Concluído-28A745?style=for-the-badge)
![Dados](https://img.shields.io/badge/Dados-100%25_Fictícios-F59E0B?style=for-the-badge)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SVG](https://img.shields.io/badge/SVG_Charts-FFB13B?style=for-the-badge&logo=svg&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

</div>

---

### 📌 Sobre o Projeto

O **Fleet Analytics Dashboard** é uma aplicação interativa de **Análise de Dados e Business Intelligence** desenvolvida para monitorar a utilização, disponibilidade e eficiência operacional de uma frota industrial de empilhadeiras. 

O projeto centraliza métricas de operação, padrões de ociosidade, comparativos mensais e análise estatística em uma interface responsiva executada diretamente no navegador.

> **⚠️ Aviso de Privacidade:** Todos os dados utilizados neste projeto são **100% sintéticos e fictícios**, gerados exclusivamente para fins de demonstração e portfólio. Nenhuma informação operacional real ou confidencial foi utilizada.

---

### 🌐 Demonstração Online

Acesse a aplicação publicada via GitHub Pages (sem necessidade de instalação):  
👉 **[caibny.github.io/fleet-analytics-dashboard](https://caibny.github.io/fleet-analytics-dashboard/)**

* **Filtros Dinâmicos:** Segmentação em tempo real por **Planta**, **Área** e **Equipamento** individual (com opção de limpeza rápida).
* **Análise Temporal:** Evolução diária de operação (Outubro/2026) e comparativo histórico mensal (Setembro vs. Outubro/2026).
* **Estatística Aplicada:** Matriz de correlação de **Pearson** ($r \in [-1, +1]$) entre horas ligadas, movimento, ociosidade, disponibilidade, OEE e distância percorrida.

---

### 📊 Indicadores Monitorados (KPIs)

| Indicador | Definição & Regra de Cálculo |
| :--- | :--- |
| **Equipamentos** | Total de empilhadeiras ativas no recorte selecionado (base de **70 máquinas**). |
| **Horas Ligadas** | Tempo total em que os equipamentos permaneceram energizados no período. |
| **Horas em Movimento** | Tempo efetivo de deslocamento e atividade produtiva da frota. |
| **Ligado e Parado** | Tempo energizado sem deslocamento (apoio à análise de espera e ociosidade). |
| **Utilização (%)** | Intensidade de uso calculada por: $\text{Utilização} = \left(\frac{\text{Horas Ligadas}}{\text{Horas do Período}}\right) \times 100$. |
| **Disponibilidade (%)** | Capacidade operacional disponível da frota no período analisado. |
| **OEE (%)** | *Overall Equipment Effectiveness* ($\text{Disponibilidade} \times \text{Performance} \times \text{Qualidade}$ — fórmula simplificada ilustrativa). |
| **TEEP (%)** | *Total Effective Equipment Performance* — aproveitamento em relação ao tempo total de calendário. |
| **Distância Percorrida** | Deslocamento acumulado simulado para correlação com intensidade de uso. |

---

### 📈 Visualizações & Análises

* **Painel Executivo (Cards):** Resumo dinâmico dos 6 principais KPIs atualizado conforme os filtros.
* **Evolução Diária:** Comportamento diário de horas ligadas vs. em movimento ao longo de outubro de 2026 (evidenciando dias úteis e finais de semana).
* **Composição do Tempo:** Proporção entre tempo produtivo em movimento e tempo ligado sem movimentação.
* **Ranking & Tabela Detalhada:** Comparativo de horas ligadas entre máquinas e tabela granular com Planta, Horas, OEE e TEEP por equipamento.
* **Matriz de Correlação (Pearson):** Avaliação linear entre variáveis operacionais (*nota: correlação não implica causalidade*).

---

### 🏗️ Arquitetura & Base de Dados

A aplicação adota uma **arquitetura estática *client-side***: os dados sintéticos são processados diretamente no navegador via JavaScript e renderizados em elementos **SVG** nativos, eliminando dependências de servidor, banco de dados ou bibliotecas externas.

```text
Dados Sintéticos (JSON/JS) ──▶ Motor de Cálculo (JS) ──▶ Gráficos SVG & Tabelas ──▶ GitHub Pages
