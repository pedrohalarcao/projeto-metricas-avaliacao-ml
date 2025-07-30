# 🧬 Projeto: Predição de Diabetes com Machine Learning

Este projeto tem como objetivo aplicar técnicas de **Machine Learning supervisionado** para desenvolver modelos de **classificação binária**, capazes de prever a ocorrência de **diabetes** com base em indicadores de saúde de pacientes.

---

## 🎯 Objetivo

Construir um pipeline de aprendizado de máquina completo, desde a **exploração e preparação dos dados** até a **validação e avaliação de diferentes modelos**, buscando identificar padrões e variáveis relevantes para a **ocorrência de diabetes**.

---

## 🧪 Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **Google Colab**
- **Pandas** – manipulação de dados
- **NumPy** – operações numéricas
- **Scikit-learn (sklearn)** – modelagem, validação e métricas
- **Seaborn** e **Matplotlib** – visualizações
- **Imbalanced-learn (imblearn.pipeline)** – tratamento de desbalanceamento de classes

---

## 📁 Dataset Utilizado

- Conjunto de dados com informações de saúde (ex: glissemia, pressão sanguínea, IMC, insulina, etc.)
- **Target**: variável binária `diabetes` (0 = não, 1 = sim)

---

## ⚙️ Pipeline do Projeto

1. **Leitura e exploração inicial dos dados**
   - Estatísticas descritivas
   - Visualizações com histogramas e heatmaps.

2. **Modelagem e Avaliação**
   - Treinamento de algoritmos de classificação:
     - **Árvore de Decisão**
     - **Random Forest**
   - **Validação cruzada (K-Fold)**
   - Avaliação com:
     - Matriz de Confusão
     - Acurácia, Precisão, Recall, F1-Score
     - **Curva ROC e AUC**
     - **Curva Precisão-Recall e AP (Average Precision)**

3. **Seleção do Melhor Modelo**
   - Comparação entre os modelos com base nas métricas
   - Escolha do modelo mais robusto para re-treinamento final
   - Geração de **relatório completo com as métricas finais**

---

## 📊 Visualizações Geradas

- **Heatmap** de correlação entre variáveis
- **Histogramas** para entender a distribuição dos dados
- **Curvas ROC** para todos os modelos comparados
- **Curvas precisão-recall** com área sob a curva (AP)
- **Matriz de confusão** para validação dos resultados

---

## ✅ Resultados Obtidos

- Os modelos apresentaram desempenho variado de acordo com o tratamento dos dados e o tipo de balanceamento aplicado.
- O modelo final escolhido apresentou ótimo equilíbrio entre **sensibilidade (recall)** e **precisão**, o que é crucial em contextos médicos.
- O projeto mostra que é possível prever **casos de diabetes** com um bom nível de confiabilidade usando dados básicos de saúde e algoritmos de ML.


---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone git@github.com:pedrohalarcao/projeto-metricas-avaliacao-ml.git
   cd pprojeto-metricas-avaliacao-ml


---

## 👤 Autor

Pedro Alarcão

Entusiasta em análise de dados e aprendizado de máquina, com projetos focados na aplicação prática de IA em problemas do mundo real.


---

## 📌 Observações

Este projeto é de cunho educacional e experimental.
Não substitui diagnósticos médicos ou aplicações clínicas.
Os dados utilizados são simulados para fins acadêmicos.


---

📝 Licença

Este projeto está licenciado sob os termos da licença MIT. Consulte o arquivo LICENSE para mais informações.
