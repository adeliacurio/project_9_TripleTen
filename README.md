# project_9_TripleTen
Product Analytics project for a Marketing Department to prioritize hypotheses and analyze A/B tests. Used Python and frameworks like RICE/ICE to increase conversion by 17.58%.

---

# Product Analytics: Priorização de Hipóteses e Análise de Teste A/B 👋

## 📋 Descrição do Projeto
Trabalhando em conjunto com o Departamento de Marketing de uma grande loja online, este projeto teve como objetivo otimizar a receita da plataforma. O processo envolveu a triagem estratégica de ideias utilizando frameworks de priorização e a análise estatística rigorosa de um Teste A/B para validar mudanças no produto.

## 🎯 Objetivos Estratégicos
* Priorizar uma lista de hipóteses de marketing para otimizar a conversão.
* Lançar e monitorar um **Teste A/B** para avaliar o impacto das alterações na receita e no comportamento do usuário.
* Aplicar testes de significância estatística para garantir decisões seguras e baseadas em dados.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python.
* **Bibliotecas:** Pandas (processamento de dados), Matplotlib/Seaborn (visualização) e Scipy (estatística inferencial).
* **Técnicas:** Frameworks de priorização (**RICE e ICE**), Testes de Hipóteses (Mann-Whitney) e Análise de Métricas Acumuladas.

## 📉 Metodologia e Insights
1.  **Frameworks RICE/ICE:** Avaliei as hipóteses sob as óticas de Impacto, Confiança e Esforço (ICE), além do Alcance (RICE), garantindo que os recursos fossem investidos nas tarefas mais promissoras.
2.  **Processamento de Dados:** Limpeza de logs de visitas e pedidos, garantindo que usuários não estivessem presentes em ambos os grupos do teste simultaneamente.
3.  **Análise de Teste A/B:** Monitoramento da receita média por usuário e taxas de conversão acumuladas para identificar o momento de estabilidade do teste.
4.  **Rigor Estatístico:** Aplicação do teste de **Mann-Whitney** para tratar a natureza não paramétrica dos dados de pedidos (presença de outliers).

## ✅ Resultados
* **Sucesso na Conversão:** O grupo de teste apresentou um aumento de **17,58% na taxa de conversão** em relação ao grupo de controle.
* **Tomada de Decisão:** Com base na significância estatística alcançada (p-value < 0.05), recomendei a interrupção do teste e a implementação definitiva da variante vencedora.
* **Eficiência Operacional:** A etapa de priorização evitou o desperdício de tempo em testes de baixo impacto, focando nos esforços que trouxeram resultado real.

---

### 💡 Como utilizar este repositório
1. O notebook segue a ordem lógica: Priorização -> Análise do Teste -> Conclusões Estatísticas.
2. Os gráficos de conversão acumulada permitem visualizar a "vitória" do grupo B ao longo do tempo.
