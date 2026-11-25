# 🚜 Fleet Analytics Dashboard

### Dashboard Interativo de Gestão e Análise de Empilhadeiras

https://img.shields.io/badge/🌐_Dashboard-Online-0078D4?style=for-the-badge](https://caibny.github.io/fleet-analytics-dashboard/)
https://img.shields.io/badge/Status-Concluído-28A745?style=for-the-badge
https://img.shields.io/badge/Dados-100%25_Fictícios-orange?style=for-the-badge

---

## 📌 1. Sobre o Projeto

O **Fleet Analytics Dashboard** é um projeto de análise de dados e Business Intelligence desenvolvido para demonstrar como indicadores operacionais podem auxiliar no monitoramento, na análise e na gestão de uma frota de empilhadeiras.

A aplicação apresenta informações relacionadas à utilização dos equipamentos, disponibilidade operacional, eficiência, movimentação e tempo de atividade.

O objetivo é transformar dados operacionais em informações visuais, organizadas e acessíveis, facilitando a identificação de tendências, padrões de utilização e oportunidades de otimização.

O dashboard possui uma interface inspirada em soluções de Business Intelligence, com indicadores, gráficos interativos, filtros dinâmicos e análises estatísticas.

> **Aviso importante:** todos os dados apresentados neste projeto são fictícios e foram gerados exclusivamente para demonstração. Nenhuma informação operacional real ou confidencial foi utilizada.

---

## 🎯 2. Objetivos do Projeto

O desenvolvimento deste dashboard tem como principais objetivos:

- Centralizar indicadores operacionais em uma única interface.
- Facilitar o acompanhamento da utilização dos equipamentos.
- Analisar a disponibilidade e a eficiência operacional.
- Identificar padrões de movimentação e ociosidade.
- Comparar o desempenho dos equipamentos.
- Explorar correlações entre variáveis operacionais.
- Demonstrar aplicações práticas de análise de dados.
- Desenvolver uma interface interativa para visualização de informações.

A proposta é apresentar como os dados podem contribuir para uma gestão mais analítica, organizada e orientada por indicadores.

---

## 🌐 3. Demonstração Online

O dashboard está publicado utilizando o GitHub Pages.

### 🔗 Acesse o projeto

**https://caibny.github.io/fleet-analytics-dashboard/**

A aplicação pode ser acessada diretamente pelo navegador, sem necessidade de instalação.

### Funcionalidades disponíveis

✅ Visualização de indicadores operacionais.

✅ Filtros interativos por planta, área e equipamento.

✅ Análise de horas ligadas e horas em movimento.

✅ Indicadores de disponibilidade, OEE e TEEP.

✅ Comparação de indicadores entre períodos.

✅ Matriz de correlação estatística.

✅ Tabela detalhada por equipamento.

✅ Interface responsiva.

---

## 📊 4. Indicadores Monitorados

O dashboard reúne indicadores que permitem analisar diferentes aspectos da utilização e eficiência dos equipamentos.

### 4.1 Quantidade de Equipamentos

Apresenta a quantidade de empilhadeiras consideradas na análise.

A base demonstrativa contém **70 equipamentos fictícios**.

O indicador é atualizado conforme os filtros selecionados.

### 4.2 Horas Ligadas

Representa o tempo total em que os equipamentos permaneceram ligados durante o período analisado.

Esse indicador permite:

- Acompanhar o tempo de funcionamento.
- Comparar a intensidade de utilização.
- Identificar diferenças entre equipamentos.
- Avaliar a distribuição das horas de operação.

### 4.3 Horas em Movimento

Representa o período em que os equipamentos permaneceram em movimentação.

Sua análise permite compreender a relação entre o tempo ligado e o tempo efetivamente utilizado em deslocamentos.

### 4.4 Tempo Ligado e Parado

Representa o tempo em que os equipamentos permaneceram ligados sem movimentação.

Esse indicador pode auxiliar na identificação de:

- Períodos de espera.
- Possíveis situações de ociosidade.
- Diferenças nos padrões de utilização.
- Oportunidades de investigação operacional.

É importante destacar que equipamentos parados não representam necessariamente desperdício, pois podem existir necessidades operacionais específicas.

### 4.5 Utilização

Indica a proporção do tempo considerado em que os equipamentos permaneceram ligados.

No conjunto de dados demonstrativo, a utilização é calculada pela relação:

**Utilização = Horas Ligadas / Horas do Período × 100**

O indicador permite comparar a intensidade de utilização entre diferentes equipamentos.

### 4.6 Disponibilidade

Representa um indicador sintético relacionado à disponibilidade operacional dos equipamentos.

Sua utilização permite demonstrar análises sobre a capacidade de disponibilidade da frota.

### 4.7 OEE

**Overall Equipment Effectiveness**

O OEE é um indicador utilizado para analisar a eficiência global de equipamentos.

Tradicionalmente, considera três componentes:

1. Disponibilidade.
2. Performance.
3. Qualidade.

**OEE = Disponibilidade × Performance × Qualidade**

No dashboard demonstrativo, foi utilizada uma fórmula simplificada baseada em disponibilidade e performance.

Portanto, os valores apresentados possuem finalidade exclusivamente ilustrativa e não representam um cálculo industrial completo de OEE.

### 4.8 TEEP

**Total Effective Equipment Performance**

O TEEP é um indicador associado ao aproveitamento da capacidade total disponível em calendário.

