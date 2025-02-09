# 🩸 **Anemia Classification with Machine Learning** 🧬

![Capa do Projeto](https://github.com/ViniciusKanh/Anemia-Classification-ML/blob/main/4daeb255-0a4d-4fef-9d42-a33c8c455143.webp)

## 📋 **Introdução**

A **anemia** é uma condição médica caracterizada pela diminuição da quantidade de glóbulos vermelhos ou hemoglobina no sangue, afetando a capacidade de transporte de oxigênio no corpo. Existem diversos tipos de anemia, como **anemia ferropriva**, **anemia megaloblástica** e **anemia de células falciformes**. A detecção precoce e precisa dessas condições é essencial para tratamentos adequados.

Com o avanço da tecnologia, a **inteligência artificial (IA)** e, mais especificamente, os modelos de **machine learning (ML)**, têm se mostrado ferramentas eficazes na análise e predição de doenças. No caso da anemia, esses modelos podem ser usados para classificar tipos de anemia com base em exames laboratoriais. Este projeto explora o uso dessas ferramentas para prever e classificar tipos de anemia com base em dados clínicos.

---

## 🚀 **Proposta**

A proposta deste projeto é aplicar **algoritmos de aprendizado supervisionado** para classificar os tipos de anemia utilizando um conjunto de dados clínicos. A classificação será realizada com modelos como **Random Forest** e **Logistic Regression**. Além disso, serão implementadas técnicas de **balanceamento de classes**, como **SMOTE** e **ADASYN**, para lidar com o desbalanceamento presente nos dados.

O processo envolverá pré-processamento e limpeza de dados, análise estatística das variáveis, e o uso de validação cruzada para avaliar a performance dos modelos. O modelo **Random Forest**, por sua robustez e capacidade de lidar com dados complexos, é esperado para produzir os melhores resultados.

---

## 🎯 **Objetivos**

### **Objetivo Geral**

Desenvolver um sistema de **classificação de tipos de anemia** utilizando técnicas de **machine learning**, a fim de prever o tipo de anemia de um paciente de maneira precisa e eficiente.

### **Objetivos Específicos**

1. **Pré-processamento dos dados**: Realizar a limpeza, normalização e balanceamento do conjunto de dados.
2. **Aplicação de técnicas de machine learning**: Utilizar os modelos **Random Forest** e **Logistic Regression** para classificar os tipos de anemia.
3. **Avaliação dos modelos**: Avaliar a performance dos modelos utilizando métricas como **acurácia**, **F1-Score** e a **matriz de confusão**.
4. **Comparação de resultados**: Comparar os resultados obtidos pelos diferentes modelos e escolher o mais adequado para a classificação de anemias.
5. **Validação do modelo**: Realizar **validação cruzada** para garantir a generalização do modelo.

---

## 🔧 **Metodologias**

### **1. Aquisição e Preparação dos Dados**

O conjunto de dados utilizado contém informações sobre exames clínicos, como a contagem de glóbulos vermelhos, hemoglobina, plaquetas, entre outros. O pré-processamento incluirá a eliminação de valores nulos e a identificação de outliers. Também serão aplicadas técnicas de balanceamento, como **SMOTE** e **ADASYN**, para gerar amostras sintéticas para as classes minoritárias.

### **2. Desenvolvimento dos Modelos de Machine Learning**

Serão treinados dois modelos de aprendizado supervisionado:

- **Random Forest**
- **Logistic Regression**

Ambos os modelos serão ajustados e avaliados com o uso de **validação cruzada** para garantir que a performance seja consistente e robusta.

### **3. Avaliação e Comparação dos Modelos**

A avaliação será feita utilizando as métricas de **acurácia**, **F1-Score** e **matriz de confusão**. Além disso, será analisada a importância das variáveis nos modelos para entender quais características mais contribuem para a previsão do tipo de anemia.

### **4. Validação e Ajuste de Hiperparâmetros**

Ajuste de hiperparâmetros será feito usando técnicas de **Grid Search** ou **Randomized Search**. O melhor modelo será selecionado após a comparação de resultados.

### **5. Implementação e Testes Finais**

Após os ajustes e validação, o modelo será testado com novos dados para garantir sua eficácia na predição do tipo de anemia em novos pacientes.

---

## 📊 **Estrutura do Repositório**

- **AnemiaTypesClassification_data.csv**: Conjunto de dados com informações clínicas para a classificação dos tipos de anemia.
- **4daeb255-0a4d-4fef-9d42-a33c8c455143.webp**: Imagem de capa do projeto.
- **README.md**: Documento com descrição do projeto, objetivos e metodologias.

---

## 🖥️ **Tecnologias Utilizadas**

- **Python**
- **Pandas** (para manipulação e análise de dados)
- **Scikit-learn** (para implementação de modelos de machine learning)
- **imbalanced-learn** (para balanceamento das classes com SMOTE e ADASYN)
- **Matplotlib e Seaborn** (para visualização de dados)

---

## 🏁 **Como Usar**

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/SEU_USUARIO/Anemia-Classification-ML.git
    ```

2. **Instale as dependências**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Execute o código** para treinar e testar os modelos:
    ```bash
    python main.py
    ```

---

## 👨‍🔬 **Contribuições**

Este projeto está aberto a contribuições. Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça commit das suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`).
4. Envie para a branch (`git push origin feature/nova-funcionalidade`).
5. Crie um Pull Request.

---

