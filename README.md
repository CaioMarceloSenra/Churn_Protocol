# 📊 Churn Protocol: Data-Driven Retention System

> **Status:** MVP Finalizado (Ready for Deploy)
> **Metodologia:** Google Data Analytics Framework (Ask, Prepare, Process, Analyze, Share, Act)

## 💼 O Business Case
A **Unicesumar** enfrentava um desafio de evasão escolar (Churn) tratado de forma reativa, gerando perda de receita recorrente e desperdício de esforço da equipe comercial em leads irreversíveis.
O objetivo deste projeto foi **estruturar a inteligência de dados** para identificar a causa raiz dos cancelamentos e criar estratégias de "Win-Back" (Reconquista) baseadas em segmentação.

---

## 🛠 A Aplicação do Framework Google
Este projeto foi conduzido seguindo rigorosamente as 6 etapas de análise de dados certificadas pelo Google, aplicadas a um cenário real de negócio:

### 1. ❓ Ask (Definição do Problema)
* **Pergunta de Negócio:** "Como podemos diferenciar um churn financeiro (reversível) de um churn geográfico (irreversível) para otimizar o tempo do time comercial?"
* **KPIs Definidos:** Taxa de Reversão (Win-Back Rate), LTV (Lifetime Value) Preservado.

### 2. 📂 Prepare (Coleta de Dados)
* Criação de pipelines de entrada de dados via formulários estruturados (padronização de *inputs*).
* Integração de fontes primárias (motivo declarado) e secundárias (histórico financeiro/CRM).
* Foco em **ROPA** (Reliable, Original, Comprehensive, Current, Cited) para garantir integridade.

### 3. 🧹 Process (Limpeza e Transformação)
* Higienização da base para eliminar viés de preenchimento manual.
* Categorização semântica dos motivos de saída (ex: "Sem dinheiro" -> Categoria: *Financeiro*).
* Verificação de consistência para garantir a precisão da análise (Data Integrity).

### 4. 🔍 Analyze (Análise Exploratória)
* Uso de **Princípio de Pareto (80/20)** para identificar que a minoria dos motivos causava a maioria das perdas.
* Análise de Causa Raiz com visualizações hierárquicas (Sunburst Chart).
* Identificação de padrões ocultos de evasão sazonal.

### 5. 📊 Share (Visualização e Storytelling)
* Desenvolvimento de Dashboards estratégicos com foco em **Acessibilidade** (paletas Okabe-Ito para daltônicos).
* Criação de "User Journeys" distintas para a Gestão (Visão Macro) e Operacional (Listas de Ação).

### 6. 🚀 Act (Plano de Ação)
* **Segmentação:** Criação de ofertas personalizadas (ex: "Desconto" para Financeiro vs. "Tutoria" para Pedagógico).
* **Automação:** Proposta de fluxo para envio automático de leads quentes para o WhatsApp da equipe comercial.

---

## 🔧 Tech Stack
* **Processamento:** Python (Pandas) / Excel Avançado
* **Visualização:** Power BI / Ferramentas de Prototipagem
* **Documentação:** Business Requirements Document (BRD) & Stakeholder Matrix

## 📈 Impacto Projetado
* **Redução de 50%** no tempo de triagem da equipe comercial.
* Potencial de **recuperação de 15%** da receita recorrente perdida (Churn Revenue).
* Implementação de cultura *Data-Driven* na gestão do polo.

---
*Desenvolvido por **Caio Senra** - Analista de Dados & BI*
*[(linkedin.com/in/caio-marcelo-57aba4381)]*
