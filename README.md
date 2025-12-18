# 💳 Credit Risk Prediction

Projeto de **Machine Learning** para prever risco de inadimplência em empréstimos usando dados financeiros e de crédito.

A ideia é direta: **usar dados históricos para identificar clientes com maior chance de não pagar um empréstimo**.

---

## 🧠 O que foi feito

* 🧹 Limpeza e tratamento dos dados
* 🔍 Análise exploratória para entender o perfil dos clientes
* 🚨 Detecção de outliers
* ⚙️ Pré-processamento com pipelines
* 🤖 Treinamento e comparação de modelos de classificação
* 📊 Avaliação do modelo em dados nunca vistos

---

## 📂 Dados

* Dataset baseado nos dados públicos do **Lending Club**
* 📈 8.000 registros
* 🎯 Variável alvo:

  * `0` → empréstimo pago normalmente
  * `1` → empréstimo inadimplente

---

## 🤖 Modelos testados

* ✅ SGDClassifier (modelo final)
* 🌳 Decision Tree
* 🌲 Random Forest
* 📍 KNN

O **SGDClassifier** apresentou o melhor equilíbrio entre desempenho e estabilidade.

---

## 📈 Resultado

* 🚀 Alta acurácia no conjunto de teste
* 🔎 Boa separação entre clientes de baixo e alto risco
* 💡 Modelo com potencial para uso em cenários reais de crédito

---

## 🛠️ Tecnologias

* 🐍 Python
* 📦 Pandas & NumPy
* 🤖 Scikit-learn
* 📊 Matplotlib

---

## 💼 Por que esse projeto importa

Prever inadimplência ajuda instituições financeiras a:

* 💰 reduzir perdas
* 🧠 tomar decisões de crédito mais seguras
* ⚖️ ajustar políticas de aprovação

---

## 🔜 Próximos passos

* 🌐 Transformar o modelo em uma API
* 📉 Criar um score de risco
* 🖥️ Construir uma interface simples para testes