Em aplicações industriais, sua análise considera a eficiência do equipamento em relação ao tempo total disponível.

No projeto, o indicador é apresentado por meio de uma simulação simplificada, utilizando o OEE demonstrativo e a utilização sintética.

### 4.9 Distância Percorrida

Representa a distância fictícia percorrida pelos equipamentos durante o período analisado.

Esse indicador permite explorar relações entre movimentação, intensidade de utilização e deslocamento.

---

## 📈 5. Visualizações Disponíveis

### 5.1 Painel de Indicadores

A página inicial apresenta cartões com os principais indicadores:

| Indicador | Descrição |
|---|---|
| Equipamentos | Quantidade de máquinas selecionadas |
| Horas Ligadas | Total de horas ligadas |
| Utilização | Percentual médio de utilização |
| Disponibilidade | Disponibilidade média |
| OEE | Eficiência demonstrativa média |
| TEEP | Aproveitamento demonstrativo médio |

Os valores são atualizados automaticamente conforme os filtros aplicados.

### 5.2 Evolução Diária

Gráfico que apresenta a evolução das horas ligadas e das horas em movimento durante outubro de 2026.

Permite observar:

- Variações diárias.
- Diferenças entre dias úteis e finais de semana.
- Intensidade de utilização ao longo do mês.
- Relação entre funcionamento e movimentação.

### 5.3 Composição do Tempo de Uso

Visualização que demonstra a distribuição entre:

- Tempo em movimento.
- Tempo ligado sem movimentação.

O objetivo é facilitar a interpretação da composição do tempo de funcionamento dos equipamentos.

### 5.4 Comparativo de Equipamentos

Gráfico que apresenta os equipamentos com maior quantidade de horas ligadas.

Permite visualizar diferenças de utilização entre máquinas da frota fictícia.

### 5.5 Comparação Mensal

Visualização comparativa dos indicadores:

- Disponibilidade.
- Performance.
- OEE.
- TEEP.

A demonstração considera dados sintéticos de setembro e outubro de 2026.

### 5.6 Matriz de Correlação

O dashboard apresenta uma matriz de correlação utilizando o coeficiente de Pearson.

Esse coeficiente varia entre -1 e +1.

| Valor | Interpretação |
|---|---|
| Próximo de +1 | Forte correlação positiva |
| Próximo de 0 | Baixa correlação linear |
| Próximo de -1 | Forte correlação negativa |

A matriz permite explorar relações entre:

- Horas ligadas.
- Horas em movimento.
- Horas paradas.
- Disponibilidade.
- OEE.
- Distância percorrida.

**Importante:** correlação não significa causalidade.

Algumas relações também podem ocorrer porque determinados indicadores são calculados a partir de outros.

### 5.7 Detalhamento por Equipamento

Tabela interativa que apresenta informações individuais dos equipamentos.

Inclui:

- Identificação da máquina.
- Planta.
- Horas ligadas.
- Horas paradas.
- OEE.
- TEEP.

---

## 🔎 6. Filtros Interativos

O dashboard permite selecionar diferentes contextos de análise.

### Filtro por Planta

Permite visualizar os indicadores de uma unidade operacional fictícia.

### Filtro por Área

Permite analisar os equipamentos pertencentes a determinada área.

### Filtro por Equipamento

Permite selecionar individualmente uma empilhadeira.

### Limpar Filtros

Restaura a visualização completa da frota demonstrativa.

Todos os gráficos e indicadores são atualizados conforme a seleção realizada.

---

## 🗂️ 7. Base de Dados

O projeto utiliza uma base de dados inteiramente sintética.

### Características

| Característica | Informação |
|---|---|
| Tipo de dados | Fictícios |
| Equipamentos | 70 empilhadeiras |
| Período principal | Outubro de 2026 |
| Período comparativo | Setembro de 2026 |
| Unidades | Quatro unidades fictícias |
| Granularidade diária | Registros por equipamento e dia |
| Finalidade | Demonstração e portfólio |

Os dados foram gerados artificialmente para representar diferentes comportamentos operacionais.

Nenhum dado empresarial real foi utilizado.

---

## 💻 8. Tecnologias Utilizadas

### HTML5

Utilizado para estruturar os elementos da aplicação.

### CSS3

Responsável pela identidade visual, organização dos componentes e adaptação do layout.

### JavaScript

Utilizado para implementar:

- Filtros dinâmicos.
- Cálculos dos indicadores.
- Atualização das visualizações.
- Manipulação dos dados.
- Interatividade da interface.

### SVG

Utilizado para renderizar gráficos e elementos visuais diretamente no navegador.

### GitHub

Utilizado para versionamento e disponibilização pública do código.

### GitHub Pages

Responsável pela hospedagem gratuita do dashboard.

---

## 🏗️ 9. Arquitetura do Projeto

O dashboard utiliza uma arquitetura estática.

Os dados fictícios estão incorporados ao arquivo HTML e são processados diretamente no navegador.

### Fluxo de funcionamento

**Dados Sintéticos → JavaScript → Cálculo dos Indicadores → Gráficos Interativos → Dashboard**

Essa abordagem permite executar a aplicação sem necessidade de:

- Banco de dados.
- Servidor dedicado.
- API externa.
- Instalação de bibliotecas.
- Autenticação.

---

## 📁 10. Estrutura do Repositório

```text
fleet-analytics-dashboard/
│
├── index.html
│   └── Aplicação interativa com dados fictícios
│
└── README.md
    └── Documentação do projeto
