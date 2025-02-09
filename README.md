# Introdução

A anemia é uma condição médica caracterizada pela diminuição da quantidade de glóbulos vermelhos ou hemoglobina no sangue, afetando a capacidade de transporte de oxigênio no corpo. Existem diversos tipos de anemia, cada um com causas e características específicas, como a anemia ferropriva, a anemia megaloblástica e a anemia de células falciformes. A detecção precoce e precisa dessas condições é essencial para a implementação de tratamentos adequados.

Com o avanço da tecnologia, a inteligência artificial (IA) e, mais especificamente, os modelos de machine learning (ML), têm se mostrado ferramentas eficazes para a análise e predição de doenças. No caso da anemia, esses modelos podem ser utilizados para classificar diferentes tipos com base em exames laboratoriais, como a contagem de células sanguíneas. Este projeto explora a utilização desses modelos para prever e classificar tipos de anemia com base em um conjunto de dados de exames clínicos.

---

# Proposta

A proposta deste projeto é aplicar algoritmos de aprendizado supervisionado para classificar os tipos de anemia com base em um conjunto de dados clínicos. A classificação será realizada utilizando modelos como **Random Forest** e **Logistic Regression**. Além disso, serão implementadas técnicas de balanceamento de classes para lidar com o desbalanceamento presente no conjunto de dados, utilizando abordagens como **SMOTE** e **ADASYN**.

A metodologia incluirá a pré-processamento e limpeza dos dados, a análise estatística das variáveis, e a utilização de validação cruzada para avaliar a performance dos modelos. Espera-se que o modelo de **Random Forest**, por sua robustez e capacidade de lidar com variáveis complexas, apresente os melhores resultados.

---

# Objetivos

## Objetivo Geral

Desenvolver um sistema de classificação de tipos de anemia utilizando técnicas de machine learning, com base em dados clínicos, a fim de prever o tipo de anemia de um paciente de maneira precisa e eficiente.

## Objetivos Específicos

1. **Pré-processamento dos dados:** Realizar a limpeza, normalização e balanceamento do conjunto de dados.
2. **Aplicação de técnicas de machine learning:** Utilizar os modelos **Random Forest** e **Logistic Regression** para classificar os tipos de anemia.
3. **Avaliação dos modelos:** Avaliar a performance dos modelos utilizando métricas como acurácia, F1-Score e a matriz de confusão.
4. **Comparação de resultados:** Comparar os resultados obtidos pelos diferentes modelos e escolher o mais adequado para a classificação de anemias.
5. **Validação do modelo:** Realizar validação cruzada para garantir a generalização do modelo.

---

# Metodologias

A metodologia do projeto será dividida em várias etapas principais:

## 1. Aquisição e Preparação dos Dados
O conjunto de dados utilizado neste projeto contém informações sobre exames clínicos, como a contagem de glóbulos vermelhos, hemoglobina, plaquetas, entre outros. O pré-processamento incluirá a eliminação de valores nulos e a identificação de outliers. Será aplicado o balanceamento das classes utilizando técnicas como **SMOTE** e **ADASYN**, que geram amostras sintéticas para as classes minoritárias, melhorando a performance do modelo em situações de desbalanceamento.

## 2. Desenvolvimento dos Modelos de Machine Learning
Serão treinados dois modelos de aprendizado supervisionado: **Random Forest** e **Logistic Regression**. Ambos os modelos serão avaliados e ajustados com o uso de validação cruzada para garantir que a performance seja consistente.

## 3. Avaliação e Comparação dos Modelos
A avaliação será feita utilizando as métricas de acurácia, F1-Score e matriz de confusão. Além disso, será analisada a importância das variáveis nos modelos, para entender quais características mais contribuem para a previsão do tipo de anemia.

## 4. Validação e Ajuste de Hiperparâmetros
O ajuste de hiperparâmetros será feito através de técnicas de otimização como **Grid Search** ou **Randomized Search**, visando melhorar a performance dos modelos. Será realizada uma comparação entre os modelos, e o modelo com melhor desempenho será selecionado.

## 5. Implementação e Testes Finais
Após o ajuste final dos parâmetros e a validação dos modelos, o sistema será testado com novos dados para garantir sua eficácia na predição do tipo de anemia de pacientes.
