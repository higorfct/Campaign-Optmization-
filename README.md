# Projeto 1: Otimização de Campanhas de Marketing com Machine Learning

## 📝 Introdução
Este projeto busca aplicar técnicas de Machine Learning para otimizar campanhas de marketing com base no **Retorno Sobre Investimento (ROI)**. O objetivo é construir um modelo preditivo que auxilie empresas a **tomar decisões mais estratégicas** sobre a alocação de seus orçamentos de marketing, identificando os canais mais rentáveis para maximizar resultados.  
A solução foi desenvolvida com foco em interpretabilidade, reprodutibilidade e potencial de aplicação prática em ambientes de negócio.

## 📊 Dados

Os dados utilizados foram extraídos de um arquivo campaigns.CSV, contendo:

- campaing_id
- budget (orçamento de cada campanha)
- channel (canais através dos quais a campanha ocorre)
- engagement
- ROI (retorno sobre investimento)

Eatapas percorridas:

- Limpeza e tratamento dos dados
- Análise exploratória com scatterplots
- Pré-processamento para modelagem
- Modelagem

---

## 🤖 Modelagem

A modelagem foi feita com o algoritmo de **Regressão Linear**, tendo como **"budget"**, **"channel"** e **"engagement"** como variáveis preditoras e **"ROI"** como variável alvo

📌 **Avaliação do modelo:**  
- **MSE**  
  0.008880675056313457

- **RMSE**  
  0.09423733366513219

- **MAE**  
  0.059717449408166846


Como se pode ver, todas as métricas de avaliação do modelo de **Regressão Linear** mostram que o modelo teve um ótimo desempenho.

---

## 🛠️ Ferramentas utilizadas

O projeto foi desenvolvido utilizando as seguintes ferramentas:

- **Python** – Linguagem principal do projeto
- **Pandas** – Manipulação e análise de dados
- **NumPy** – Operações numéricas e vetoriais
- **Scikit-Learn** – Modelagem preditiva e avaliação com métricas
- **Matplotlib** – Visualizações de dados
- **Google Colab** – Desenvolvimento e prototipagem inicial

---

## ✅ Resultados

- Forte correlação entre investimentos em marketing e vendas como evidenciado pelos gráficos.
- O modelo sugere que o canal **Google** é o mais rentável de todos, com um ROI de 1.60.
- Modelo altamente capaz de prever vendas com base em alocação de orçamento por canal.
- Auxílio direto na decisão de onde investir para maior ROI.

---

## 🧠 Conclusões

O projeto demonstra como Machine Learning pode:

- **Otimizar o ROI** de campanhas publicitárias
- Apoiar **decisões estratégicas** sobre alocação de verba
- Identificar **canais mais eficazes** de marketing

---

## 🔄 Próximos Passos

- Coletar mais dados para refinar a acurácia
- Testar novos algoritmos e abordagens
- Criar interface gráfica (ex: com Streamlit)
- Implementar em ambiente de produção (ex: API ou dashboard)

---

🧑‍💻 **Autor e Contato**

Higor Roberto Coutinho Caetano

**Linkedin**: https://www.linkedin.com/in/higor-caetano-049521136/

**e-mail**: higorfct@gmail.com



