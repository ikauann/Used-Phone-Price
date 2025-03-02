# PROJETO TURING: PREÇO DE REVENDA DE TELEFONES

## 📌 Principais Descobertas com EDA

### 1️⃣ Marcas consolidadas Têm Maior Valor de Revenda  
Marcas como **Apple, Google e Vivo** mantêm um preço de revenda mais alto. No caso da Vivo, pode estar relacionado à popularidade dos modelos chineses no mercado. Isso sugere que consumidores que buscam um bom valor de revenda devem considerar essas marcas na compra de um novo aparelho.

### 2️⃣ O Tempo Aumenta o Valor de Revenda  
Curiosamente, observamos que, ao longo dos anos, os preços de revenda vêm aumentando. Isso pode indicar um crescimento no mercado de revenda ou uma valorização de determinados modelos (*tenho um viés que seja a valorização*).

### 3️⃣ Conectividade 4G e 5G Elevam o Preço  
Celulares com **4G e 5G** são mais valorizados no mercado de segunda mão. Isso reflete a demanda por aparelhos compatíveis com redes modernas, mostrando que consumidores estão dispostos a pagar mais por conectividade.

### 4️⃣ O Android Apresenta a Maior Variação de Preços  
Diferente do **iOS**, os smartphones **Android** apresentam grandes discrepâncias nos preços de revenda. Isso pode ser explicado pela ampla diversidade de marcas e modelos no ecossistema Android, onde alguns modelos premium retêm valor, enquanto outros depreciam rapidamente.

---

## 📈 Principais Fatores Que Impactam o Preço - Análise de Correlação

### 💰 Fatores que aumentam o preço:
✔ **Tamanho de tela (+62%)** → Telas maiores são mais valorizadas.  
✔ **Bateria (+62%)** → Quanto maior a capacidade da bateria, maior o preço de revenda.  
✔ **Número total de câmeras (+70%)** → Aparelhos com mais câmeras tendem a ter maior valor de revenda.  

### 📉 Fatores que reduzem o preço:
❌ **Dias de uso (-33%)** → Quanto mais tempo o aparelho foi usado, menor o preço de revenda.  
❌ **Idade do dispositivo (-50%)** → Modelos mais antigos desvalorizam mais rápido.  

---

## 🚀 Melhor Modelo de Machine Learning

Testei três modelos e o que apresentou melhor desempenho foi o **XGBoost**, com:

📌 **MAE:** US$ 38,21 → Erro médio absoluto (diferença entre previsão e valor real)  
📌 **RMSE:** US$ 50,28 → Penaliza desvios maiores (avalia precisão global)  
📌 **R²:** 0,83 → O modelo explica **83% da variação dos preços de revenda**  

### 📊 Features mais importantes segundo o modelo:
1️⃣ **Tamanho da tela**  
2️⃣ **Bateria**  
3️⃣ **Número total de câmeras**  
