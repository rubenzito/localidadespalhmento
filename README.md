
# 📊 Trabalho: Medidas de Localidade e Espalhamento

## 📌 Objetivo

Este trabalho, é a primeir aatividade da disciplina Ia Na Industria e  tem como objetivo aplicar conceitos de estatística descritiva, especialmente **medidas de localidade** e **medidas de espalhamento**, a partir da adaptação dos códigos apresentados em aula para uma nova base de dados.

---

## 📁 Estrutura do repositório

O repositório está organizado em dois notebooks:

- **Medidas_de_Localidade.ipynb**  
  → cálculo de média, mediana, moda, quartis e percentis  

- **Medidas_de_Espalhamento.ipynb**  
  → análise de intervalo, variância, desvio padrão, ADD, MAD e IQR  

---

## 🌸 Base de dados utilizada

Foi utilizada a base **Iris**, que contém medidas de flores.

Cada linha representa uma flor, com as seguintes variáveis:

- **sepal_length**: tamanho da parte verde da flor  
- **sepal_width**: largura da parte verde  
- **petal_length**: tamanho da pétala  
- **petal_width**: largura da pétala  
- **species**: tipo da flor  

Essa base é bastante utilizada em estudos de estatística por ser simples e bem estruturada.

---

## 🔄 Adaptação em relação ao exemplo do professor

Nos exemplos do professor, as variáveis representavam tempo e medições industriais.  
Na base Iris, os dados representam tamanhos de partes da flor.

Por isso, foi feita a adaptação de “tempo” para “tamanho”, mantendo a lógica da análise, mas ajustando o contexto para algo coerente com a base utilizada.

A estrutura dos códigos foi mantida o mais próxima possível da original, alterando apenas:

- fonte dos dados  
- nomes das variáveis  
- textos explicativos  

---

## 📊 Medidas de Localidade

Foram calculadas:

- média  
- mediana  
- moda  
- quartis (Q1, Q2, Q3)  
- percentis  

Essas medidas ajudam a entender o valor típico dos dados.

---

## 📈 Medidas de Espalhamento

Foram analisadas:

- mínimo e máximo  
- amplitude (intervalo)  
- variância  
- desvio padrão  
- ADD (desvio absoluto médio)  
- MAD (desvio absoluto mediano)  
- IQR (intervalo interquartil)  

Essas medidas mostram o quanto os dados estão dispersos.

---

## ⚠️ Uso de outliers

Em alguns trechos, foram adicionados valores extremos (outliers) de forma controlada, com o objetivo de observar o impacto nas medidas estatísticas.

Isso permitiu comparar:

- comportamento com dados normais  
- comportamento com presença de outliers  

---

## 📊 Visualizações

Foram utilizados gráficos como:

- histogramas  
- boxplots  
- gráficos comparativos  

Esses gráficos ajudam a visualizar a distribuição dos dados e identificar possíveis valores extremos.

---

## 🧠 Principais observações

- a média é mais sensível a valores extremos  
- a mediana é mais estável (robusta)  
- o desvio padrão aumenta com maior dispersão  
- o MAD sofre menos impacto com outliers do que o ADD  
- o IQR permite identificar outliers de forma visual (boxplot)  

---

## ✅ Conclusão

Foi possível aplicar os conceitos apresentados em aula em uma nova base de dados, mantendo a lógica dos exemplos originais.

A adaptação mostrou que as medidas estatísticas podem ser utilizadas em diferentes contextos, não apenas industriais, mas também em dados biológicos, como no caso da base Iris.