# 📌 MVP - Visão Macroeconômica e Estrutura Geral
- Foco: O panorama estadual versus São José dos Campos.
## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:
 
- Qual problema resolve? A falta de visualização clara do peso de São José dos Campos na base de empregos do Estado de São Paulo.

- Qual hipótese será validada? Validar que SJC possui uma vocação industrial acima da média estadual.


- Qual valor será entregue? Um dashboard interativo com os KPIs iniciais (estabelecimentos e vínculos) extraídos da base RAIS.  

---

## 📝 Descrição da Solução

- Funcionalidades: Painel no Power BI com cartões de KPIs macroeconômicos e gráficos de vínculos por CNAE.  Limitações: Visão geral do mercado, ainda sem aprofundar na cadeia automotiva específica.Escopo: Tratamento de dados no Google Colab (Python) e importação inicial para o Power BI.  

---

## 👥 Personas / Usuários-Alvo

- Persona 1: Pesquisador Acadêmico buscando entender o panorama de empregabilidade geral de SJC 

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1  | Como pesquisador, quero visualizar os vínculos totais por cidade para comparar SJC com o Estado.       | Alta       | 5 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | ETL em Python e Dashboard Macroeconômico                        | Concluído|

---

## 📊 Critérios de Aceitação
- O sistema deve registrar o total de 14,08 Mi vínculos em SP e 206,72 mil em SJC.  

---

## 📈 Métricas de Validação
- Aprovação técnica da fórmula DAX e da integridade dos dados extraídos da RAIS
 
---

## 🚀 Próximos Passos

- Filtrar os dados especificamente para o setor Automotivo. 

---

## 📂 Anexos / Evidências
> Print: "Dashboard Macroeconômico: Proporção SP vs. SJC"
<img width="945" height="521" alt="image" src="https://github.com/user-attachments/assets/c548be86-b6ab-465a-8a3e-ce47583bd260" />
