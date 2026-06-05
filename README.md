## Habilidades

**Linguagens e Ferramentas**  
Python · SQL · Power BI · Git · Docker

**Bibliotecas e Frameworks**  
Scikit-learn · LightGBM · Pandas · NumPy · FastAPI · MLflow · SHAP · DoWhy · EconML · Optuna · pymoo · Keras · NLTK · Gensim · Evidently · Statsmodels · Pydantic · SciPy · PuLP · Matplotlib · Seaborn

**Métodos**  
Classificação · Regressão · Engenharia de Features · Métodos Ensemble · Otimização Bayesiana · Análise Exploratória de Dados · Teste A/B · Power Analysis · Análise Bayesiana · Análise de Lift · Validação Temporal · Concept Drift · ML em Produção · Rastreamento de Experimentos · Monitoramento de Deriva de Dados · Inferência Causal · Modelagem de DAG Causal · Propensity Score Matching · Double Machine Learning · Efeitos Heterogêneos de Tratamento · Modelagem de Atribuição · Valores de Shapley · Otimização de Budget · Programação Linear Inteira · NLP · Otimização Multiobjetivo · Análise de Pareto · Visualização de Dados · ETL · DAX / Power Query

---

## Projetos

### Causalidade e Decisão

| Projeto | Descrição | Ferramentas |
|---|---|---|
| [Qual Canal Realmente Converte? Modelagem de Atribuição e Otimização de Budget de Mídia](https://github.com/bssju/qual-canal-realmente-converte) | Comparação de quatro modelos de atribuição em canais de mídia paga. O Last-Click supervalorizou o Google Search e ignorou o Display. Com atribuição correta e otimização de alocação, o retorno esperado aumenta 14,3% sem investimento adicional. | Python, SciPy, PuLP, Scikit-learn, Valores de Shapley |
| [Hora Extra Aumenta a Rotatividade? Análise de Inferência Causal](https://github.com/bssju/hora-extra-aumenta-a-rotatividade-de-funcionarios) | Análise para determinar se a hora extra causa diretamente a rotatividade de funcionários ou se outros fatores, como nível do cargo e salário, explicam a relação. Com três métodos independentes de estimação causal, o efeito direto da hora extra sobre a rotatividade foi de +21,1%, confirmado em testes de robustez. | Python, DoWhy, EconML |
| [A Nova Página Converte Mais? Teste A/B com Abordagem Clássica e Bayesiana](https://github.com/bssju/nova-pagina-converte-mais) | Análise completa de experimento A/B em e-commerce (294.478 sessões, 21 dias). Power analysis retrospectivo confirmou poder acima de 99%, portanto a ausência de efeito é conclusiva. Quatro verificações de sanidade (incluindo SRM e KS-test horário), Z-test bilateral (p = 0,19) e análise bayesiana (P(tratamento > controle) de 44%) convergem para a mesma decisão: manter a página atual. | Python, SciPy, Statsmodels, Pandas, NumPy |

### Modelagem Preditiva e Produção

| Projeto | Descrição | Ferramentas |
|---|---|---|
| [Quem Vai Assinar? Propensão de Clientes em Campanhas Bancárias](https://github.com/bssju/marketing-bancario-notebook-propensao) | Modelo de propensão para priorizar contatos em campanha telefônica bancária. O LightGBM captura 44,9% de todas as adesões ligando para apenas 10% da base (lift 4,5x). Inclui tratamento de vazamento de dados, validação temporal com detecção de concept drift e interpretação com SHAP. AUC-ROC: 0,808. | Python, LightGBM, Scikit-learn, SHAP, MLflow, Pandas |
| &nbsp;&nbsp;&nbsp;[API de Propensão: Modelo Bancário em Produção](https://github.com/bssju/marketing-bancario-api-propensao) | Coloca em produção o modelo de propensão do projeto anterior. Inferência em lote e API REST com validação de domínio (Pydantic), autenticação, logging de previsões para monitoramento de drift e carregamento via MLflow Model Registry. | Python, FastAPI, Pydantic, LightGBM, MLflow, Docker |
| [Previsão de Preços de Imóveis: Do Modelo Base à Produção](https://github.com/bssju/1-construcao-do-modelo-base-regressao) | Série em três etapas: modelo base com 236 features (RMSLE 0,12949), otimização com Optuna e seleção multiobjetivo com redução de 65% das features e melhoria de 3,96%, e deploy com API REST, versionamento e monitoramento de drift em Docker (RMSLE 0,12436). | Python, LightGBM, FastAPI, MLflow, Docker, Evidently, Optuna, pymoo |
| [Identificação de Tweets sobre Desastres: Classificação com NLP](https://github.com/bssju/identificacao-de-tweets-sobre-desastres-reais) | Modelo para classificar automaticamente se um tweet relata um desastre real ou não. Limpeza de texto, extração de features linguísticas e combinação de três algoritmos ensemble. F1-Score: 0,80 no Kaggle. | Python, NLTK, Gensim, Word2Vec, Scikit-learn |
| [Reconhecimento de Dígitos Manuscritos: Rede Neural com 98% de Acurácia](https://github.com/bssju/reconhecimento-de-digitos-manuscritos) | Rede neural treinada para identificar dígitos manuscritos (0 a 9) a partir de imagens. Inclui aumento de dados e regularização para evitar overfitting. Acurácia: 98% no Kaggle. | Python, Keras, TensorFlow |

### Análise e Visualização

| Projeto | Descrição | Ferramentas |
|---|---|---|
| [Dashboard de Vendas: Análise de 8.800 Oportunidades no Power BI](https://github.com/bssju/dashboard-de-vendas) | Dashboard interativo construído a partir de dados reais de CRM com 8.800 oportunidades de vendas. Modelagem de 4 tabelas, criação de métricas e visualizações de receita, taxa de conversão (63%) e desempenho por vendedor, produto e região. | Power BI, DAX, Power Query |

---

## Formação

| Grau | Instituição | Período |
|---|---|---|
| MBA em Ciência de Dados, Inteligência Artificial e Analytics | USP/Esalq | 2026 – 2027 (em andamento) |
| Especialização em Ciência de Dados | Unicamp | 2026 – 2027 (em andamento) |
| Pós-Doutorado em Química Analítica | USP / IFSC | 2022 – 2023 |
| Doutorado em Ciências | USP / IQSC | 2018 – 2022 |
| Bacharelado em Química | USP / IQSC | 2013 – 2017 |

---

## Certificações

- Certificado Profissional em Análise de Dados do Google (2026)
- CDPO 3ª ed. Estatística e Otimização para Ciência de Dados e Pesquisa Operacional, ICMC/USP
- Engenharia de Prompt para Engenheiros de Software, MBA USP/Esalq
- Introdução ao Machine Learning com Python, MBA USP/Esalq
- Python: Do Básico ao Avançado com Estudos de Caso, ICMC/USP
- 9ª Escola Avançada de Big Data Analysis, ICMC/USP
- Séries Temporais, Engenharia de Features, Deep Learning, Machine Learning, Pandas, Python, Kaggle

---

## Contato

[LinkedIn](https://linkedin.com/in/julianaburato) · buratojuliana@gmail.com
