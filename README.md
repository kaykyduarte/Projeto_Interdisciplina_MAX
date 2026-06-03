# Projeto_Interdisciplina_MAX

### **Classificação de URLs Phishing utilizando KNN**

*Descrição do Projeto:*

Este projeto tem como objetivo aplicar o algoritmo K-Nearest Neighbors (KNN) para identificar possíveis URLs de phishing. Foram desenvolvidas duas abordagens:

Implementação manual do algoritmo KNN utilizando Python.
Implementação utilizando a biblioteca Scikit-Learn.

### 1.  **01_knn_manual.ipynb**

Implementação manual do algoritmo KNN.

Neste arquivo são realizadas as seguintes etapas:

- Carregamento dos dados.
- Divisão entre treino e teste.
- Cálculo da distância euclidiana.
- Seleção dos k vizinhos mais próximos.
- Votação majoritária para classificação.
- Cálculo da acurácia.
- Construção da matriz de confusão.

### 2.  **02_knn_biblioteca.ipynb**

Implementação do KNN utilizando a biblioteca Scikit-Learn.

Neste arquivo são realizadas as seguintes etapas:

- Carregamento dos dados.
- Divisão dos dados em treino e teste.
- Treinamento do modelo KNeighborsClassifier.
- Realização das previsões.
- Avaliação da acurácia.
- Construção da matriz de confusão.

### 3. **phishing_dataset.csv**

Base de dados utilizada nos experimentos.

O dataset contém características extraídas de URLs e páginas web, permitindo identificar padrões associados a ataques de phishing.

Os atributos representam informações relacionadas ao comportamento da URL e do site analisado.

### 4. **Sobre o conjunto de dados.pdf**

Documento contendo a descrição completa do dataset utilizado.

Inclui:

- Origem dos dados.
- Significado dos atributos.
- Explicação das variáveis.
- Informações sobre a classe alvo.
- Contexto de aplicação em detecção de phishing.

### 5. **curadoria_dados_phishing.ipynb**

- Exploração inicial dos dados.
- Prática com Pandas e NumPy.
- Verificações e análises preliminares do dataset.