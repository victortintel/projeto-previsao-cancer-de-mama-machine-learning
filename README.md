# Projeto de Machine Learning: Previsão de Câncer de Mama

Este projeto tem como objetivo desenvolver um modelo de machine learning para auxiliar no diagnóstico de câncer de mama com base em características de núcleos celulares.

## 📌 Visão Geral

O câncer de mama é uma das principais causas de morte entre mulheres mundialmente. O diagnóstico precoce pode melhorar significativamente o prognóstico. Este projeto utiliza o dataset Breast Cancer Wisconsin para construir modelos preditivos que classificam tumores como malignos ou benignos.

## 📊 Dataset

O dataset contém 569 amostras com 30 características computadas a partir de imagens digitalizadas de aspirados por agulha fina (FNA) de massas mamárias. As características descrevem propriedades dos núcleos celulares presentes nas imagens.

**Variável Alvo**: diagnóstico (0 = maligno, 1 = benigno)

## 🛠️ Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Bibliotecas:
  - pandas, numpy
  - scikit-learn
  - matplotlib, seaborn
  - XGBoost
  - SHAP

## 📈 Métricas Principais

O modelo final (XGBoost refinado) alcançou:

- Acurácia: 97.66%
- Recall (maligno): 96.30%
- AUC-ROC: 0.995
