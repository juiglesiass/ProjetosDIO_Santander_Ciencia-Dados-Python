# Relatório do Projeto – Dashboard Xbox

## 1. Visão Geral do Projeto

Este projeto tem como objetivo a construção de um **dashboard analítico** para acompanhamento de **assinaturas de serviços Xbox**, permitindo visualizar informações de faturamento, tipos de planos, adesão a passes adicionais (EA Play e Minecraft Season Pass) e impacto de cupons de desconto.

O dashboard foi desenvolvido em **Excel**, utilizando uma base de dados estruturada, cálculos auxiliares e uma aba dedicada à visualização final, seguindo boas práticas de organização e separação entre dados, regras de negócio e apresentação.

---

## 2. Estrutura do Arquivo

O arquivo está organizado nas seguintes abas:

### 2.1 Assets

Aba de apoio visual, utilizada para:

* Elementos gráficos
* Ícones ou imagens de suporte ao dashboard
* Padronização visual

---

### 2.2 Bases

Aba principal de **dados brutos**, que serve como fonte para todas as análises e visualizações.

#### Campos disponíveis:

* **Subscriber ID**: Identificador único do assinante
* **Name**: Nome do assinante
* **Plan**: Tipo de plano contratado (Core, Standard, Ultimate)
* **Start Date**: Data de início da assinatura
* **Auto Renewal**: Indica se a renovação automática está ativa
* **Subscription Price**: Valor do plano principal
* **Subscription Type**: Periodicidade (Mensal, Trimestral, Anual)
* **EA Play Season Pass**: Indica se o passe adicional foi contratado
* **EA Play Season Pass Price**: Valor do EA Play (quando aplicável)
* **Minecraft Season Pass**: Indica se o passe do Minecraft foi contratado
* **Minecraft Season Pass Price**: Valor do passe do Minecraft
* **Coupon Value**: Valor de desconto aplicado
* **Total Value**: Valor final pago pelo cliente

---

### 2.3 Cálculos

Aba destinada às **regras de negócio e métricas**, separando os cálculos da base bruta.

Exemplos de análises realizadas:

* Faturamento total
* Faturamento por tipo de plano
* Total de assinaturas realizadas por mês
* Comparação entre tipos de assinaturas

---

### 2.4 Dashboard

Aba final de **visualização**, onde os dados são apresentados de forma consolidada e intuitiva.

O dashboard permite:

* Análise rápida do faturamento
* Comparação entre planos
* Visualização da adesão a passes extras
* Apoio à tomada de decisão

---

## 3. Dados Utilizados

* Os dados são **estruturados e tabulares**
* Não há conexão com fonte externa
* Todos os dados estão armazenados localmente na aba *Bases*
* Valores e nomes são fictícios

Essa abordagem garante:

* Facilidade de reprodução
* Independência de sistemas externos
* Controle total sobre os dados

---

## 4. Instruções para Reprodução do Projeto

### 4.1 Pré-requisitos

* Microsoft Excel (ou software compatível)
* Conhecimentos básicos de:

  * Fórmulas do Excel
  * Tabelas dinâmicas
  * Gráficos

---

### 4.2 Passo a Passo

1. **Importar ou recriar a base de dados**

   * Inserir os dados conforme a estrutura da aba *Bases*
   * Garantir os mesmos nomes de colunas

2. **Criar a aba de Cálculos**

   * Utilizar Tabelas Dinâmicas
   * Centralizar todas as métricas que alimentarão o dashboard

3. **Construir o Dashboard**

   * Inserir gráficos e indicadores
   * Conectar os gráficos aos cálculos
   * Aplicar filtros, se necessário

4. **Ajustar Layout e Visual**

   * Utilizar a aba *Assets* para padronização
   * Garantir clareza e legibilidade

---

## 5. Considerações Finais

O projeto demonstra uma abordagem organizada para análise de dados em Excel, separando claramente:

* Dados
* Regras de negócio
* Visualização

Essa estrutura facilita a evolução do dashboard, a validação dos resultados e a adaptação para outras ferramentas de BI, como Power BI ou Tableau.
